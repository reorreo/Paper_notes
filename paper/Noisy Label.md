
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
サポートベクトル対照学習(SVCL)は、サポートベクトルを使用して超平面を構築し、異なるカテゴリの特徴分布間の超平面マージンを最大化することで、特徴分布の収束を最適化し、半教師付き分類に役立つ。
精度が高い
</div></details> 
- Keywords : `` 'Contrastive Learning?'

### SigCo: Eliminate the inter-class competition via sigmoid for learning with noisy labels
[[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Selective-Supervised_Contrastive_Learning_With_Noisy_Labels_CVPR_2022_paper.pdf)
[[bibtex]](https://www.sciencedirect.com/science/article/pii/S0950705124002867)
<details><summary>summary</summary><div>
データセットはCIFAR-10N, CIFAR-100Nなどを使っている
クラスごとにしきい値を用いて判断しており，複数のクラスでしきい値を超えたサンプルはハードとしている．
データをシグモイド予測に基づいて，サンプルをクリーン，ハード，ノイジーに分割する
また，ネットワークの表現学習を暗黙的に学習している．
そのため，対照学習も用いている．
この際ポジティブとしてクリーンセット内の同じクラスのサンプルを選択している．
精度が高い
</div></details> 
- Keywords : `` 'Contrastive Learning?'

### Manifold DivideMix: A Semi-Supervised Contrastive Learning Framework for Severe Label Noise(CVPR2024)
[[Paper]](https://openaccess.thecvf.com/content/CVPR2024W/VAND/papers/Fooladgar_Manifold_DivideMix_A_Semi-Supervised_Contrastive_Learning_Framework_for_Severe_Label_CVPRW_2024_paper.pdf)
[[code]](https://github.com/Fahim-F/ManifoldDivideMix)
[[bibtex]](https://openaccess.thecvf.com/content/CVPR2024W/VAND/html/Fooladgar_Manifold_DivideMix_A_Semi-Supervised_Contrastive_Learning_Framework_for_Severe_Label_CVPRW_2024_paper.html)
<details><summary>summary</summary><div>
ベースはDivideMix
はじめに対照学習を用いて埋め込み空間を学習する(warmup)
ラベルの信頼度は埋め込み空間に基づいて分布外検出を用いて行われている(TCLと同じやと思う)
MixUpにサンプル，ラベルの他に埋め込み空間でも結合している
</div></details> 
- Keywords : `` 'Contrastive Learning?'

### Selective-Supervised Contrastive Learning With Noisy Labels(CVPR2022)
[[Paper]](https://openaccess.thecvf.com/content/CVPR2024W/VAND/papers/Fooladgar_Manifold_DivideMix_A_Semi-Supervised_Contrastive_Learning_Framework_for_Severe_Label_CVPRW_2024_paper.pdf)
[[code]](https://github.com/ShikunLi/Sel-CL)
[[bibtex]](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Selective-Supervised_Contrastive_Learning_With_Noisy_Labels_CVPR_2022_paper.html)
<details><summary>summary</summary><div>
選択的教師あり対照学習を用いている
選択手法は，対照サンプルに対して類似度の高いサンプルのラベルで多数決を取る. 1つのクラスが擬似ラベルとして割り振られるイメージ(擬似ラベル1とする)
擬似ラベル1を基に，類似性の高いサンプルのラベルの割合を擬似ラベルとする．
</div></details> 
- Keywords : `` 'Contrastive Learning?'

### UniCon: Combating Label Noise Through Uniform Selection and Contrastive Learning(CVPR2022)
[[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Karim_UniCon_Combating_Label_Noise_Through_Uniform_Selection_and_Contrastive_Learning_CVPR_2022_paper.pdf)
[[code]](https://github.com/nazmul-karim170/UNICON-Noisy-Label)
[[bibtex]](https://openaccess.thecvf.com/content/CVPR2022/html/Karim_UniCon_Combating_Label_Noise_Through_Uniform_Selection_and_Contrastive_Learning_CVPR_2022_paper.html)
<details><summary>summary</summary><div>
ラベルありサンプルの個数をクラス毎に均等にしている．
FixMatchベースのSSLに教師なし対照学習を組み込んでいる
</div></details> 
- Keywords : `` 'Contrastive Learning?'


### Adaptive Contrastive Learning for Learning Robust(2023)
[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3581783.3612491)
[[bibtex]](https://dl.acm.org/doi/abs/10.1145/3581783.3612491)
<details><summary>summary</summary><div>
ラベルありサンプルの個数をクラス毎に均等にしている．
FixMatchベースのSSLに教師なし対照学習を組み込んでいる
</div></details> 
- Keywords : `` 'Contrastive Learning?'


### UniCon: Combating Label Noise Through Uniform Selection and Contrastive Learning(CVPR2022)
[[Paper]](https://openaccess.thecvf.com/content/CVPR2022/papers/Karim_UniCon_Combating_Label_Noise_Through_Uniform_Selection_and_Contrastive_Learning_CVPR_2022_paper.pdf)
[[code]](https://github.com/nazmul-karim170/UNICON-Noisy-Label)
[[bibtex]](https://openaccess.thecvf.com/content/CVPR2022/html/Karim_UniCon_Combating_Label_Noise_Through_Uniform_Selection_and_Contrastive_Learning_CVPR_2022_paper.html)
<details><summary>summary</summary><div>
適応的対照学習法(ACLを提案)→ 固定されたしきい値の代わりに，自己適応的しきい値を使用して，対照学習のペアを選択する
</div></details> 
- Keywords : `` 'Contrastive Learning?'

### RankMatch: Fostering Confidence and Consistency in Learning with Noisy Labels(ICCV2023):RankMatch
[[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_RankMatch_Fostering_Confidence_and_Consistency_in_Learning_with_Noisy_Labels_ICCV_2023_paper.pdf)
[[bibtex]](https://openaccess.thecvf.com/content/ICCV2023/html/Zhang_RankMatch_Fostering_Confidence_and_Consistency_in_Learning_with_Noisy_Labels_ICCV_2023_paper.html)
<details><summary>summary</summary><div>
信頼投票によるサンプリングを導入 → 信頼できるサンプルからの重心をクラスタ平均とする(各クラスプロトタイプ複数個できる感じやと思う)
対照学習では，特徴ベクトルに重要度をつけて重要度が高いところの類似性が高くなることを優先して学習している?
</div></details> 

### Supervised contrastive learning with corrected labels for noisy label learning(2023)
[[Paper]](https://link.springer.com/content/pdf/10.1007/s10489-023-05018-0.pdf)
[[code]](https://github.com/ChenyangLu922/SCL2.git)
[[bibtex]](https://link.springer.com/article/10.1007/s10489-023-05018-0)
<details><summary>summary</summary><div>
教師あり対照学習に修正ラベルの概念を導入した．同じソフトラベルを共有するサンプルは正のペアとしている．また，プロトタイプを用いた対照学習も行っている．
</div></details> 
- Keywords : `` 'Contrastive Learning?'

### NoiseBox: Towards More Efficient and Effective Learning with Noisy Labels(IEEE2024)
[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10594806)
[[bibtex]](https://ieeexplore.ieee.org/abstract/document/10594806)
<details><summary>summary</summary><div>
NoiseBoxを導入した学習法．精度がすごく高い．NoiseBoxがしっかり理解できてないが同一のアーキテクトを学習している感じだと考える．
</div></details> 
- Keywords : `` 'Contrastive Learning?'

### Learning with Structural Labels for Learning with Noisy Labels (CVPR2024)
[[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Kim_Learning_with_Structural_Labels_for_Learning_with_Noisy_Labels_CVPR_2024_paper.pdf)
[[bibtex]](https://openaccess.thecvf.com/content/CVPR2024/html/Kim_Learning_with_Structural_Labels_for_Learning_with_Noisy_Labels_CVPR_2024_paper.html)
<details><summary>summary</summary><div>
CIFAR-10 Sym.20%の正解率97%超えていた．
分布情報構造ラベルを導入した．これは，
</div></details> 
- Keywords : `` 

### Learning with Structural Labels for Learning with Noisy Labels (CVPR2024)
[[Paper]](https://arxiv.org/pdf/2401.04390)
[[bibtex]](https://arxiv.org/abs/2401.04390)
<details><summary>summary</summary><div>
CIFAR-10 Sym.20%の正解率97%超えていた．
mineネットワークと補助ネットワークを使って学習していた．
補助ネットワークは擬似ラベルを推定するために存在する．
</div></details> 
- Keywords : `` 

