
# Noisy Label


## Title List

1. [Adaptive Integration of Partial Label Learning and Negative Learning for Enhanced Noisy Label Learning (2024:AAAI)]
2. [Regroup Median Loss for Combating Label Noise (2024:AAAI)]
3. [Learning Accurate Pseudo-Labels via Feature Similarity in the(MDPI)]
4. [LSV-Learner: Support-Vector Contrastive Learning for Robust Learning with Noisy Labels (IEEE2024)]
5. [SigCo: Eliminate the inter-class competition via sigmoid for learning with noisy labels (CVPR2022)]
6. [Manifold DivideMix: A Semi-Supervised Contrastive Learning Framework for Severe Label Noise (CVPR2024)]
7. [Selective-Supervised Contrastive Learning With Noisy Labels (CVPR2022)]
8. [UniCon: Combating Label Noise Through Uniform Selection and Contrastive Learning (CVPR2022)]
9. [Adaptive Contrastive Learning for Learning Robust (2023)]
10. [UniCon: Combating Label Noise Through Uniform Selection and Contrastive Learning (CVPR2022)]
11. [RankMatch: Fostering Confidence and Consistency in Learning with Noisy Labels (ICCV2023)]
12. [Supervised contrastive learning with corrected labels for noisy label learning (2023)]
13. [NoiseBox: Towards More Efficient and Effective Learning with Noisy Labels (IEEE2024)]
14. [Learning with Structural Labels for Learning with Noisy Labels (CVPR2024)]
15. [Learning with Noisy Labels Interconnection of Two Expectation-Maximizations (CVPR2024)]
16. [Subclass-Dominant Label Noise: A Counterexample for the Success of Early Stopping (NeurIPS2023)]
17. [BPT-PLR: A Balanced Partitioning and Training Framework with Pseudo-Label Relaxed Contrastive Loss for Noisy Label Learning]
18. [Enhancing Noisy Label Learning Via Unsupervised Contrastive Loss with Label Correction Based on Prior Knowledge]
19. [ProMix: Combating Label Noise via Maximizing Clean Sample Utility]
20. [Prediction Consistency Regularization for Learning with Noise Labels Based on Contrastive Clustering]
21. [Learning transferable visual models from natural language supervision]
22. [Improving CLIP Robustness with Knowledge Distillation and Self-Training]
23. [Robust Noisy Label Learning via Two-Stream Sample Distillation]
24. [CLIPCleaner: Cleaning Noisy Labels with CLIP]
25. [Vision-Language Models are Strong Noisy Label Detectors]
26. [FedPPO: Reinforcement Learning-Based Client Selection for Federated Learning With Heterogeneous Data]
27. [Reinforcement Learning-Guided Semi-Supervised Learning]
28. [Domain adaptation in reinforcement learning: a comprehensive and systematic study]

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
NoiseBoxを導入した学習法．精度がすごく高い．既存のサンプル選択の多くと組み合わせることが可能
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

