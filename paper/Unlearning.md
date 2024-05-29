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
第1段階
損失が高いやつはラベルが違うと判断している・・・(1)
ついでに早期から損失が最小のインスタンスを使ってダブルチェックしている．・・・(2)
エントロピーを用いてnoisyに適応したと判断して1段階目を停止する
第2段階
上記のどちらにも含まれないやつに対しては2値分類モデルをトレーニングする((1) → -1, (2) → 1)
第2段階では特徴量や2値分類結果も含めてK-NNを用いて分類している？ → K-NNではなくMLPで分類しているかも？2値分類モデルがMLPなだけ?

</div></details> 
- Keywords : `Mislabel` 

