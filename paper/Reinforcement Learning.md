

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


### Constraint-Conditioned Policy Optimization for Versatile Safe Reinforcement Learning
[[Paper]](https://proceedings.neurips.cc/paper_files/paper/2023/file/29906cbd165b78991da2c4dbabc2a04b-Paper-Conference.pdf)
[[bibtex]](https://proceedings.neurips.cc/paper_files/paper/2023/hash/29906cbd165b78991da2c4dbabc2a04b-Abstract-Conference.html)
<details><summary>summary</summary><div>

概要:

安全強化学習（Safe RL）は、事前に定義された安全制約（コスト閾値）を守りながら報酬を最大化するエージェントを訓練します。しかし、訓練時とは異なる様々な安全制約に適応できる「多様な（versatile）」安全方策を、再訓練なしで学習することは未だ困難な課題です。本研究は、この「多様な安全RL問題」を定式化し、訓練効率とゼロショット適応能力の要求に応えるため、新しいフレームワーク「Constraint-Conditioned Policy Optimization (CCPO)」を提案します。CCPOは、(1) 未知の閾値条件下の価値関数を近似する「Versatile Value Estimation (VVE)」と、(2) 任意の制約閾値を方策最適化に組み込む「Conditioned Variational Inference (CVI)」の2つのモジュールで構成されます。

主な貢献:
1.  **多様な安全RL問題の定式化:**
    • 従来の固定された単一の制約閾値を超える問題として「多様な学習問題（versatile learning problem）」を定義しました。
    [cite_start]• この課題に対し、再訓練なしで未知の多様な制約閾値にゼロショットで汎化できるCCPOを提案しました [cite: 33-34]。
2.  **VVEとCVIによるゼロショット適応:**
    [cite_start]• 価値関数を観測特徴と閾値特徴に線形分解する「VVE」を導入し、未知の閾値に対する価値推定を可能にしました [cite: 97-98, 112]。
    • 「CVI」により、任意の安全制約 $\epsilon$ を条件として最適なの行動分布を計算（Eステップ）し、それを教師データとして多様な方策 $\pi(a|s, \epsilon)$ を学習（Mステップ）する枠組みを構築しました。
3.  **理論的・実験的有効性の実証:**
    [cite_start]• 未知の閾値に対するコスト違反の理論的なバウンド（限界値）を示しました [cite: 37, 184-185]。
    • 広範な実験により、CCPOがベースライン手法と比較して、安全性とタスク性能の両方で優れており、特に高次元のタスクでその差が顕著であることを示しました。

結論:

[cite_start]本研究は、多様な安全RLという概念を提唱し、CCPOアルゴリズムを提案しました。CCPOは、VVEとCVIという核心的要素により、訓練時に経験しなかったコスト閾値に対しても効率的に適応し、ゼロショット汎化を可能にします [cite: 413-414]。実験結果は、CCPOがベースライン手法よりも安全であり、かつデータ効率（$\epsilon$-sampling efficiency）が大幅に高いことを裏付けています。
</div></details>
- Keywords : `Safe Reinforcement Learning`, `Versatile Safe Reinforcement Learning`, `Zero-shot adaptation`, `Policy Optimization`, `Constrained Markov Decision Process`, `Variational Inference`
