@snap[midpoint span-80]
# AMPとPWAの
# パワフルさを堪能しよう！
![AMP logo](assets/images/amp_logo.png)
@snapend

+++
このスライドでは、
  実際に __「AMPとPWAをLPに実装するとどうなるか」__ を体感してもらいます。

- AMPと非AMPのスピード比較
- オフライン表示を可能にするPWA

+++

@snap[midpoint span-80]
![doge](assets/images/doge.png)
# AMPをざっくりとおさらい
@snapend

+++

@snap[midpoint span-80]
## 高速化の重要性
@snapend

+++
### 表示速度に関する調査でも・・・

@ul
  - 53%の訪問者は、__ページの表示が3秒遅れるだけで離脱__ する
  - 1秒表示が遅れるごとに __20%ものコンバージョン率が減る__
@ulend

+++

## AMPが早い理由
- 挙動が遅くなるものを読み込ませない
- AMPキャッシュというCDNが使える

+++

@snap[midpoint span-80]
![cool doge](assets/images/cool-doge.gif)
# ここからは実際に体験しましょう
@snapend

+++

## AMPを実装したサイトを紹介
https://amp.ca-test-dhc.com/shop/ad_amp/limited_offer_mb/

+++
☝️Tips
- 静的コンテンツにのみ使えると思われがちなAMPですが
- 動的なコンテンツも扱うことができます。
- サンプルサイトの動的部分は、ランキングエリアです。

+++

## スピードを計測してみよう
  #### 非AMP
  https://top.dhc.co.jp/shop/ad/cam_dhc/diet_sey.html

    #### AMP
  https://amp.ca-test-dhc.com/shop/ad_amp/limited_offer_mb/

+++

### Light houseで測定しよう
@ol
  1. Chrome Devtools -> Auditsタブ
  1. performanceだけにチェックを入れて、**Run audits**
@olend

+++

@snap[midpoint span-80]
# PWAMPでユーザーとの距離を一気に縮める
    pwampとは、AMPとPWAを併用することです
@snapend

+++

## PWAとは？

+++
  > プログレッシブ ウェブアプリ はウェブとアプリの両方の利点を兼ね備えたアプリです。
  > 不安定なネットワークでも迅速に起動し、関連性の高いプッシュ通知を送信することができます。
  > また、ホーム画面にアイコンを表示することができ、トップレベルの全画面表示で読み込むことができます。

+++
### 要するに・・・

  - スマホのホーム画面に追加できる
  - オフラインでも閲覧できる
  - プッシュ通知を行うことができる

+++

@snap[midpoint span-80]
![3d doge](assets/images/doge3d.gif)
# ホームに追加してみましょう
@snapend

+++

#### スマホのブラウザで以下を開く
    https://amp.ca-test-dhc.com/shop/ad_amp/limited_offer_mb/

+++
### Androidのchrome場合
@ol
  1. インストールを促すバナーが表示される
  1. __ホームスクリーンに追加__ する
@olend



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
