
# Noisy Label


## Title List

1. [Adaptive Integration of Partial Label Learning and Negative Learning for Enhanced Noisy Label Learning]
2. [Regroup Median Loss for Combating Label Noise (2024:AAAI)]
3. [Learning Accurate Pseudo-Labels via Feature Similarity in the(MDPI)]

---


### Adaptive Integration of Partial Label Learning and Negative Learning for Enhanced Noisy Label Learning(2024:AAAI)
[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/28284/28559)
[[Code]](https://github.com/NUST-Machine-Intelligence-Laboratory/NPN)
[[bibtex]](https://ojs.aaai.org/index.php/AAAI/article/view/28284)
<details><summary>summary</summary><div>
データセットがCIFAR-100から派生したCIFAR-100N使っている．
部分ラベル学習(PLL:各サンプルに複数のラベルが与えられる)とNegative learning(NL)を統合している．
PLLで複数のラベルが含まれているから正解ラベルが含まれていることが保証されるようにしている．信頼性とかを使っているぽい
NLを用いて入力された画像はこの補完ラベルに属さないみたいなことを学習しているぽい?
</div></details> 

### Regroup Median Loss for Combating Label Noise (2024:AAAI)
[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/29250/30360)
[[Code]](https://github.com/Feng-peng-Li/Regroup-Loss-Median-to-Combat-Label-Noise)
[[bibtex]](https://ojs.aaai.org/index.php/AAAI/article/view/29250)
<details><summary>summary</summary><div>
Instanceノイズが登場している(CIFAR)
CIFAR-10のSymmetric50%で90%弱だったのであまり正解率高くない?
ノイズのあるサンプルの損失を修正する．
トレーニングサンプルと同じラベルを持つサンプルをランダムに選択し，再グループ化する．
</div></details> 

### Learning Accurate Pseudo-Labels via Feature Similarity in the(MDPI)
[[Paper]](https://www.mdpi.com/2076-3417/14/7/2759/pdf?version=1711447152)
[[bibtex]](https://www.mdpi.com/2076-3417/14/7/2759)
<details><summary>summary</summary><div>
モデル予測と特徴量の類似性からの情報を利用する特徴擬似ラベル(FPL)を使っている．
精度Clothing1Mで73.54%
CIFARは少し低そうな印象
各クラスの特徴の中心(式を見た感じ論文で用いた重心とは違いそうだった)を計算し，各サンプルとのcos類似度を求め，最も類似性の高いクラスを特徴ラベル(ハードラベル？)とする．特徴ラベルとモデルの予測クラスから特徴擬似ラベルを作成している．
特徴量に対する擬似ラベルを考えている．
次やりたかったことに似ている気がする．
</div></details> 
- Keywords : `` 'Contrastive Learning?'

### LSV-Learner: Support-Vector Contrastive Learning for Robust Learning with Noisy Labels(IEEE2024)
[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10495194)
[[code]](https://github.com/yanliji/SV-Learner)
[[bibtex]](https://ieeexplore.ieee.org/abstract/document/10495194)
<details><summary>summary</summary><div>
対照学習にサポートベクターマシン(SVM)を導入した(SVCL)を使っている．
各クラスの特徴分布境界でSVMを考える．ここで，サポートベクトルはクリーンなセットから選択する．
TCLが引用されていた
精度が高い
</div></details> 
- Keywords : `` 'Contrastive Learning?'

### SigCo: Eliminate the inter-class competition via sigmoid for learning with noisy labels
[[Paper]](https://www.sciencedirect.com/science/article/pii/S0950705124002867/pdfft?md5=72834ccd19b2e5df1d78b240ef15b865&pid=1-s2.0-S0950705124002867-main.pdf)
[[bibtex]](https://www.sciencedirect.com/science/article/pii/S0950705124002867)
<details><summary>summary</summary><div>
データセットはCIFAR-10N, CIFAR-100Nなどを使っている
データをシグモイド予測に基づいて，サンプルをクリーン，ハード，ノイジーに分割する
また，ネットワークの表現学習を暗黙的に学習している．
そのため，対照学習も用いている．
精度が高い
</div></details> 
- Keywords : `` 'Contrastive Learning?'
