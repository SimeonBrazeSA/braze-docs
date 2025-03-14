---
nav_title: 사용자 지정 트리거
article_title: iOS용 인앱 메시지 트리거 사용자 지정
platform: Swift
page_order: 6
description: "이 참조 문서에서는 Swift SDK를 위한 커스텀 iOS 인앱 메시징 트리거을 다룹니다."
channel:
  - in-app messages
---

# 커스텀 트리거링

> 기본적으로, 인앱 메시지는 SDK에 의해 기록된 이벤트에 의해 트리거됩니다. 또는 서버 전송 이벤트로 인앱 메시지를 트리거할 수 있습니다.

서버 측 이벤트를 사용하여 인앱 메시지를 트리거하려면 기기에 무음 푸시를 보내 기기가 SDK 기반 이벤트를 기록할 수 있도록 합니다. 이 SDK 이벤트는 이후에 사용자에게 표시되는 인앱 메시지를 트리거할 수 있습니다.

## 1단계: 무음 푸시 및 키-값 쌍 처리

다음 함수를 구현하고 [`application(_:didReceiveRemoteNotification:fetchCompletionHandler:)`: 메서드](https://developer.apple.com/documentation/uikit/uiapplicationdelegate/1623013-application/): 내에서 호출하십시오

{% tabs %}
{% tab swift %}

```swift
func handleExtras(userInfo: [AnyHashable : Any]) {
  print("A push was received")
  if userInfo != nil && (userInfo["IS_SERVER_EVENT"] as? String) != nil && (userInfo["CAMPAIGN_NAME"] as? String) != nil {
    AppDelegate.braze?.logCustomEvent("IAM Trigger", properties: ["campaign_name": userInfo["CAMPAIGN_NAME"]])
  }
}
```

{% endtab %}
{% tab 목표-C %}

```objc
- (void)handleExtrasFromPush:(NSDictionary *)userInfo {
  NSLog(@"A push was received.");
  if (userInfo !=nil && userInfo[@"IS_SERVER_EVENT"] !=nil && userInfo[@"CAMPAIGN_NAME"]!=nil) {
    [AppDelegate.braze logCustomEvent:@"IAM Trigger" properties:@{@"campaign_name": userInfo[@"CAMPAIGN_NAME"]}];
  }
};
```

{% endtab %}
{% endtabs %}

푸시가 수신되면 SDK에서 기록한 이벤트 '인앱 메시지 트리거'가 고객 프로필에 기록됩니다. 

{% alert important %}
푸시 메시지는 SDK에서 기록한 커스텀 이벤트에 사용되기 때문에, Braze는 이 솔루션을 활성화하기 위해 각 사용자의 푸시 토큰을 저장해야 합니다. iOS 사용자의 경우, Braze는 사용자가 OS의 푸시 프롬프트를 받은 시점부터 토큰만 저장합니다. 이전에는 푸시를 사용하여 사용자에게 접근할 수 없으며, 이전 솔루션은 불가능합니다.
{% endalert %}

## 2단계: 무음 푸시 캠페인 생성

서버 전송 이벤트를 통해 트리거되는 [무음 푸시 캠페인]({{site.baseurl}}/developer_guide/platform_integration_guides/swift/push_notifications/silent_push_notifications/)을 생성합니다. 

![사용자 프로필에 사용자 지정 이벤트 "server_event"가 있는 사용자에게 전달되는 액션 기반 전달 인앱 메시지 캠페인입니다.]({% image_buster /assets/img_archive/iosServerSentPush.png %})

푸시 캠페인에는 이 푸시 캠페인이 SDK 커스텀 이벤트를 기록하기 위해 전송되었음을 나타내는 키-값 페어 추가 항목이 포함되어야 합니다. 이 이벤트는 인앱 메시지를 트리거하는 데 사용됩니다.

![두 개의 키-값 쌍을 가진 실행 기반 전달 인앱 메시지 캠페인. "CAMPAIGN_NAME"을 "인앱 메시지 이름 예시"로 설정하고 "IS_SERVER_EVENT"를 "true"로 설정합니다.]({% image_buster /assets/img_archive/iOSServerPush.png %})

`application(_:didReceiveRemoteNotification:fetchCompletionHandler:)` 메서드 내 코드가 `IS_SERVER_EVENT` 키에 있는지 확인하고, 이 키가 존재하면 SDK 커스텀 이벤트를 기록합니다.

푸시 페이로드의 키-값 페어 추가 항목 내에서 원하는 값을 보내 이벤트 이름이나 이벤트 속성정보를 변경할 수 있습니다. 사용자 지정 이벤트를 로깅할 때 이러한 추가 정보는 이벤트 이름의 매개변수 또는 이벤트 속성으로 사용할 수 있습니다.

## 3단계: 인앱 메시지 캠페인 만들기

Braze 대시보드에서 사용자가 볼 수 있는 인앱 메시지 캠페인을 생성하세요. 이 캠페인은 실행 기반 전달을 지원해야 하며 `application(_:didReceiveRemoteNotification:fetchCompletionHandler:)` 메서드 내에서 기록된 커스텀 이벤트에서 트리거되어야 합니다.

다음 예제에서는 초기 무음 푸시의 일부로 이벤트 속성정보를 전송하여 트리거할 특정 인앱 메시지를 구성합니다.

![사용자 지정 이벤트 "인앱 메시지 트리거"를 수행하는 사용자에게 전달되는 액션 기반 전달 인앱 메시지 캠페인으로, "캠페인_이름"이 "IAM 캠페인 이름 예시"와 같습니다.]({% image_buster /assets/img_archive/iosIAMeventTrigger.png %})

{% alert note %}
이 인앱 메시지는 애플리케이션이 포그라운드에 있을 때 무음 푸시를 수신해야만 트리거됩니다.
{% endalert %}

