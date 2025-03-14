---
nav_title: キーと値のペア
article_title: ニュースフィード ウェブ用キー・バリュー・ペア
platform: Web
page_order: 1
page_type: reference
description: "この記事では、Braze SDKを介してニュースフィードカードでキーバリューペアを使用する方法について説明する。"
channel: news feed

---

# キーと値のペア

> この記事では、Braze SDKを介してニュースフィードカードでキーバリューペアを使用する方法について説明する。

{% alert note %}
ニュースフィードは非推奨になります。Braze では、News Feed ツールを使用するお客様は、コンテンツカードメッセージングチャネルに移動することを推奨しています。これは、より柔軟でカスタマイズ可能で、信頼性が高いチャネルです。詳しくは[マイグレーションガイド]({{site.baseurl}}/user_guide/message_building_by_channel/content_cards/migrating_from_news_feed/)をご覧ください。
{% endalert %}

オプションで、`Card` オブジェクトはキーと値のペアを `extras` として保持できます。これらは、カードと一緒にデータを送信し、アプリケーションでさらに処理するために使用します。`card.extras`を呼び出して、これらの値にアクセスします。

[ClassicCard](https://js.appboycdn.com/web-sdk/latest/doc/classes/braze.classiccard.html)、[ImageOnly](https://js.appboycdn.com/web-sdk/latest/doc/classes/braze.imageonly.html)、[CaptionedImage](https://js.appboycdn.com/web-sdk/latest/doc/classes/braze.captionedimage.html) については JSDocs を参照してください。

