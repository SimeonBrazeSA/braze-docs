---
nav_title: "フルスクリーン"
article_title: フルスクリーンのアプリ内メッセージ
description: "この参考記事では、フルスクリーンのアプリ内メッセージのメッセージとデザイン要件について取り上げている。"
page_type: reference
page_order: 0
channel:
  - in-app messages
tool:
  - Media

---

# フルスクリーンのアプリ内メッセージ

> フルスクリーンのメッセージは端末の画面全体を占める！このメッセージタイプは、必須アプリのアップデートのように、ユーザーの注意が本当に必要な場合に最適だ。

{% tabs %}
{% tab ポートレート %}

![フルスクリーンのアプリ内メッセージを縦向きで2つ並べて表示し、おすすめの画像とテキストを詳しく説明する。詳細は以下のセクションを参照のこと。]({% image_buster /assets/img/full-screen-spec.png %}){: style="max-width:801px;border:none;display:block;margin-left:auto;margin-right:auto"}

{% endtab %}
{% tab 景観 %}

![横向きで2つのフルスクリーンのアプリ内メッセージを横に並べ、おすすめの画像とテキストを詳しく説明する。詳細は以下のセクションを参照のこと。]({% image_buster /assets/img/full-screen-spec-landscape.png %}){: style="max-width:801px;border:none;display:block;margin-left:auto;margin-right:auto"}

{% endtab %}
{% endtabs %}

## 画像

フルスクリーンのアプリ内メッセージは、デバイスの高さいっぱいに表示され、必要に応じて水平方向（左右）にクロップされる。画像とテキストのフルスクリーンメッセージは、デバイスの高さの50％を埋める。ノッチ付き」デバイスでは、アプリ内のフルスクリーンメッセージがすべてステータスバーを埋める。

- すべての画像は5MB以下でなければならない。
- ファイル形式はPNG、JPEG、[GIFのみ]({{site.baseurl}}/developer_guide/platform_integration_guides/android/in-app_messaging/customization/gifs#gifs)受け付ける。
- 画像は500KBを推奨する。

{% alert tip %} 自信を持ってアセットを創造しましょう！当社のアプリ内メッセージ画像テンプレートとセーフゾーンオーバーレイは、あらゆるサイズのデバイスでうまく動作するように設計されている。\[デザインテンプレートのダウンロード ZIP]({% image_buster /assets/download_file/Braze-In-App-Message-Design-Templates.zip %}) {% endalert %}

### ポートレート

| レイアウト | 資産規模 | 注釈 |
|--- | --- | --- |
| 画像とテキスト | アスペクト比6:5<br> 高解像度 1200 x 1000 px<br> 最小600 x 500 px | トリミングは四方で可能だが、画像は常にビューポートの上部50％を埋める。 |
| 画像のみ | 3:5のアスペクト比<br> 高解像度 1200 x 2000 px<br> 最小600 x 1000 px | 背の高いデバイスでは、左右の端でクロッピングが発生することがある。 |
{: .reset-td-br-1 .reset-td-br-2 .reset-td-br-3}

### 景観

| レイアウト | 資産規模 | 注釈 |
|--- | --- | --- |
| 画像とテキスト | アスペクト比10:3<br> 高解像度 2000 x 600px<br> 最小1000 x 300 px | トリミングは四方で可能だが、画像は常にビューポートの上部50％を埋める。 |
| 画像のみ | アスペクト比5:3<br> 高解像度 2000 x 1200px<br> 最小1000 x 600 px | 背の高いデバイスでは、左右の端でクロッピングが発生することがある。 |
{: .reset-td-br-1 .reset-td-br-2 .reset-td-br-3}

### 画像の安全地帯

Brazeプラットフォームでフルスクリーンのアプリ内メッセージをプレビューする際、デバイス間で表示される際にトリミングから保護されるメッセージの領域に対して、イメージセーフゾーンを有効にすることができる。プレビューペインでイメージセーフゾーンをテストするだけでなく、いつも通り[メッセージをテスト]({{site.baseurl}}/user_guide/message_building_by_channel/in-app_messages/testing/)することをお勧めする。

![画像セーフゾーンを表示」を有効にしたBrazeで、アプリ内メッセージをプレビューする。画像のセーフゾーンは、画像のどの部分が切り抜きから保護されるかを視覚化する画像上のオーバーレイである。]\[3c]

## 大型スクリーン

タブレットやデスクトップ・ブラウザでは、以下のスクリーンショットのように、フルスクリーンのアプリ内メッセージがアプリ画面の中央に表示される。

{% tabs %}
{% tab ポートレート %}

![縦向きの大画面で表示されるフルスクリーンのアプリ内メッセージ。]({% image_buster /assets/img/full-screen-large-viewport.png %}){: style="border:none;display:block;margin-left:auto;margin-right:auto"}

{% endtab %}
{% tab 景観 %}

![横向きの大画面で表示されるフルスクリーンのアプリ内メッセージ。]({% image_buster /assets/img/full-screen-large-viewport-landscape.png %}){: style="max-width:80%;border:none;display:block;margin-left:auto;margin-right:auto"}

{% endtab %}
{% endtabs %}

\[3b] ： {% image_buster /assets/img/full-screen-large-viewport.png %}
\[3c] ： {% image_buster /assets/img/image-safe-zone-full-screen-in-app-message.png %}
