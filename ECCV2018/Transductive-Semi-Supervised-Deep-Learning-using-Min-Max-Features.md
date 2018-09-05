# 論文名
Transductive Semi-Supervised Deep Learning using Min-Max Features
### 著者
### 学会名/ジャーナル名
### 論文へのリンク
http://openaccess.thecvf.com/content_ECCV_2018/html/Weiwei_Shi_Transductive_Semi-Supervised_Deep_ECCV_2018_paper.html

## 概要
DCNNモデルの学習に有効なTSSDL（Transductive Semi-Supervised Deep Learning）法を提案する。この手法では、学習に従来のトランスダクティブ学習を適用する。さらに、外れ値などのサンプルからの影響を防ぐため、ラベルなしサンプルに対して信頼度を導入する。特徴記述子間の距離を最小にするためにMin-Max Feature (MMF) regularizationも提案する。最先端のSSLメソッドと同等画像分類精度を達成している。

- 従来のSSL・TSSDLはラベルなしサンプルをすべて同等に扱うので、外れ値に影響される可能性がある→誤った方向に学習する可能性がある
- 訓練サンプル間の類似距離を測定が学習初期時には困難（高品質な特徴記述子が必要なため）
- ラベルなしサンプルにおいても、損失関数を定義し、最適化を試みる（TSSLを拡張する）→これは初の試みらしいので、面白いかも

## 事前知識
### Feature Description(特徴量記述)
http://labs.eecs.tottori-u.ac.jp/sd/Member/oyamada/OpenCV/html/py_tutorials/py_feature2d/py_features_meaning/py_features_meaning.html#features-meaning

>一度画像中の特徴を見つければ，他の画像中に写る同じ特徴も見つけられないといけません．何をすればいいのでしょうか?特徴の周囲の領域をとり，我々の言葉で”上の方は青い空，下の方は建物があり，建物にはガラスがあって…”といったように説明し，他の画像中に同じような領域があるか探すのです．この記述は Feature Description(特徴量記述) と呼ばれます．

https://www.slideshare.net/lawmn/siftsurf
## 新規性・結果・なぜ通ったか
## 先行研究と比べてどこがすごい？
## 技術や手法のキモはどこ？
## 議論はある？
## 次に読むべき論文は？

## 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
## デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
