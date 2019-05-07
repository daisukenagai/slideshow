@img[AMP logo](assets/images/amp.png)


# AMPをおさらい

+++
## AMPが早い理由


技術的な意味でのAMPとは？
HTMLフレームワークです。
HTMLをAMP⚡HTMLという形式に則って拡張することで、先述のAMPコンポーネンツやAMPキャッシュの恩恵を享受することができる。


# AMPを実装した
https://amp.ca-test-dhc.com/shop/ad_amp/limited_offer_mb/

+++
☝️Tips
静的サイトにのみ使えると思われがちなAMPですが
動的なコンテンツも扱うことができます。
DHCの社名検索サイトにおける、動的部分は、ランキングエリアです。

+++
どれくらいSpeed hackが成功しているか？
Light houseを使用して、速度を測定しよう

+++
### 測定するサイト
- 非AMP： https://top.dhc.co.jp/shop/ad/cam_dhc/diet_sey.html
- AMP： https://amp.ca-test-dhc.com/shop/ad_amp/limited_offer_mb/

+++

### Light houseを使う
1. Chrome Devtools -> Auditsタブ
1. performanceだけにチェックを入れて、**Run audits**

+++
# PWAMPでUXを最大化する
pwampとは、AMPとPWAの技術を併用することです。

+++
## PWAとは？

+++
> プログレッシブ ウェブアプリ はウェブとアプリの両方の利点を兼ね備えたアプリです。
> 不安定なネットワークでも迅速に起動し、関連性の高いプッシュ通知を送信することができます。
> また、ホーム画面にアイコンを表示することができ、トップレベルの全画面表示で読み込むことができます。

+++
要するに・・・
普通のサイトなのに、

- スマホのホーム画面に追加できる
- オフラインでも閲覧できる
- プッシュ通知を行うことができる

そんな技術です

+++
## PWAMPを実装してみた
スマホのブラウザでモバイル版のページを開く
https://amp.ca-test-dhc.com/shop/ad_amp/limited_offer_mb/

Androidのchrome場合
ページにアクセスするとインストールを促すバナーが表示されるので、ホームスクリーンに追加する

iOSのsafari場合
下部にある「ホーム画面に追加」アイコンをタップする


+++
## AMP導入の注意点
それは、AMPでなければ、実現できないことか？
この前提が崩れると、技術的な障壁による導入コストの増大、スピード改善できたけれど思うような結果に繋がらない。

+++
最終チェックポイント
- ターゲットはモバイルデバイスか？
- AMPでなくてもスピード改善で十分早くなる


+++

AMPで、より良いUXを提供しましょう！
@snap[midpoint span-50]
@img[AMP logo](assets/images/amp.png)
@snapend
