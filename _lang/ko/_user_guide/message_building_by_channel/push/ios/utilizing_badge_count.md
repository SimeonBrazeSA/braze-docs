---
nav_title: 배지 수 활용
article_title: 배지 수 활용
page_order: 8

page_type: reference
description: "이 문서에서는 iOS 배지 수를 사용하여 푸시를 받지 못했거나 포그라운드 푸시 알림을 비활성화한 사용자의 참여를 다시 유도하는 방법에 대해 설명합니다."
platform: iOS
channel: 
- push
- in-app messages

---

# 배지 수 활용하기

> iOS 배지 개수는 앱 아이콘의 오른쪽 상단에 빨간색 원 형태로 애플리케이션 내에서 읽지 않은 알림의 수를 표시합니다. 최근 몇 년 동안 배지는 앱 사용자의 재참여를 유도하는 효과적인 수단으로 자리 잡았습니다.

배지 개수는 푸시를 받지 못했거나 포그라운드 푸시 알림을 비활성화한 사용자의 참여를 다시 유도하는 데 사용할 수 있습니다. 마찬가지로 인앱 업데이트와 같이 확인하지 않은 메시지에 대해 사용자에게 알리는 데 사용할 수 있습니다.

## Braze로 배지 수 계산

Braze 대시보드를 통해 푸시 알림을 작성할 때 원하는 배지 개수를 지정할 수 있습니다. 개인화된 메시징을 통해 사용자 속성으로 설정할 수 있으므로 무한한 커스텀 로직이 가능합니다. 사용자를 방해하지 않고 배지 수를 업데이트하는 무음 푸시를 보내려면 푸시에 '콘텐츠 사용 가능' 플래그를 추가하고 메시지 내용을 비워두세요.

{% alert note %}
Android용 배지 개수를 설정하는 방법이 궁금하신가요? Android는 푸시용 앱 배지를 자동으로 처리하므로 Braze에서는 배지에 대한 커스텀 설정이 없습니다.
{% endalert %}

### 배지 수 제거하기

배지 수를 0 또는 ""로 설정하여 앱 아이콘에서 배지 수를 제거합니다. 또한 Braze에서는 앱이 포그라운드에 있는 동안 푸시 알림을 받으면 배지가 자동으로 지워집니다.

## 모범 사례

배지의 재참여 효과를 최적화하려면 사용자 경험을 가장 단순화하는 방식으로 배지 설정을 구성하는 것이 중요합니다.

### 배지 수를 적게 유지하세요
연구에 따르면 배지 수가 두 자릿수를 넘어서면 사용자는 일반적으로 업데이트에 흥미를 잃고 앱 사용을 완전히 중단하는 경우가 많습니다.

> 앱의 특성에 따라 이 규칙에 예외가 있을 수 있습니다(예: 이메일 및 그룹 메시징 앱).

### 배지 개수가 나타낼 수 있는 항목 제한하기
배지를 만들 때는 알림을 최대한 명확하고 직접적으로 전달하고 싶을 것입니다. 배지 알림이 표시할 수 있는 항목의 수를 제한하면 사용자에게 앱의 기능 및 업데이트에 대한 친숙함을 제공할 수 있습니다.

