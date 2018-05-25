---?image=assets/images/amp.png&size=620px 620px

# Speed Hackathon
### @Google
![doge](assets/images/doge.png)

+++

そのコンセプトはシンプル！

+++

## LPを高速表示する

+++

> とにかくパフォーマンスのいいサイトにしましょう。
>

> もう __なんでもいい__ です。
>

> なんでもいいから
> __表示が速くて画面遷移がスムーズなもの__にして、
> ユーザーに好かれましょう。

+++

## 改善のイメージ
<div class="mario">
![before](assets/images/mario.gif)

<span class="pb5">👉👉👉</span>

![after](assets/images/sonic.gif)
</div>

+++

### なぜそんなに
### __高速化__ にこだわるの？

+++

様々な調査で・・・
@ul
- __53%__ の訪問者は、ページの表示が __3秒__ 遅れるだけで __離脱__ する
- __1秒__ 表示が遅れるごとに __20%__ もの __コンバージョン率が減る__
@ulend
![trump](assets/images/trump-eclipse.png)

+++

<div class="left">

仮に・・・
<br>
### __3秒__ で表示されていたページが、
<br>
### __1秒__ に改善されると・・・

</div>

+++

![coin](assets/images/coin.gif)
@ol
- __離脱率の53%__ を抑え
- __コンバージョン率が40%__ 改善
@olend

+++

## ページスピードは非常に __重要__

+++

## モバイルWebを取り囲む環境
@ul
- 多様なデバイス
  - 👉 __スマホ、タブレット__

<br>

- あらゆる環境
  - 👉 屋外などの __ナローな回線__
@ulend

+++

さて、ここで理解してほしいのは・・・
@ul
- スピード改善できるなら __AMPじゃなくてもOK__
@ulend

+++

![trump](assets/images/donald_trump.png)
# そう、なんでもいいから早くしろ！

+++

## AMPじゃなくてもいいんです！

+++

## が・・・

+++

## やっぱり、AMPはすごかった⚡

+++

## AMPってなに？
爆速⚡なWebサイトを作る為のフレームワーク

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

<div class="left">
Validatorをパスするページは
<br>
### __Google AMP Cache__ を利用できる
（googleが用意するCDN）
</div>

+++

<div class="left">
AMP HTMLが正しく記述されていれば、
<br>
## googleのCDNキャッシュが__自動的に使える__
</div>

+++

### 発見したこと
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
<br>
<div class="left">
残念なことに開発環境では、AMPキャッシュが生きてません。。。
</div>

+++
## が、しかし！
+++

<div class="left">
それでもこのパフォーマンス！
<br>
<br>
つまり、 __仕様に準拠するだけ__ でスピード __改善__ している！
</div>

+++

## AMP実装ってかんたん？
@ul
- 実装そのものよりも、
- __既存の環境で 無事に動作__ させられるかどうか
@ulend

+++

## AMP対応の課題
@ul
- HTMLからAMP HTMLへ
- CSSの`!important`が使えない
- JSが使えない
- ⚡AMPし続けなくてはならない
@ulend

+++

<div class="left">
### ⚠️
@ul
- 既存システムからの移行は、
- 大きなトラブルに繋がりかねません。
@ulend

+++

### 開発にはクライアントの深い理解が不可欠です！

+++

### AMP化で気をつけること
@ul
- 別ドメインでコンテンツが配信（場合によって）
- 3rdPartyCookieブロッキングブラウザで􏰁Cookie書込が出来ない
- WebAppManifestによるホーム画面へ追加が動作しない
@ulend

+++

<div class="left">
また、根本的な問題ですが、
<br>
Dのサーバーの文字コードが　__shift-jisなので仕様外__。。。
<br>
</div>

(；´∀｀)実装できません

+++

### AMP以外の方法で、Speed hack
@ul
- jsとincludeの除外
- 画像の圧縮
- canonicalとか詳細設定の見直し
- css及びweb fontの`preload`
@ulend

+++

# 結論

+++

## ⚡AMPすごい
## でも、AMPじゃなくても早くなるよ

+++

# いまできることは、ある！

+++

# 最後に

+++

## 高速表示は、最低ラインの基準
@ul
- せっかく作ったLPを、ちゃんとユーザーに見てもらいましょう
- コンテンツの質を高めて、ユーザーに満足してもらいましょう
@ulend

+++

## よりよい体験をユーザーに提供しましょう

+++

# お疲れ様でした！
![doge](assets/images/doge.png)
