# Speed Hackathon LT
+++
## スピードアップしたいサイト
遺伝子ダイエット（記事）  
https://top.dhc.co.jp/shop/ad/sph/idenshi/adv/index_n_basaj.html  
をAMPにするためにやってきました。
+++
### Score
始める前のスコア
+++
Develop server
![speed hack](assets/images/idenshi_dev_LH_before.png)

<!-- DHC Server
![speed hack](assets/images/idenshi_dhc_LH_before.png) -->


<!-- section -->
+++
# AMP
+++
### まずはAMPで書いてみることに。
+++
とりあえずAMPの書き方にした結果
![speed hack](assets/images/idenshi_dev_LH_after.png)
+++
### 嫌な予感・・・
そもそも・・・

+++
### Shift-jis！
クライアントの環境がshift-jisでした。。。
(；´Д｀)

+++
UTF-8
![speed hack](assets/images/idenshi_dev_LH_UTF-8.png)

+++
Image min
![speed hack](assets/images/idenshi_dev_LH_imagemin.png)

+++
canonical
![speed hack](assets/images/before.png)

+++
# NOTO FONT (；´∀｀)

+++
Noto fontをはずす
![speed hack](assets/images/amp_after.png)

+++
# SPEED　HACK
+++
AMPで改善した箇所を継承しつつ、元の仕様に戻す
+++
スピードハックしただけのやつ
![speed hack](assets/images/spd_normal.png)

font外した
![speed hack](assets/images/spd_after2.png)
+++
font外した
![speed hack](assets/images/spd_after2.png)


+++
# 結果
+++
### Speed hackとAMP
Speed hack
![speed hack](assets/images/spd_after2.png)

AMP
![speed hack](assets/images/amp_after.png)
+++
![speed hack](assets/images/amp_after.png)

+++
結果的にSpeed hackの方がスコアは良かった。

+++
### パフォーマンスを見比べる
+++

SPD
![speed hack](assets/images/spd_performance.png)

AMP
![speed hack](assets/images/amp_performance.png)

+++
AMP
![speed hack](assets/images/amp_performance.png)
First meaningful paintに大きな差ができた。


+++
# 最後に
+++
### 大変だったこと
pug, sass
+++
### 良かったこと
Light House, Web Page Test
+++
# 数値化できるって素晴らしい！
さぁ、あとは説得するだけだぜ！
