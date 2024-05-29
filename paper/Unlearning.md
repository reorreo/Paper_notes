# Unlearning


## Title List

1. [MisDetect: Iterative Mislabel Detection using Early Loss(2024)]
2. [Towards Unbounded Machine Unlearning(2023:NeurIPS)]


---

### MisDetect: Iterative Mislabel Detection using Early Loss(2024)
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

### Towards Unbounded Machine Unlearning(2023:NeurIPS)
[[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/062d711fb777322e2152435459e6e9d9-Paper-Conference.pdf)
[[bibtex]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/062d711fb777322e2152435459e6e9d9-Abstract-Conference.html)
<details><summary>summary</summary><div>
忘却させる際に，忘却エラーが大きくなりすぎるとMIA(メンバーシップ推論攻撃)に対して脆弱になってしまうから．
忘却の定義を新たにしている．
教師生徒モデルを使っている．
</div></details> 
- Keywords : `` 