### Learning with Noisy Labels Interconnection of Two Expectation-Maximizations (CVPR2024)
[[Paper]](https://arxiv.org/pdf/2401.04390)
[[bibtex]](https://arxiv.org/abs/2401.04390)
<details><summary>summary</summary><div>
CIFAR-10 Sym.20%の正解率97%超えていた．
mineネットワークと補助ネットワークを使って学習していた．
補助ネットワークは擬似ラベルを推定するために存在する．
</div></details> 
- Keywords : `` 

### Subclass-Dominant Label Noise: A Counterexample for the Success of Early Stopping
[[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/d763b4a2dde0ae7b77498516ce9f439e-Paper-Conference.pdf)
[[code]](https://github.com/tmllab/2023_NeurIPS_SDN)
[[bibtex]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/d763b4a2dde0ae7b77498516ce9f439e-Abstract-Conference.html)
<details><summary>summary</summary><div>
NoiseClusterの基本原理は「レイターストッピング（later stopping）」に基づいている。従来はノイズデータが時間とともに表現を劣化させると考えられていたが，本研究では，レイターストッピングによって得られる長期間トレーニングされた表現が，ノイズのある例の高次の意味をより効果的に捉えることができることを示している。これにより，特徴が似ているノイズのある例の埋め込みが互いに近づくクラスタリング効果が生じる。
具体的には，まずネットワークのトレーニングをレイターストッピングで停止した後，特徴密度に基づいてこれらの特徴をクラスごとにグループ化し，最も大きなグループを「クリーングループ」として識別する。これは正しいラベルである可能性が高いためであり，残りのグループは「誤ラベルの可能性があるグループ」として扱う。
</div></details> 
- Keywords : `` 

### BPT-PLR: A Balanced Partitioning and Training Framework with Pseudo-Label Relaxed Contrastive Loss for Noisy Label Learning
[[Paper]](file:///Users/reo/Desktop/entropy-26-00589.pdf)
[[code]](https://github.com/LanXiaoPang613/BPT-PLR)
[[bibtex]](https://www.mdpi.com/1099-4300/26/7/589)
<details><summary>summary</summary><div>
本研究では「BPT-PLR」と呼ばれる，擬似ラベル緩和コントラスト損失を用いたバランス分割・訓練フレームワークを提案する。このフレームワークは，2次元ガウス混合モデルを用いたバランス分割プロセス（BP-GMM）と，擬似ラベル緩和コントラスト損失を用いた半教師ありオーバーサンプリング訓練プロセス（SSO-PLR）という2つの重要なプロセスから構成される。前者は，意味的な特徴情報とモデルの予測結果の両方を利用してノイズラベルを識別し，分割されたサブセット間のクラスバランスを可能な限り保つためのバランス調整戦略を導入する。後者は，最新の擬似ラベル緩和コントラスト損失を採用して教師なしコントラスト損失を置き換え，半教師あり学習と教師なしコントラスト損失間の最適化の衝突を軽減し，性能を向上させる。
精度はめっちゃ高い
</div></details> 
- Keywords : `` 

### Enhancing Noisy Label Learning Via Unsupervised Contrastive Loss with Label Correction Based on Prior Knowledge
[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10446840)
[[code]](https://github.com/LanXiaoPang613/BPT-PLR)
[[bibtex]](https://ieeexplore.ieee.org/abstract/document/10446840)
<details><summary>summary</summary><div>
本手法では，事前学習済みの視覚・言語モデルの事前知識を導入することで，NLLの学習プロセスに依存せずにクリーンサンプルを効果的に選択することが可能となる。
提案手法では，データセット内の画像とラベルを事前学習済みの視覚と言語モデルによって構築された潜在空間に埋め込み，埋め込み表現間の距離に基づいてラベル修正を行う．
CIFAR-10,100のSym.80,90%しか実験してないが，CIFAR-10では，Sym.20%とあまり変わらない正解率(96.8)．CIFAR-100でも70を超えている．
</div></details> 
- Keywords : `` 

### ProMix: Combating Label Noise via Maximizing Clean Sample Utility
[[Paper]](https://arxiv.org/pdf/2207.10276)
[[code]](https://github.com/Justherozen/ProMix)
[[bibtex]](https://arxiv.org/abs/2207.10276)
<details><summary>summary</summary><div>
観測されたラベルに対して高い予測スコアを持つサンプルを収集することで，基礎となるクラスごとの選択セットを動的に拡張する「進行的選択メカニズム」を提案する。
この最大選択手順には，SSLに対する副作用が伴う可能性がある。第一に，クリーンサンプルが異なるラベル間で均等に分布しない可能性があり，ラベル分布に偏りが生じる。第二に，選択手順と半教師あり学習手順が緊密に依存しているため，自らのエラーを繰り返し確認する「確認バイアス」に起因する問題が発生する可能性がある。これらの問題を軽減するために，以下の2つの主要な要素を含む「デバイアス化SSLトレーニングフレームワーク」を開発した。1つ目は補助的な擬似ヘッドで，信頼性の低い擬似ラベルの生成と利用を分離し，モデルがエラーを自己確認することを防ぐものである。2つ目は，偏った擬似ラベルとクロスエントロピー損失を同時に補正するキャリブレーションアルゴリズムを組み込むことである。
精度高い．特に低ノイズ率に強い
</div></details> 
- Keywords : `` 

### Prediction Consistency Regularization for Learning with Noise Labels Based on Contrastive Clustering
[[Paper]](https://www.mdpi.com/1099-4300/26/4/308/pdf?version=1712068099)
[[bibtex]](https://www.mdpi.com/1099-4300/26/4/308)
<details><summary>summary</summary><div>
観測されたラベルに対して高い予測スコアを持つサンプルを収集することで，基礎となるクラスごとの選択セットを動的に拡張する「進本研究では，ラベルノイズのある画像データに効果的に対応するために，ツインコントラストクラスタリングに基づく予測一貫性正則化（TPCR）を提案する。本手法は2つの主要なコンポーネントから成る。サンプルの類似性を正確かつ効率的に特定し，自己教師あり学習に伴うリスクを軽減するために，TPCRは表現学習のフレームワークとしてツインコントラストクラスタリング（TCC）【12】を採用した。TCCをラベル一貫性を反映する表現を生成できるよう改善し，最初のリスクに対処している。TCCのプレテキストタスクが入力サンプルを異なるグループにクラスタリングするため，同じクラスタに属するサンプルは追加計算なしに本質的に類似していると見なすことができ，2つ目のリスクを回避する。次に，改良されたTCCのクラスタリング結果に基づき，各クラスタ内での分類の一貫性を高めるため，モデル出力とプロトタイプ間のクロスエントロピーを罰則化するプロトタイプベースの正則化手法を設計した
</div></details> 
- Keywords : `` 

### Learning transferable visual models from natural language supervision
[[Paper]](http://proceedings.mlr.press/v139/radford21a/radford21a.pdf)
[[code]](https://github.com/OpenAI/CLIP)
[[bibtex]](http://proceedings.mlr.press/v139/radford21a)
<details><summary>summary</summary><div>
CLIP
</div></details> 
- Keywords : ``

### Improving CLIP Robustness with Knowledge Distillation and Self-Training
[[Paper]](https://arxiv.org/pdf/2309.10361)
[[code]](https://github.com/OpenAI/CLIP)
[[bibtex]](https://arxiv.org/abs/2309.10361)
<details><summary>summary</summary><div>
CLIPを教師なし学習で再学習している
教師あり学習の参考にできそう
</div></details> 
- Keywords : ``

### Robust Noisy Label Learning via Two-Stream Sample Distillation
[[Paper]](https://arxiv.org/pdf/2404.10499)
[[bibtex]]([https://arxiv.org/abs/2309.10361](https://arxiv.org/abs/2404.10499?utm_source=chatgpt.com))
<details><summary>summary</summary><div>
この手法では、サンプル選択とラベル補正を組み合わせ、ノイズの多いラベルを持つデータセットに対して、学習中に高品質なサンプルを抽出するTwo-Stream Sample Distillation（TSSD）フレームワークが提案されている。CIFAR-10やCIFAR-100などでの実験において、ノイズの影響を受けにくいモデルの学習が可能であることが示されている。精度が高い
</div></details> 
- Keywords : ``

### CLIPCleaner: Cleaning Noisy Labels with CLIP
[[Paper]](https://dl.acm.org/doi/pdf/10.1145/3664647.3680664)
[[bibtex]](https://dl.acm.org/doi/abs/10.1145/3664647.3680664)
<details><summary>summary</summary><div>
clipの予測値使って学習している．
</div></details> 
- Keywords : ``


### Vision-Language Models are Strong Noisy Label Detectors
[[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/6af08ba9468f0daca4b8dd388cb95824-Paper-Conference.pdf)
[[bibtex]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/6af08ba9468f0daca4b8dd388cb95824-Abstract-Conference.html)
<details><summary>summary</summary><div>
clipをファインチューニングしている
精度すごく高い
</div></details> 
- Keywords : ``

### FedPPO: Reinforcement Learning-Based Client Selection for Federated Learning With Heterogeneous Data
[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10909702)
[[bibtex]](https://ieeexplore.ieee.org/abstract/document/10909702)
<details><summary>summary</summary><div>
通信，計算コストを削減することを目的としている．
主成分分析を用いて，行動探索空間を縮小することで効率的に強化学習を行っている．
</div></details> 
- Keywords : ``

### Reinforcement Learning-Guided Semi-Supervised Learning
[[Paper]](https://arxiv.org/abs/2405.01760)
[[bibtex]](https://arxiv.org/pdf/2405.01760)
<details><summary>summary</summary><div>
半教師あり学習にRL損失を導入している．
本論文では、SSLを一方アームドバンディット問題として定式化し、重み付き報酬に基づく革新的なRL損失を導入して予測モデルの学習を適応的に導く、新しい強化学習（RL）ガイド付きSSL手法 RLGSSL を提案します。
</div></details> 
- Keywords : ``

### Domain adaptation in reinforcement learning: a comprehensive and systematic study
[[Paper]](https://link.springer.com/content/pdf/10.1631/FITEE.2300668.pdf)
[[bibtex]](https://link.springer.com/article/10.1631/FITEE.2300668)
<details><summary>summary</summary><div>
ドメイン適応に強化学習を追加している


</div></details> 
- Keywords : ``

### Design and Application of Adaptive Image Recognition Algorithm Based on Deep Reinforcement Learning
[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10667548)
[[bibtex]](https://ieeexplore.ieee.org/abstract/document/10667548)
<details><summary>summary</summary><div>

(pdf):Design_and_Application_of_Adaptive_Image_Recognition_Algorithm_Based_on_Deep_Reinforcement_Learning

強化学習とインクリメンタルラーニングフレームワークを用いている．
noisy labelsではない．

GPTによる翻訳

本論文では、深層強化学習（Deep Reinforcement Learning, DRL）に基づいた適応的画像認識アルゴリズムの設計と応用について提案している。従来のCNNモデルは、入力分布の変化に弱く、汎化能力に課題があることから、本研究では次の3つの工夫を導入している。
	1.	ResNetとDenseNetを融合したハイブリッドCNNの設計
　ResNetのショートカット接続とDenseNetの密結合構造を組み合わせることで、勾配消失の問題を緩和し、特徴伝搬を改善。パラメータ数を約20%削減しつつ、分類精度を向上。
	2.	適応的データ拡張（Adaptive Data Augmentation）
　損失関数の勾配に基づき、データ拡張の種類や強度を動的に調整。これにより、データ分布の変化に柔軟に対応し、モデルの汎化性能を向上。
	3.	効率的オンライン学習フレームワークの構築
　新カテゴリや環境変化に対して、既存の特徴抽出層は凍結し、分類層のみを更新。また、パラメータの一部だけをファインチューニングすることで計算コストを最大90%削減。過学習を防ぎつつ、モデルが継続的に知識を吸収可能にしている。

さらに、強化学習を用いた動的ハイパーパラメータ制御や、知識勾配に基づくインクリメンタル学習も導入されている。実験では、CIFAR-10およびImageNetのサブセットを用いた画像分類タスクにおいて、ベースラインと比較して5%以上の認識精度向上を実現。特に転移学習や新規カテゴリへの適応で高い頑健性を示した。

結論として、本研究は動的環境への適応力と学習効率を備えた、知能的かつ拡張可能な視覚解析システムの構築に向けた新たな方向性を示している。
</div></details> 
- Keywords : ``

### Harnessing deep reinforcement learning algorithms for image categorization: A multi algorithm approach
[[Paper]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10667548)
[[bibtex]](https://www.sciencedirect.com/science/article/abs/pii/S0952197624010832)
<details><summary>summary</summary><div>

PDFは有料やから開いていない

強化学習
noisy labelsではない．

GPTによる翻訳
概要:

本研究では、深層強化学習（Deep Reinforcement Learning, DRL）アルゴリズムを画像分類タスクに適用し、その性能を複数のベンチマークデータセット上で比較検討しています。

研究の背景と目的:

画像分類はコンピュータビジョンにおける基本的な課題であり、従来は主に教師あり学習手法が用いられてきました。しかし、DRLの発展により、エージェントが環境との相互作用を通じて学習する新たなアプローチが可能となっています。本研究の目的は、異なるDRLアルゴリズムを画像分類に適用し、その有効性と性能を評価することです。

結論:

本研究は、DRLアルゴリズムが画像分類タスクにおいて有望な手法であることを示しています。特に、Dueling DQNとPPOは高い分類精度を達成し、A3Cは学習の安定性に寄与することが確認されました。これらの結果は、DRLを画像分類に応用する際の有効な選択肢となる可能性を示唆しています。
</div></details> 
- Keywords : ``

### Image Classification by Reinforcement Learning With Two-State Q-Learning
[[Paper]](https://arxiv.org/pdf/2007.01298)
[[bibtex]](https://onlinelibrary.wiley.com/doi/abs/10.1002/9781119792642.ch9)
<details><summary>summary</summary><div>

(PDF):s12530-024-09632-2

強化学習
noisy labelsではない．

本研究は、深層強化学習（Deep Reinforcement Learning, DRL）を応用した画像分類アルゴリズムの体系的な評価と比較を行ったものである。従来の画像分類は主に教師あり学習に依存していたが、本研究は探索と報酬に基づいて最適戦略を学習するDRLの有効性を検証することを目的としている。

主な貢献
	1.	5つの代表的なDRLベース分類アルゴリズム（DQN, DDQN, Dueling DQN, A3C, PPO）を選定し、比較。
	2.	実験にはMNIST、CIFAR-10、Fashion-MNIST、SVHNといった標準的な画像分類データセットを使用。
	3.	比較指標として、分類精度、訓練時間、報酬獲得率、安定性を用いた。
	4.	さらに、異なるDRL構造や損失関数、報酬設計、割引率γなどの要因が性能に与える影響について詳細に解析した。

主な結果
	•	**PPO（Proximal Policy Optimization）とA3C（Asynchronous Advantage Actor-Critic）**が多くの評価指標において最も優れた性能を示した。
	•	Dueling DQNはDQNよりも優れた安定性を持ち、報酬設計が学習の効率に大きな影響を与えることが確認された。
	•	ただし、DRLベースの分類器は従来のCNN分類器と比べて精度でやや劣る一方で、学習戦略の柔軟性やロバスト性において利点がある。

結論

DRLは、画像分類タスクにおいて完全に教師ありな手法の代替にはならないが、探索的・自己強化的学習が必要な場面において有用である。また、報酬関数や状態設計が精度向上に大きく寄与するため、今後はこの設計面の最適化が鍵となる。
</div></details> 
- Keywords : ``

### Adaptive patch selection to improve Vision Transformers through Reinforcement Learning
[[Paper]](https://link.springer.com/article/10.1007/s10489-025-06516-z)
[[bibtex]](https://link.springer.com/article/10.1007/s10489-025-06516-z)
<details><summary>summary</summary><div>

(PDF):s10489-025-06516-z

ViTを強化学習で効率的に学習している．
AgentViT: Reinforcement Learning for Token Sparsification in Vision Transformers

概要:

本研究は、Vision Transformer（ViT）の計算効率を向上させるために、強化学習（RL）を用いた動的なトークン選択手法「AgentViT」を提案する。ViTではすべてのパッチを同等に処理するため、計算コストが高くなる問題がある。AgentViTは、ViTの注意機構から得られる情報をもとに重要なパッチのみを選択し、無駄な計算を削減する。

主な貢献:
	1.	新しいRLフレームワークの導入:
	•	Deep Q-Network（DQN）に基づくポリシーにより、画像のパッチ選択を動的に行う。
	•	状態はViTの最初の注意層から得られる平均注意スコアに基づく。
	•	報酬関数は精度と計算効率のバランスを考慮。
	2.	高い汎化性能:
	•	AgentViTはデータセットやモデルアーキテクチャを問わず、パッチ選択のポリシーを自律的に最適化する。
	•	過剰な削減（over-pruning）や不足（under-pruning）を防ぐ機構を備える。
	3.	評価実験:
	•	CIFAR-10、ImageNetなど複数の画像分類ベンチマークで実験。
	•	AgentViTは、精度を維持しつつ推論時間を大幅に削減。
	•	他のトークン削減法（DynamicViTなど）と比較して優れた性能を示す。

結論:

AgentViTは、ViTのパッチ処理において、効率と精度を両立させる新しい枠組みを提供する。強化学習により、事前定義されたルールに依存せず適応的にトークンを選択することで、さまざまなタスクやモデルに対して高い適用性を持つ。
</div></details> 
- Keywords : ``

### Strategic data navigation: information value-based sample selection
[[Paper]](https://link.springer.com/content/pdf/10.1007/s10462-024-10813-3.pdf)
[[bibtex]](https://link.springer.com/article/10.1007/s10462-024-10813-3)
<details><summary>summary</summary><div>

(PDF):s10462-024-10813-3.p

概要:

[cite_start]教師あり学習（SL）において、学習データのサンプリングは依然として非効率的であり、多くの場合、すべてのデータポイントに等しい価値を割り当てる均一分布に依存しています [cite: 40][cite_start]。しかし、データポイントが持つ情報の価値は一様ではありません [cite: 10][cite_start]。本研究は、強化学習（RL）の分野、特にPrioritized Experience Replay（PER）の原則に着想を得て [cite: 36, 71][cite_start]、教師あり学習における分類精度を向上させるための新しい動的なサンプル優先順位付けアプローチを提案します [cite: 12, 456]。

主な貢献:
	1.	**RLの優先順位付け手法のSLへの適用:**
	•	RLにおける探索（Exploration）と活用（Exploitation）のトレードオフが、SLにおけるアンダーフィッティングとオーバーフィッティングの問題に対応すると捉え [cite: 160]、サンプル優先度を動的に更新するフレームワークを提案しました [cite: 195, 199]。
	2.	**2つの情報価値メトリクスの提案:**
	•	RLのTD誤差に着想を得た「Probability Error（PB Error）」 [cite: 184, 187]と、よりSLの文脈に即した「Label Change Error（LC Error）」の2つのメトリクスを導入し、サンプルの情報価値を評価します [cite: 232, 235]。
	3.	**過学習の制御:**
	•	優先順位付けによる過学習リスクを軽減するため、サンプルの使用頻度（探索項）と情報価値（活用項）のバランスを調整するハイパーパラメータ $c_p$ を導入しました [cite: 167, 172, 248]。

結論:

[cite_start]本アプローチをCIFAR-10、CIFAR-100、TinyImagenetデータセットと複数のアーキテクチャ（ResNet50, Mobilenet V3など）で評価しました [cite: 45, 296, 298][cite_start]。特に「Label Change Error」メトリクスを使用した場合、従来の均一サンプリングと比較して、すべてのケースで一貫して分類精度が向上（例：CIFAR-100で最大+0.817%）することを確認しました [cite: 281, 296, 310][cite_start]。この結果は、提案する動的な優先順位付けが、計算コストを大幅に増加させることなく、モデル性能を効果的に改善することを示しています [cite: 301, 430]。
</div></details>
- Keywords : `Supervised learning`, `Classification`, `Sampling efficiency`, `Sample prioritization`, `Reinforcement learning`

### RL-Selector: Reinforcement Learning-Guided Data Selection via Redundancy Assessment
[[Paper]](https://arxiv.org/pdf/2506.21037)
[[bibtex]](https://arxiv.org/abs/2506.21037)
<details><summary>summary</summary><div>

(PDF):Yang\_Reinforcement\_Learning-Guided\_Data\_Selection\_via\_Redundancy\_Assessment\_ICCV\_2025\_paper.pdf

概要:

[cite_start]大規模データセットを用いた深層学習は、高い計算コストとストレージオーバーヘッドを伴います [cite: 583][cite_start]。これらのデータセットにはしばしば実質的な冗長性が含まれており [cite: 584, 597][cite_start]、データ効率の良い学習手法が求められています。本研究は、データ選択を強化学習（RL）プロセスとして再定式化する新しい手法「RL-Selector」を提案します [cite: 588][cite_start]。RL-Selectorは、データセット内の冗長性を評価し、最も代表的なサンプルを特定することで、性能を損なうことなく学習コストを削減します [cite: 585]。

主な貢献:
	1.	**ε-sample cover概念の導入:**
	•	サンプル間の関係性に基づいて冗長性を定量化する「ε-sample cover」という新しい概念を導入しました 。
	•	理論的に、互いにε-coverされたサンプル（冗長なサンプル）を削除しても、モデルの汎化性能への影響が最小限であることを証明しました [cite: 610, 625, 768]。
	2.	**RLによる動的な選択ポリシー:**
	•	データ選択をRLプロセスとしてモデル化し、軽量なA2Cエージェントがε-sample coverを報酬シグナルとして選択ポリシーを最適化します [cite: 588, 612, 616]。
	•	これにより、従来の静的な評価指標では見落とされていた、学習のダイナミクス [cite: 603, 611]と選択されたサンプルの「グループ効果」 [cite: 601]を考慮することができます。
	3.	**高い汎化性能と効率の実証:**
	•	選択されたデータセットで学習したモデルは、学習効率が向上するだけでなく [cite: 590]、フルデータセットで学習したモデルよりも高い汎化性能を達成しました [cite: 590, 856]。

結論:

[cite_start]RL-Selectorは、CIFAR-100やImageNet-1kなどの主要なベンチマークにおいて、既存の最先端（SOTA）データ選択手法を一貫して上回る性能を示しました [cite: 589, 852, 855][cite_start]。さらに、ResNet-50で選択されたデータセットが、ViTやSwin-Transformerなどの異なるアーキテクチャに対しても高い汎化性能（クロスアーキテクチャ汎化）を示すことを実証しました [cite: 622, 894][cite_start]。また、ImageNet-A/R/Hardといったより困難なベンチマークにおいても、フルデータセットで学習したモデルを凌駕する堅牢性と汎化性能が確認されました [cite: 622, 899]。
</div></details>
- Keywords : `Data Selection`, `Reinforcement Learning`, `Redundancy Assessment`, `Data-Efficient Training`, `Deep Learning`

### RIME: Robust Preference-based Reinforcement Learning with Noisy Preferences
[[Paper]](https://arxiv.org/pdf/2402.17257)
[[bibtex]](https://arxiv.org/abs/2402.17257)
<details><summary>summary</summary><div>
	
概要: サンプル選択には強化学習は使っていない

[cite_start]好みベース強化学習（PbRL）は、人間の好みを報酬信号として利用することで、面倒な報酬関数の設計を不要にします [cite: 4][cite_start]。しかし、既存のPbRL手法はドメイン専門家からの高品質なフィードバックに過度に依存しており [cite: 5][cite_start]、ロバスト性（頑健性）に欠けています [cite: 5][cite_start]。人間のフィードバックにはノイズ（間違い）が含まれやすく [cite: 20][cite_start]、わずか10%のノイズでも性能が劇的に低下することが示されています [cite: 22][cite_start]。本研究は、ノイズの多い好みデータからでも効果的に報酬モデルを学習するためのロバストなPbRLアルゴリズム「RIME」を提案します [cite: 6][cite_start]。RIMEは、サンプル選択ベースの「ノイズ除去識別器」を用いてノイズを動的にフィルタリングし [cite: 7][cite_start]、さらに「報酬モデルのウォームスタート」によって間違った選択が引き起こす累積エラーに対処します [cite: 8]。

主な貢献:
	1.	**RIMEアルゴリズムの提案:**
	[cite_start]•	ノイズの多いフィードバックから報酬モデルを効果的に学習するために設計された、ロバストな報酬学習アルゴリズム「RIME」を提示しました [cite: 75]。
	2.	**ノイズ除去識別器 (Denoising Discriminator):**
	[cite_start]•	モデルの予測と注釈ラベル間のKLダイバージェンスに基づき、サンプルをフィルタリングする識別器を導入しました [cite: 32, 33, 70, 71]。
	[cite_start]•	この識別器は、動的な下限しきい値（$\tau_{lower}$）で信頼できるサンプルを選択し [cite: 70, 165][cite_start]、固定の上限しきい値（$\tau_{upper}$）で信頼性が極めて低いサンプルのラベルを反転させます [cite: 70, 167, 168]。
	3.	**報酬モデルのウォームスタート:**
	[cite_start]•	間違ったサンプル選択による累積エラーを軽減し [cite: 72][cite_start]、識別器の初期性能を向上させるため、報酬モデルを（ノイズのない）内在的報酬で事前学習（ウォームスタート）させる手法を提案しました [cite: 72, 180, 181]。
	[cite_start]•	このウォームスタートは、PbRLの「事前学習」から「オンライン学習」へ移行する際に発生する性能のギャップを埋める効果も持ちます [cite: 73, 76]。

結論:

[cite_start]RIMEは、Meta-World（ロボット操作）やDeepMind Control Suite（歩行）などの複雑なタスクにおいて [cite: 218][cite_start]、ノイズの多い好みデータが与えられた場合でも、既存の最先端PbRL手法（PEBBLEなど）の性能を大幅に上回りました [cite: 9, 74, 77, 246][cite_start]。さらに、専門家ではない実際の人間（エラー率約40%）からのフィードバックを用いた実験でも [cite: 486, 493][cite_start]、RIMEはベースラインを圧倒し [cite: 494][cite_start]、タスク（ホッパーの後方宙返り）の学習に成功しました [cite: 494][cite_start]。これにより、RIMEは専門家でないユーザーやクラウドソーシングからの好みデータを活用する道を開き [cite: 545][cite_start]、PbRLの適用可能性を広げることができます [cite: 545, 555]。
</div></details>
- Keywords : `Preference-based Reinforcement Learning (PbRL)`, `Learning from Noisy Labels`, `Robust Reward Learning`, `Sample Selection`, `Human-in-the-Loop`, `Denoising Discriminator`

### Policy Learning for Actively Labeled Sample Selection on Lumbar Semi-supervised Classification
[[Paper]](https://link.springer.com/content/pdf/10.1007/s10278-024-01167-x.pdf)
[[bibtex]](https://link.springer.com/article/10.1007/s10278-024-01167-x)
<details><summary>summary</summary><div>



概要:

[cite_start]医療データのラベル付けは、多大な労力、時間、医学的専門知識を必要とするため困難です [cite: 1519, 1587][cite_start]。この問題に対処するため、半教師あり学習（SSL）がラベルなしデータを活用するために用いられてきました [cite: 1520][cite_start]。しかし、SSLモデルの性能は、ラベル付きデータの質と量に大きく依存します [cite: 1520][cite_start]。本研究は、半教師あり学習と強化学習（RL）ベースのアクティブラーニング（AL）を統合した新しいアーキテクチャ「RL-based SSAL」を提案します [cite: 1522, 1576, 1588][cite_start]。このフレームワークは、SSLネットワークの学習とアクティブなサンプル選択を交互に実行します [cite: 1522, 1591][cite_start]。サンプル選択プロセスを「決定問題」として扱い、強化学習のポリシー学習アプローチを採用しています [cite: 1524, 1592]。

主な貢献:
	1.	**統一されたSSALアーキテクチャ:**
	[cite_start]•	半教師あり学習とアクティブラーニングを交互に訓練する、統一されたフレームワーク「RL-based SSAL」を提案しました [cite: 1522, 1591]。
	[cite_start]•	SSLモデルを事前学習させた後、そのモデルを使って情報価値の高いサンプルを選択し [cite: 1523][cite_start]、ラベル付けされたサンプルを教師ありデータセットに追加してSSLモデルをさらに訓練します [cite: 1523]。
	2.	**ポリシー学習によるサンプル選択:**
	[cite_start]•	従来の不確実性ベースのような手動設計された基準とは異なり [cite: 1565][cite_start]、サンプル選択を「ラベルを付けるか否か」の決定問題としてモデル化し [cite: 1524][cite_start]、強化学習エージェントが選択ポリシーを学習します [cite: 1566-1567, 1592]。
	3.	**新規の報酬関数:**
	[cite_start]•	ポリシー学習を導くために、予測「信頼度（confidence）」と「不確実性（uncertainty）」の積に基づく新しい報酬関数を設計しました [cite: 1525, 1593]。
	[cite_start]•	この報酬関数は、「高い信頼度」と「高い不確実性」を同時に示すサンプルを選択することを目的としています [cite: 1525, 1580, 1593][cite_start]。このようなサンプルは、モデルが識別困難でありながら価値が高いとみなされます [cite: 1580-1582, 1593]。

結論:

[cite_start]提案手法（RL-based SSAL）は、収集された腰椎椎間板ヘルニア（LDH）データセットにおいて、ベースラインのSSL（FixMatch）や他のAL手法と比較して一貫して優れた性能を示しました [cite: 1526-1527, 1594][cite_start]。異なるラベル数の設定（例：40, 200, 800）で、ベースラインを3%以上上回る精度を達成しました [cite: 1526, 1802-1804][cite_start]。特筆すべきことに、わずか200枚のラベル付きデータで学習したモデルが、全ラベル付きデータセット（10,000枚以上）で学習したモデルに匹敵する精度（89.32%）を達成し [cite: 1528, 1595][cite_start]、医療画像の注釈コストを大幅に削減できる可能性を示しました [cite: 1595, 1913]。
</div></details>
- Keywords : `Semi-supervised learning`, `Active learning`, `Policy learning`, `Reward function`, `Reinforcement Learning`, `Medical Image Classification`
