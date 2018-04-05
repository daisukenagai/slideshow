# Speed Hackathon LT
+++
## スピードアップしたいサイト
遺伝子ダイエット（記事LP）  
https://top.dhc.co.jp/shop/ad/sph/idenshi/adv/index_n_basaj.html  
をAMPにするためにやってきました。
+++
### 始める前のスコア
+++
Develop sever
![speed hack](assets/images/idenshi_dev_LH_before.png)


+++
## AMP
### 調査
AMPの記法で試した
+++
Before
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
noto-fontをはずす
![speed hack](assets/images/amp_after.png)

+++
## SPEED　HACK
前半で話されていたハックを試す
+++
Before
![speed hack](assets/images/spd_normal.png)

After
font外した
![speed hack](assets/images/spd_after2.png)



<!-- section -->
+++
## 結果
+++
### Speed hackとAMP
Speed hack
![speed hack](assets/images/spd_after2.png)

AMP
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

First meaningful paintに大きな差ができた。
