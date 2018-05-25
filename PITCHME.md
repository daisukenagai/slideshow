---?image=assets/images/amp.png&size=620px 620px

# SPEED HACKATHON
@Google

+++

そのコンセプトはシンプル！

+++

> とにかくパフォーマンスのいいサイトにしましょう。
>
> なんでもいいから
>
> __表示が速くて画面遷移がスムーズなもの__にして、
>
> ユーザーに好かれましょう。

+++

## 改善のイメージ
<div class="mario">
![before](assets/images/mario.gif)

<span class="pb5">👉👉👉</span>

![after](assets/images/sonic.gif)
</div>

+++

なぜそんなに __高速化__ にこだわるの？
![doge](assets/images/doge.png)

+++

様々な調査で・・・
@ul
- __53%__ の訪問者は、ページの表示が __3秒__ 遅れるだけで __離脱__ する
- __1秒__ 表示が遅れるごとに __20%__ もの __コンバージョン率が減る__
@ulend
![trump](assets/images/trump-eclipse.png)

+++

仮に・・・

## __3秒__ で表示されていたページが、
## __1秒__ に改善されると・・・

+++

@ol
- __離脱率の53%__ を抑え
- __コンバージョン率が40%__ 改善
@olend

![coin](assets/images/coin.gif)

+++

## ページスピードは非常に __重要__

+++

## あらゆる環境
@ul
- 👉 屋外などの __ナローな回線__
- 👉 信号待ちなどの __見るタイミング__
@ulend

## 多様なデバイス
@ul
- 👉 サイズ __スマホ/タブレット/laptop__
- 👉 スペック __高 / 低__
@ulend

+++

となると・・・
## スピード改善するなら
# __AMPじゃなくてもOK__
+++

![trump](assets/images/donald_trump.png)
# そう、なんでもいいから早くしろ！

+++

## AMPじゃなくてもいいんです！

+++

## が・・・

+++

## やっぱり、⚡AMPはすごかった
![doge](assets/images/doge.png)

+++

## ⚡AMPってなに？
__爆速なWebサイト__ を作る為のフレームワーク

+++

### なんで早くなるの？

+++

ページロードを __阻害する要素を排除__ するから
@ul
- Javascriptは使わせない！
- AMPが用意するWeb Componentsを利用する
- __Google AMP Cache__ を利用できる
@ulend

+++

Validatorをパスするページは
### __Google AMP Cache__ を利用できる
（googleが用意する __CDN__）

+++

AMP HTMLが正しく記述されていれば、
## googleのCDNキャッシュが__自動的に使える__

+++

### 発見したこと👀
@ul
- Google Search経由の __アクセスは最速__
- 検索結果カルーセル部分に記事コンテンツが表示
- 実は、__Responsive__ なサイトもOK
- 実は実は、__Dynamic__ なサイト（ECとか）もOK
- __PWA__ と併用で更にUXを向上
@ulend

+++

### 補足：PWAについて
@ul
- Webアプリを __ホーム画面に追加__ できる
- __オフラインでも動作__ する
- __プッシュ通知__ ができる
@ulend

+++

<div class="left">

今まで __Webでは実現できなかったアプリっぽいこと__ ができるようになります

</div>

+++

## さて、そろそろ計測してみようか
![doge](assets/images/doge.png)

+++
- [これまでのLP](http://develop.ca-test-dhc.com/shop/ad/sph/idenshi/adv/index_n_basaj.html) ↗️
- [AMP](http://develop.ca-test-dhc.com/shop/ad/sph/idenshi/adv/index_amp.html) ↗️
- [SPD](http://develop.ca-test-dhc.com/shop/ad/sph/idenshi/adv/index_spd.html) ↗️

+++
パフォーマンス計測ツール
- Lighthouse
- [WebPagetest](https://www.webpagetest.org/) ↗️

+++

## ＿|￣|○
<div class="left">
残念なことに開発環境では、
<br>
AMPキャッシュが生きてません。。。
</div>

+++
## が、しかし！
+++

<div class="left">

### それでもこのパフォーマンス！
@ul
- つまり・・・
- __仕様に準拠するだけ__ で
- スピード __改善__ している！
@ulend
![doge](assets/images/doge.png)

+++

## AMP実装ってかんたん？
@ul
- 実装そのものよりも、
- __既存の環境で 無事に動作__ させられるかどうか
@ulend

+++

## AMP対応の具体的にやること
@ul
- HTMLからAMP HTMLへ
- CSSの`!important`が使えない
- JSが使えない
- ⚡AMPし続けなくてはならない
@ulend

+++

### 起こりそうな問題
@ul
- 別ドメインでコンテンツが配信（場合によって）
- 3rdPartyCookieブロッキングブラウザで􏰁Cookie書込が出来ない
- WebAppManifestによるホーム画面へ追加が動作しない
@ulend

+++

# 残念なニュース

+++

Dのサーバーの文字コード=　__shift-jis__

![doge](assets/images/doge.png)実装してもAMPとして認められません


+++

# ⚠️
@ul
- 既存システムからの移行は、
- 大きなトラブルに繋がりかねません。
@ulend

+++

### 開発にはクライアントの深い理解が不可欠です！

+++

### AMPじゃないSpeed hackの方法
@ul
- `js` と `SSI`の除外
- 画像の圧縮
- `canonical` とか詳細設定の見直し
- css及びweb fontの `preload`
@ulend

+++

# __結論__

+++

## ⚡AMPすごい
## でも、__AMPじゃなくても__ 早くなるよ

+++

# いまできることは、ある！

+++

# 最後に

+++

## 高速表示は、最低ラインの基準
@ul
- まずはユーザーに __見てもらう__ ために
- 次は __コンテンツの質__ が問われる時代に
@ulend

+++

## ユーザーに __よりよい体験を__！

+++

# お疲れ様でした！
![doge](assets/images/doge3d.gif)
