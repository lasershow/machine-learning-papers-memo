# 論文名
DF-Net: Unsupervised Joint Learning of Depth and Flow using Cross-Task Consistency
### 著者
### 学会名/ジャーナル名
### 論文へのリンク


## 概要

ラベルなしビデオシーケンスを使用したsingle depth predection(単焦点深度予測)とオプティカルフロー推定についての教師なし学習フレームワークを提案している。このフレームワークのキモは、rigid regionsに対して、induced 3D scene flowを逆投影することによって、予測されたシーン深度とカメラモーションを使用して2Dオプティカルフローを合成することができるということである。

- 単視点深度予測とオプティカルフロー推定は、コンピュータビジョンにおける2つの基本的な問題である。
- 現実世界でこのように高密度にラベル付けされたデータセットを収集するには、相当量の人間の努力が必要であり、エラーが発生しがちです。
- 合成データセットは、実際のシーンからのモーションブラー、オクルージョン、および自然な画像統計の複雑さをキャプチャしません

### オプティカルフローとは
物体やカメラの移動によって生じる隣接フレーム間の物体の動きの見え方のパターンです． 各ベクトルが1フレーム目から2フレーム目への変位ベクトルを表す2次元ベクトル場で表現されます． 以下の画像(画像引用: Wikipedia article on Optical Flow) を見てください．
http://labs.eecs.tottori-u.ac.jp/sd/Member/oyamada/OpenCV/html/py_tutorials/py_video/py_lucas_kanade/py_lucas_kanade.html
### single depth predection
### optical flow estimation

### 参考
RGBからRGB-Dへ-深度推定するディープラーニング-
https://qiita.com/hiroqik/items/2c6c7ece73a74b7b6644

- わたしたちは単一の単眼カメラで撮影した一枚の画像から深度を推定する課題を検討する(2005年)
-

## 新規性・結果・なぜ通ったか
## 先行研究と比べてどこがすごい？
## 技術や手法のキモはどこ？
## 議論はある？
## 次に読むべき論文は？

## 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
## デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
