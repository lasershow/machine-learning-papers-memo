------------
## 論文名
### 著者
### 新規性・結果・なぜ通ったか
### 先行研究と比べてどこがすごい？
### 技術や手法のキモはどこ？
### 議論はある？
### アイデア
### 次に読むべき論文は？
### 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
### デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
### 参考

------------
## 論文名
Conversion upliftine-commerce:A systematic benchmark of modeling strategies
### 概要
- Eコマースに関する、包括的な調査
- Conversion modeling using uplift vs. response models
  -

### 新規性・結果・なぜ通ったか
### 先行研究と比べてどこがすごい？
### 技術や手法のキモはどこ？
### 議論はある？
### アイデア
### 次に読むべき論文は？
to identify the most suitable channel to contact custmer in MULTI channel advertising
( (Zantedeschi et al., 2016), )

- あるお客に対して、どのようなクーポンか行動を起こすべきかは検討していきたい。

which is more general
than campaign and used in the econometrics literature on causal inference (Athey & Imbens,
2017).

- causal inferenceからどのようなことが可能か

Another example arises in marketing where a marketer is interested to estimate how actions
in the form of marketing messages (newsletters, telephone calls, etc.) alter the purchase behavior
of customers (Dost et al., 2014)

- 様々な介入が行動にどのような影響を与えるか
### 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
### デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
### 参考


------------
ちょっとマーケティング系の論文もあさっていく

## 論文名
Uplift Modeling　in Direct Marketing
### 概要
ダイレクトマーケティングにおけるuplift
問題設定的には自分と同じ

- 実際にマーケティング結果に大きい結果をもたらしたことを記している
### 新規性・結果・なぜ通ったか
### 先行研究と比べてどこがすごい？
### 技術や手法のキモはどこ？
### 議論はある？
### アイデア
### 次に読むべき論文は？
### 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
### デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
### 参考
------------
## 論文名
Uplift Modeling from Separate Labels
### 著者
### 概要
https://arxiv.org/pdf/1803.05112.pdf
- estimation under the presence of systematic missing labels.
- neural networks. On the other hand, model
selection may be a challenging problem due to the min-max structure. Addressing this issue would be
important research directions for further expanding the applicability and improving the performance
of the proposed method.

欠損したラベルをどのように扱うか、というNIPSで発表された論文


### 新規性・結果・なぜ通ったか
### 先行研究と比べてどこがすごい？
### 技術や手法のキモはどこ？
### 議論はある？
### アイデア
### 次に読むべき論文は？
### 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
### デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
### 参考



------------
## 論文名
A Large Scale Benchmark for Uplift Modeling

https://docs.wixstatic.com/ugd/b6ac34_c8b6d5eec3c04fe2ba2439b89c71f4b3.pdf
### 著者
### 概要
adkddのupliftmodelingのベンチマークとデータ・セット
### 新規性・結果・なぜ通ったか
### 先行研究と比べてどこがすごい？
### 技術や手法のキモはどこ？
### 議論はある？
### アイデア
### 次に読むべき論文は？

Nicholas J Radcliffe and Patrick D Surry. Real-World Uplift Modelling with
Significance-Based Uplift Trees. 2011. 二回目

Pierre Gutierrez and Jean-Yves Gérardy. Causal Inference and Uplift Modeling A
review of the literature. 67:1–13, 2016

Ikko Yamane, Florian Yger, and Masashi Sugiyama. Uplift Modeling from Separate
Labels. pages 1–18, 2018.
### 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
### デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
### 参考

------------
## 論文名
Uplift Modeling with Multiple Treatments and General Response Types


https://scholar.google.es/citations?view_op=top_venues&hl=en&vq=eng_datamininganalysis (datamining conf ranking )

https://epubs.siam.org/doi/abs/10.1137/1.9781611974973.66
Proceedings of the 2017 SIAM International Conference on Data Mining

### 著者
### 概要

- 通常のアップリフトモデリングでは、代替治療との結果を比較することができない。それは例えば同じ患者に他の治療方法を試すことはできないから。（同時期に）

- 15% - 40% more revenue than non-uplift algorithms with the priority boarding and seat reservation data
- 数式を見た感じ、multipleに対応できそう、それぞれの異なる介入で最大のものを選択する感じかー、
  - どうやって学習データを確保するんだろうか
  -
- 航空会社の座席の例
  - 席は三種類
  - The response is the revenue from each
transaction.
  - The features we use include the booking hour,
the booking weekday, the travel hour, the travel weekday, the number of days between the last login and the
next flight, the fare class, the zone code (all flight routes
are divided into 3 zones, ..
- この問題をクーポンに置き換えれば良い、いくつかの価格設定でどのくらいの。。。
### 新規性・結果・なぜ通ったか
### 先行研究と比べてどこがすごい？
### 技術や手法のキモはどこ？
### 議論はある？
### アイデア
### 次に読むべき論文は？
N. J. Radcliffe and P. D. Surry, Real-world uplift
modelling with significance-based uplift trees, White
Paper TR-2011-1, Stochastic Solutions (2011).

M. Sotys, S. Jaroszewicz, and P. Rzepakowski, Ensemble methods for uplift modeling. Data mining and
knowledge discovery 29.6 (2015), pp. 1531-1559.

P. Rzepakowski and S. Jaroszewicz, Decision trees for
uplift modeling with single and multiple treatments,
Knowledge and Information Systems 32.2 (2011), pp.
303-327.

N. J. Radcliffe, Using control groups to target on
predicted lift: Building and assessing uplift models,
Direct Market J Direc


### 次の研究トレンドを作れるような問題を提案しているかどうか（e.g. Taskonomy, ImageNet）
### デファクトスタンダードになるような手法を提案しているかどうか（e.g. ResNet, R-CNN）
### 参考
