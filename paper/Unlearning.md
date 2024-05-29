# Unlearning


## Title List

1. [Adaptive Integration of Partial Label Learning and Negative Learning for Enhanced Noisy Label Learning]


---

### MisDetect: Iterative Mislabel Detection using Early Loss
[[Paper]](https://dl.acm.org/doi/pdf/10.14778/3648160.3648161)
[[bibtex]](https://dl.acm.org/doi/abs/10.14778/3648160.3648161)
<details><summary>summary</summary><div>
github貼ってあるが404となる
Mislabelの多くの手法が説明されていた
やっぱりMislabelを見つけるのは難しそう
Mislabel ratio20%のCIFAR-10でF1 score 0.8622 
memorizationぽいことを使っている
損失が高いやつはラベルが違うと判断している・・・(1)
ついでに早期から損失が最小のインスタンスを使ってダブルチェックしている．・・・(2)
上記のどちらにも含まれないやつに対しては2値分類モデルをトレーニングする((1) → -1, (2) → 1)
</div></details> 
- Keywords : `Mislabel` 

