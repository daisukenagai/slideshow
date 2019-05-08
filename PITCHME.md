---?image=assets/images/amp.png&size=620px 620px

# SPEED HACKATHON
@Google

+++

[詳細な資料やハッカソンのログ🐙](https://github.com/CyberAgent/advertising-crs-playground/issues/13)

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

## なぜそんなに __高速化__ にこだわるの？
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

## スピード改善が難しいところ

+++

## ユーザーひとりひとりの環境が違うから

+++

## シチュエーション
@ul
- 👉 屋外などの __ナローな回線__
- 👉 信号待ちなどの __見るタイミング__
@ulend

+++

## 多様なデバイス
@ul
- 👉 サイズ __スマホ/タブレット/laptop__
- 👉 スペック __高 / 低__
@ulend

+++

# ページスピードは非常に __重要__

+++

![trump](assets/images/donald_trump.png)
# そう、なんでもいいから早くしろ！

+++

## スピード改善がテーマ
## だから __AMPじゃなくて__ もいいんです！

+++

# 実装してみた

+++

## 改善のイメージ
<div class="mario">
![before](assets/images/mario.gif)

<span class="pb5">👉👉👉</span>

![after](assets/images/sonic.gif)
</div>

+++
## スピードアップしたいサイト
遺伝子の記事LP

（もう今はリダイレクト中なので、実装後のページ👇）
- [speed hacked](http://develop.ca-test-dhc.com/shop/ad/sph/idenshi/adv/index_spd.html)
- [amplifyed](http://develop.ca-test-dhc.com/shop/ad/sph/idenshi/adv/index_amp.html)

+++
### Score
始める前のスコア
+++
Develop server
![speed hack](assets/images/idenshi_dev_LH_before.png)

+++

### 軽量化メニュー
- image minify
- canonical
- web font

+++
### 計測ツール
- Light House(chrome 👉 audits)
- [Web Page Test](https://www.webpagetest.org/)
+++
### Image min
![speed hack](assets/images/idenshi_dev_LH_imagemin.png)

+++
### canonical
![speed hack](assets/images/before.png)

+++
### Noto fontをはずす
![speed hack](assets/images/amp_after.png)


+++
# 結果
+++
![speed hack](assets/images/spd_after2.png)
