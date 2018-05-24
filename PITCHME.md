<div class="bg_amp">

## GoogleのSpeed Hackathonに参加してきました

</div>

+++

そのコンセプトはシンプル！

+++

## LPを高速表示する

+++

![google](assets/images/google.png)

<div class="left">

> とにかくパフォーマンスのいいサイトにしましょう。
>
> もう __なんでもいい__ です。
>
> なんでもいいから
> __表示が速くて画面遷移がスムーズなもの__にして、
> ユーザーに好かれましょう。

</div>

+++

## 改善のイメージ
<div class="mario">
![before](assets/images/mario.gif)
<span class="pb5">👉</span>
![after](assets/images/sonic.gif)
</div>

+++

### なぜそんなに
### 高速化にこだわるの？

+++

様々な調査で
<br>
@ul
1. 53%の訪問者は、ページの表示が __3秒遅れるだけで離脱__ する
2. 1秒表示が遅れるごとに __20%ものコンバージョン率が減る__
@ulend
<br>
という結果に。

+++

<div class="left">
仮に・・・
<br>
__3秒__ で表示されていたページが、
<br>
__1秒__ に改善されると・・・
</div>

+++

@ul
1. __離脱率の53%__ を抑え
1. __コンバージョン率が40%__ 改善
@ulend

+++

## モバイルWeb
@ul
- 多様なデバイス
  - 👉 __スマホ、タブレット__
- あらゆる環境
  - 👉 屋外などの __ナローな回線__
@ulend
+++

ページスピードは非常に __重要__

+++

さて、ここで理解してほしいのは・・・
<br>
スピード改善できれば __AMPじゃなくてもOK__

+++

![google](assets/images/google.png)
## そう、なんでもいいから早くしろ！

+++
## AMPじゃなくてもいいんです！
+++

## いやでも、AMPはすごかった・・・

+++

## AMPってなに？
⚡爆速なWebサイトを作る為のフレームワーク⚡

+++

### なんで早くなるの？

+++

@ul
- Javascriptは使わせない！
- AMPが用意するWeb Componentsを利用する
- __Google AMP Cache__ を利用できる
@ulend

+++

<div class="left">
ページロードを阻害する要素を__使わせない__
<br>
重い挙動の原因となるものを排除
</div>

+++

<div class="left">
Validatorをパスするページは
<br>
__Google AMP Cache__ （googleが用意するCDN）を利用できる
</div>

+++

<div class="left">
AMP HTMLが正しく記述されていれば、
<br>
googleのCDNキャッシュが__自動的に使える__
</div>

+++

### こんな良さもあります
@ul
- Google Search経由の __アクセスは最速__
- 検索結果カルーセル部分に記事コンテンツが表示
- 実は、__Responsive__ なサイトもOK
- 実は実は、__Dynamic__ なサイト（ECとか）もOK
- __PWA__ と併用で更にUXを向上
@ulend

+++

### PWAについて
<div class="left">
__今までWebでは実現できなかったアプリっぽいこと__ ができるようになります
</div>
@ul
- Webアプリを __ホーム画面に追加__ できる
- __オフラインでも動作__ する
- __プッシュ通知__ ができる
@ulend

+++
## みんなで計測してみよう
+++
- [これまでのLP](http://develop.ca-test-dhc.com/shop/ad/sph/idenshi/adv/index_n_basaj.html) ↗️
- [AMP](http://develop.ca-test-dhc.com/shop/ad/sph/idenshi/adv/index_amp.html) ↗️
- [SPD](http://develop.ca-test-dhc.com/shop/ad/sph/idenshi/adv/index_spd.html) ↗️

+++
パフォーマンス計測ツール
- Lighthouse
- [WebPagetest](https://www.webpagetest.org/) ↗️


+++

## やったこと
AMP HTMLに書き直す

+++

## 注意点
＿|￣|○
<br>
<br>
<div class="left">
残念なことに開発環境ではAMPキャッシュが使えません。
</div>


+++

<div class="left">
ただ、それでもこのパフォーマンス！
<br>
( ｰ`дｰ´)ｷﾘｯ
<br>
<br>
つまり、 __仕様に準拠するだけ__ でスピード __改善__ しているということです。
</div>

+++

<div class="left">
また、根本的な問題ですが、
<br>
DHCの場合はサーバーの文字コードがshift-jisなので、仕様から外れます
<br>
</div>
(；´∀｀)

+++

### Speed hack
AMPではない方法で、可能な限りチューニングを施します。

+++

- 文字コードのUTF-8化
- 画像のファイルサイズを軽量化
- canonicalの設定

+++

## AMP実装ってかんたん？

<div class="left">
実は、みなさんが思っているよりも、簡単です。
<br>
実装そのものよりも、
<br>
__「既存の環境で 無事に動作させられるかどうか」__
</div>

+++

## AMP対応の課題
@ul
- html tagを、amp tagに書き換える必要がある
- 既存のjsが使えなくなる
- 導入後はAMPに準拠し続けなくてはならない
@ulend
+++

<div class="left">
既存システムからの移行は、
<br>
大きなトラブルに繋がりかねません。
<br>
<br>
</div>
### 開発にはクライアントの深い理解が不可欠です！

+++

### AMPによる副作用
@ul
- 自身􏰀のコンテンツが 3rd partyとして扱われる悪影響
- AMPページ􏰁は場合によって別ドメインでコンテンツが配信される
- 従ってオリジンやドメインを意識する機能が動作しない可能性がある
- 3rd Party Cookieブロッキングブラウザで􏰁Cookie􏰀書込が出来ない
- 表示されているページで􏰁Service Worker􏰁動作しない
- Web App Manifestによるホーム画面へ追加が動作しない
@ulend

+++

## 結論

+++

## AMPすごい
## でも、AMPじゃなくても早くなる

+++
## まずはAMPじゃなくても、できることはある

+++

## 最後に

+++

## すべてはユーザー体験の向上のために

+++

- モバイル・デバイスでの高速表示は今後、最低ラインの基準となる
- よりコンテンツの質が問われるようになっていく

+++

# よりよい体験をユーザーに提供しましょう

+++

# お疲れ様でした！
