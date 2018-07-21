# Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet?

`CVPR2018`

```
Kensho Hara, Hirokatsu Kataoka, Yutaka Satoh
National Institute of Advanced Industrial Science and Technology (AIST)
Tsukuba, Ibaraki, Japan

{kensho.hara, hirokatsu.kataoka, yu.satou}@aist.go.jp
```

`arxiv link`
https://arxiv.org/pdf/1711.09577v2.pdf

## 概要
現在存在するビデオデータセットが、3DCNNモデルを訓練するのに十分であるかを検証した。

- ResNet-18をUCF-101などのデータ・セットで学習、結果過学習が起こった（十分ではなかった）
- Kineticsデータセットは、最大ResNet-152層まで学習の有意性が見られた
- 複雑な2DアーキテクチャーよりもKinetics Pretrainedシンプル3Dアーキテクチャーが優れていることが分かった。


## 新規性・結果・なぜ通ったか
UCF-101等を用いて、3DCNNを学習しても、高い精度がでないという先行研究(Kineticsを除く)

Kineticsで、どのくらいまで深い層を学習できるかを検証した。

3Dモデルにおける転移学習の検証

## 先行研究と比べてどこがすごい？
## 技術や手法のキモはどこ？
## 議論はある？
## 次に読むべき論文は？

`residual learningについて学ぶ`
K. He, X. Zhang, S. Ren, and J. Sun. Deep residual learning
for image recognition. In Proceedings of the IEEE Conference
on Computer Vision and Pattern Recognition (CVPR)

`3DCNN`
[2]


## コメント

>ImageNetで訓練された2D CNNを使用することにより、画像のさまざまなタスクが大幅に進歩しました。ディープ3D CNNとKineticsを使用することで、2D CNNやImageNetの歴史を振り返り、ビデオのコンピュータビジョンの進歩を刺激すると確信しています。

実際に、様々なタスクで3DCNNを活用しても良いかもしれない。
Kaggle等で試してみる。

計算リソースとデータセットの整備が進み、膨大なパラメータを要する3DCNNモデルも、実用レベルに近づいてきている。videoを学習させ、予測するというのはさらに現実化してきている。その先のビジネスで何が起こりうるかを予測しておく必要がある。

また、今後2Dアーキテクチャに変わり、転移学習を用いた3Dアーキテクチャが主流になるかもしれない。

## 事前知識

### residual learning
![Residual Learning from Qiita.](https://camo.qiitausercontent.com/dc2110c9be7fc86ecd088d4d9e68a9578199b665/68747470733a2f2f71696974612d696d6167652d73746f72652e73332e616d617a6f6e6177732e636f6d2f302f33383535352f38626637623865362d646630362d613764382d333639642d3235383464333163646238632e706e67)
https://qiita.com/ikeyasu/items/ea9ced2b8e0fcb3da2be

### 3DCNN
パラメータ数が多いので、学習が困難
さらに、3Dモデルは転移学習を行うことができる。

※その問題を解決しようとする論文がある。
https://arxiv.org/abs/1711.08200
--------------
