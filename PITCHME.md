@snap[midpoint span-80]
# AMPとPWAの
# パワフルさを堪能しよう！
![AMP logo](assets/images/amp_logo.png)
@snapend

+++
このスライドでは、実際にAMPとPWAをLPに実装するとどうなるかを紹介します。
主に、
- AMPと非AMPのスピード比較
- PWAの実装について

+++

# AMPをざっくりとおさらい
+++

@snap[midpoint span-80]
## 高速化の重要性
![doge](assets/images/doge.png)
@snapend

+++
### 表示速度に関して広く知られる調査結果
@ul
- 53%の訪問者は、__ページの表示が3秒遅れるだけで離脱__ する
- 1秒表示が遅れるごとに __20%ものコンバージョン率が減る__
- ![trump](assets/images/trump-eclipse.png)
@ulend

+++

## AMPが早い理由
- 挙動が遅くなるものを読み込ませない
- AMPキャッシュというCDNが使える

+++

@snap[midpoint span-80]
# ここからは実際に体験しましょう
@snapend

+++

## AMPを実装したサイトを紹介
https://amp.ca-test-dhc.com/shop/ad_amp/limited_offer_mb/

+++
☝️Tips
静的サイトにのみ使えると思われがちなAMPですが
動的なコンテンツも扱うことができます。

サンプルサイトの動的部分は、ランキングエリアです。

+++

## スピードを計測してみよう

+++
### Light houseを使用して、速度を測定しよう

- 非AMP： https://top.dhc.co.jp/shop/ad/cam_dhc/diet_sey.html
- AMP： https://amp.ca-test-dhc.com/shop/ad_amp/limited_offer_mb/

+++

### Light houseを使う
1. Chrome Devtools -> Auditsタブ
1. performanceだけにチェックを入れて、**Run audits**

+++
@snap[midpoint span-80]
# PWAMPでUXを最大化する
pwampとは、AMPとPWAを併用することです。
@snapend

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

@snap[midpoint span-80]
# ホームに追加してみましょう
@snapend

+++
スマホのブラウザでモバイル版のページを開く
https://amp.ca-test-dhc.com/shop/ad_amp/limited_offer_mb/

+++
### Androidのchrome場合
ページにアクセスするとインストールを促すバナーが表示されるので、__ホームスクリーンに追加__ する

### iOSのsafari場合
下部にある __「ホーム画面に追加」アイコン__ をタップする

+++
## AMP導入の注意点
それは、AMPでなければ、実現できないことか？

この詰めが甘いと・・・
@ul
- 技術的な障壁による導入コストの増大
- スピード改善できたのに思うような結果にならない
@ulend

+++
### 最終チェックポイント
- ターゲットはモバイルデバイスか？
- AMPでなくてもスピード改善で十分早くなる


+++

@snap[midpoint span-80]
@img[AMP logo](assets/images/logo_yoshiko.png)
# AMPで、より良いUXを提供しましょう！
@snapend
