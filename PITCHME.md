#

+++
## スピードアップしたいサイト
遺伝子ダイエット  
https://top.dhc.co.jp/shop/ad/sph/idenshi/adv/index_n_basaj.html  
をAMPにするためにやってきました。
+++
### Score
始める前のスコア
+++
Develop sever
[image:assets/images/idenshi_dev_LH_before.png]

DHC Server
[image:assets/images/idenshi_dhc_LH_before.png]


<!-- section -->
+++
## AMP
### 調査
AMPの記法で試した
+++
Before
[image:assets/images/idenshi_dev_LH_after.png]

+++
UTF-8
[image:assets/images/idenshi_dev_LH_UTF-8.png]

+++
Image min
[image:assets/images/idenshi_dev_LH_imagemin.png]

+++
canonical
[image:assets/images/before.png]

+++
Preload
noto-fontをはずす
[image:assets/images/amp_after.png]

+++
## SPEED　HACK
前半で話されていたハックを試す
+++
Before
[image:assets/images/spd_normal.png]

After
font外した
[image:assets/images/spd_after2.png]



<!-- section -->
+++
## 結果
### Speed hackとAMP
Speed hack
[image:assets/images/spd_after2.png]

AMP
[image:assets/images/amp_after.png]

<!-- section -->
+++
何が違うのか、パフォーマンスを見比べる
SPD
[image:assets/images/spd_performance.png]

AMP
[image:assets/images/amp_performance.png]

First meaningful paintに大きな差ができた。
