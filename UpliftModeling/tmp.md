https://arxiv.org/abs/1807.07909

- This paper presents an adaptation of boosting to the uplift modeling case.
- in this paper we demonstrate that it can bring similar benefits to uplift modeling.
- We begin by stating three desirable properties of an uplift boosting algorithm.
Since all three cannot be satisfied at the same time, we propose three uplift
boosting algorithms, each satisfying two of them


Fundamental Problem of Causal Inference.
- 各データに関して、どちらかの現象を確認することができない問題

t treatment groups
C control groups

datasets d
DT ∪ DC

Each data record (x, y) consists of a vector of features x ∈ X and a class
y ∈ {0, 1} with 1 assumed to be the successful outcome,
