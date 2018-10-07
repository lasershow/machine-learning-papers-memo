# 論文名
COTA: Improving the Speed and Accuracy of Customer Support through Ranking and Deep Networks
### 著者
### 学会名/ジャーナル名
### 論文へのリンク
http://www.kdd.org/kdd2018/accepted-papers/view/cota-improving-the-speed-and-accuracy-of-customer-support-through-ranking-a
-------

## 概要
カスタマーサポートのためのチケット分類システムとテンプレート推薦システム

ユーザーの情報、お問い合わせのテキスト情報からチケットの種類分類とそれに関する返信のテンプレートの推薦を行う。



- 情報を抽出して、重要度
- 関連する情報を抽出して、返信する

- チケット分類システム(not hand craft)

### 事前知識

- 文章を分析して、特定のカスタマーサポートに通知する
- お問い合わせの種類の特定と解決策の選択
- カスタマーサポートでは多くのテンプレートが用意されているはず
- カスタマーサポートでの分類がかなり変更されることが予想される
- amazonのカスタマーサポートツール、お客様の特徴や購入履歴、最近よくおこっていること・問題点
- 実際にカスタマーサポートを確認する


問題を分類して、テンプレートを選択するシステム
Customer Obsession Ticket Assistant (COTA)

#### トピックモデル
#### TFIDF
#### Latent Semantic Analysis
https://nlp.stanford.edu/IR-book/html/htmledition/latent-semantic-indexing-1.html
#### Pointwise-Ranking
### アイデア

-------

## 新規性・結果・なぜ通ったか
マルチ分類の問題をランキング問題へ転換して考えた(v1)
encoder combine decoderの新規DL手法を提案(v2)
## 先行研究と比べてどこがすごい？
カスタマーサポートの正確さと速度を高めることに注力している。
先行研究の場合（感情的なお問い合わせを分類する等）
## 技術や手法のキモはどこ？
## 議論はある？
## 次に読むべき論文は？
## 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
## デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
