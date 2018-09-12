# 論文名
Key-Word-Aware Network for Referring Expression Image Segmentation
### 著者
### 学会名/ジャーナル名
### 論文へのリンク

-------

## 概要
Referring expression image segmentationのためのキーワード認識ネットワークとキーワード認識型ビジュアルコンテキストモデルを含むネットワークを提案する。各画像領域ごとにキーワードを抽出し、自然言語クエリに基づいて複数の画像領域の中からキーワード認識型視覚コンテキストをモデル化するkey-word-aware network (KWAN)を提案する。

- 内部でCNNとRNNを用いて、画像領域とキーワードの特徴をエンコードする。
- それらに基づいて、アテンションモデルが各画像領域のキーワードを見つける
- 抽出したvisual features, key-word-aware visual context features、key word featuresを元に各画像領域を分類する。

ReferItGame and Google-Ref datasetsにおいて、既存手法と比べてachieves the best IoU and precision
### 事前知識
- 既存の研究は、通常、前景/背景分類器に、それぞれ画像領域およびクエリ全体から抽出されたカスケード画像およびテキスト特徴を直接供給することによってこの課題を処理する
- 一方では、問合せ式の各単語が目的のオブジェクトを識別するために異なる貢献をすることを無視します。
- 参照画像のセグメンテーションでは、画像と自然言語の両方を分析する必要がある。
-------


## 新規性・結果・なぜ通ったか
## 先行研究と比べてどこがすごい？
## 技術や手法のキモはどこ？
## 議論はある？
## 次に読むべき論文は？
## 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
## デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
