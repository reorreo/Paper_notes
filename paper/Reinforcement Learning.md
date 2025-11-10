

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


### Near-Optimal Distributionally Robust Reinforcement Learning with General $L_{p}$ Norms
[[Paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/0346c8a510dd15971566a97a241c5e6a-Paper-Conference.pdf)
[[bibtex]](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0346c8a510dd15971566a97a241c5e6a-Abstract-Conference.html)
<details><summary>summary</summary><div>

概要:

シミュレーションと実世界のギャップ（sim-to-real gap）に対処するため、分布ロバスト強化学習（RMDPs）は、環境が名目上のモデルから一定の不確実性セット内にある場合に、最悪ケースの性能を最適化します。しかし、RMDPsのサンプル複雑性（学習に必要なデータ量）は、特に一般的な$L_p$ノルムを不確実性セットの距離関数として用いる場合、これまで大きく未解明でした。本研究は、名目MDPからのサンプリングが可能な生成的モデルを仮定し、sa-rectangularおよびs-rectangularという2つの一般的な条件下で、一般化された$L_p$ノルムを用いたRMDPsのサンプル複雑性を分析します。本研究の結果は、RMDPsが標準的なMDPsよりもサンプル効率が高くなり得ることを示唆しています。

主な貢献:

* **sa-rectangular RMDPsのサンプル複雑性:**
    • 一般的な$L_p$ノルムを用いたsa-rectangular RMDPsのサンプル複雑性について、ほぼ最適 (near-optimal) な上限 $\tilde{O}(\frac{SA}{(1-\gamma)^{2}max\{1-\gamma,C_{g}\sigma\}\epsilon^{2}})$ を導出しました。
    • この上限のタイトさを確認するため、一致するミニマックス下限 (minimax lower bound) も導出しました。
* **s-rectangular RMDPsのサンプル複雑性:**
    [cite_start]• s-rectangular RMDPsに対しても、既存研究のサンプル複雑性を改善する上限を導出しました [cite: 65-67]。
    • さらに、$L_{\infty}$ノルムを用いた代表的なケースにおいて、s-rectangular RMDPsに対する**初の下限**を導出し、上限のタイトさを検証しました。
* **RMDPs vs 標準MDPsの比較:**
    • 本研究の結果は、RMDPsが標準的なRL（サンプル複雑性 $\tilde{O}(\frac{SA}{(1-\gamma)^{3}\epsilon^{2}})$）と比較して、サンプル効率が**同等か、あるいは優れている**（必要なサンプル数が少ない）ことを示しました。
    • 特に、不確実性のレベル $\sigma$ が比較的大きい場合 ($\sigma \ge 1-\gamma$)、RMDPsのサンプル複雑性は標準RLよりも小さくなります。
* **s- vs sa-rectangularの比較:**
    • s-rectangular RMDPsは、sa-rectangular RMDPsよりも複雑な定式化であるにもかかわらず、サンプル要求量の観点からは、解くのが**難しくない**ことを示しました。

結論:

本研究は、生成的モデルの仮定のもと、一般化された$L_p$ノルムによって特徴づけられる不確実性セットを持つRMDPsのサンプル複雑性バウンドを明らかにしました。s-rectangular RMDPsの学習は、sa-rectangular RMDPsと比較してサンプル複雑性の観点で難しくないことを示し、s-rectangularケースに関して初めてミニマックスバウンドを提供しました。さらに、RMDPsのミニマックスサンプル複雑性は、標準的なMDPsの学習に必要なサンプル複雑性よりも**決して大きくならない**ことを実証しました。
</div></details>
- Keywords : `Distributionally Robust Reinforcement Learning`, `RMDPs`, `Sample Complexity`, `$L_p$ Norms`, `Minimax Optimal`, `sa-rectangular`, `s-rectangular`

### Frustratingly Easy Regularization on Representation Can Boost Deep Reinforcement Learning
[[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/He_Frustratingly_Easy_Regularization_on_Representation_Can_Boost_Deep_Reinforcement_Learning_CVPR_2023_paper.pdf)
[[bibtex]](https://openaccess.thecvf.com/content/CVPR2023/html/He_Frustratingly_Easy_Regularization_on_Representation_Can_Boost_Deep_Reinforcement_Learning_CVPR_2023_paper.html)
<details><summary>summary</summary><div>


概要:

[cite_start]ディープラーニング（DRL）は高次元情報から良い方策を学習しますが、その中核には関連情報を保持し不要な情報を捨てる「表現学習」があります [cite: 2367, 2380][cite_start]。DRLの学習安定化に不可欠なQ-networkとその「ターゲットQ-network」 [cite: 2385-2386] [cite_start]について、両者の表現が持つべき特性はこれまで見過ごされてきました [cite: 2388][cite_start]。本研究は、Q-networkとそのターゲットの表現が、理論的に「識別可能な表現特性（distinguishable representation property）」を満たすべきであることを初めて示しました [cite: 2368, 2392][cite_start]。これは、2つの表現の類似性（内積）に特定の上限が存在することを意味します [cite: 2369, 2486][cite_start]。しかし、実験により、既存のDRLエージェント（特にCURLなど）がこの特性に違反し、準最適な方策に陥る可能性があることを明らかにしました [cite: 2370, 2398, 2500-2501][cite_start]。この問題を解決するため、本研究は**PEER (Policy Evaluation with Easy Regularization on Representation)** という、わずか1行のコードで実装可能な、シンプルかつ効果的な正則化項を提案します [cite: 2371-2372, 2399-2400]。PEERは、この「識別可能な表現特性」を明示的に維持するように働きます。

主な貢献:
1.  **「識別可能な表現特性」の理論的導出:**
    * [cite_start]Q-networkの表現 $\Phi(s,a;\Theta_{+})$ とそのターゲットの表現 $\mathbb{E}_{s^{\prime},a^{\prime}}\Phi(s^{\prime},a^{\prime};\Theta_{+}^{\prime})$ の類似性（内積）には、報酬 $r(s,a)$ などに依存する明確な**上限**が存在することを理論的に証明しました（Theorem 3.2） [cite: 2368-2369, 2485-2486]。
    * [cite_start]これは、最適な方策選択のために、隣接タイムステップ間の表現が十分に「識別可能」であるべきことを示唆します [cite: 2491]。
2.  **既存手法における特性違反の発見:**
    * [cite_start]実験を通じて、TD3のようなアルゴリズムはこの特性を維持する傾向がある一方で、CURLのような明示的な表現学習手法がこの特性に違反しうることを示しました [cite: 2397-2398, 2499-2500] (Fig. 1)[cite_start]。この違反が性能低下の一因である可能性を指摘しました [cite: 2370, 2501]。
3.  **PEER正則化項の提案:**
    * [cite_start]上記特性を維持するため、Q-networkとターゲットネットワークの表現の**内積を直接正則化する**（類似度を下げる）PEERロス $L_{PEER}$ を提案しました [cite: 2371, 2401, 2506] (Fig. 2)。
    * [cite_start]PEERは既存の方策評価ロス $\mathcal{L}_{PE}$ に加算するだけでよく（ $\mathcal{L}(\Theta)=\mathcal{L}_{PE}(\Theta)+\beta\mathcal{L}_{PEER}(\Theta)$ ）、実装が極めて容易です [cite: 2372, 2528]。
    * [cite_start]PEERを用いた場合の収束率の保証も理論的に提供しました [cite: 2372, 2414, 2542-2553]。
4.  **広範な実験による有効性の実証:**
    * [cite_start]PEERをTD3、CURL、DrQといった代表的なDRLアルゴリズムに適用し、性能とサンプル効率が大幅に向上することを示しました [cite: 2373, 2403, 2407]。
    * [cite_start]PyBullet (4/4環境)、DMControl (12タスク中9タスク)、Atari (26ゲーム中19ゲーム) という複数のベンチマークで最先端（SOTA）の性能を達成しました [cite: 2374, 2406]。

結論:

[cite_start]本研究は、DRLにおけるQ-networkとターゲットネットワークの表現間に存在する本質的な「識別可能な表現特性」を初めて理論的に導出しました [cite: 2375, 2722, 2731][cite_start]。既存エージェントがこの特性を違反しがちであることを示し [cite: 2723][cite_start]、この特性を維持するためのシンプルな正則化項PEERを提案しました [cite: 2724][cite_start]。広範な実験の結果、PEERはTD3、CURL、DrQなどのベースアルゴリズムの性能とサンプル効率を大幅に改善すること、また既存の表現学習手法（CURL, DrQ）と直交的（互換性がある）であることが示されました [cite: 2695-2696, 2719, 2725]。
</div></details>
- Keywords : `Deep Reinforcement Learning`, `Representation Learning`, `Regularization`, `Q-Learning`, `Target Network`, `Policy Evaluation`

### Regularized Parameter Uncertainty for Improving Generalization in Reinforcement Learning
[[Paper]](https://openaccess.thecvf.com/content/CVPR2024/papers/Moure_Regularized_Parameter_Uncertainty_for_Improving_Generalization_in_Reinforcement_Learning_CVPR_2024_paper.pdf)
[[bibtex]](https://openaccess.thecvf.com/content/CVPR2024/html/Moure_Regularized_Parameter_Uncertainty_for_Improving_Generalization_in_Reinforcement_Learning_CVPR_2024_paper.html)
<details><summary>summary</summary><div>

概要:

[cite_start]強化学習（RL）エージェントが実世界でタスクを実行するには、訓練環境とは異なる「未知の」環境へ汎化する能力が不可欠です。しかし、RLエージェントは訓練環境に過剰適合（over-fitting）しやすく、分布外（out-of-distribution）の汎化性能が低いという課題があります [cite: 2892-2893][cite_start]。教師あり学習の正則化手法（ノイズ注入やパラメータ正則化など）を単純に適用しようとしても、RL特有の性質（例：学習の不安定化、モデルの表現力不足）により限定的な効果しかありませんでした [cite: 2894, 2906, 2909][cite_start]。パラメータの不確実性（ネットワークの重みを固定値ではなく確率分布として扱う）は、この問題の有望な解決策ですが [cite: 2910][cite_start]、従来のKLダイバージェンスによる正則化はRLのノイズが多い学習設定では適用が難しく、汎化目的での利用は進んでいませんでした [cite: 2911-2912, 2981]。本研究は、この問題を解決するため、**SNR PUN (Signal-to-Noise Ratio regulated Parameter Uncertainty Network)** という新しい正則化手法を提案します。

主な貢献:
1.  **SNR（信号対雑音比）による新しい正則化手法の提案:**
    * [cite_start]パラメータの不確実性を測る新しい尺度として、各パラメータ分布の平均と標準偏差の比率である「SNR（信号対雑音比）」を導入しました [cite: 2916]。
    * [cite_start]従来のKLダイバージェンス（特定の事前分布に近づける）の代わりに、各パラメータのSNRが最大閾値 $\Omega_{Max~SNR}$ を超えないように制約する「Max SNR正則化」（$\mathcal{L}^{SNR}$）を提案しました [cite: 2917, 2992-2993]。
2.  **SNR正則化の理論的分析:**
    * [cite_start]提案するSNR正則化は、従来のKLダイバージェンスを、より広範な事前分布の集合に対して計算することと等価であることを示しました [cite: 2921-2922, 2999-3000]。
    * [cite_start]これにより、SNR正則化はKLダイバージェンスよりも柔軟な制約を課すことができ、RLにおける汎化性能の向上に適していることを示しました [cite: 3013-3015] (Fig. 1)。
3.  **SNR PUNのためのRL学習スキーム:**
    * 提案手法をPPO（Proximal Policy Optimization）に統合しました。
    * [cite_start]汎化性能を高めるため、アクター（方策）とクリティック（価値）を分離し、アクターのみを確率的（SNR PUN）にし、クリティックは決定論的なネットワークとすることで学習を安定させました [cite: 2923-2924, 3038-3039]。
    * [cite_start]さらに、パラメータのサンプリング戦略の変更や、不確実性を最大化する新しい初期化手法を導入しました [cite: 2924, 3030, 3041-3042]。
4.  **実機転移を含む実験的検証:**
    * [cite_start]シミュレーション（Cartpole, Acrobotなど）において、未知の環境パラメータ（例：ポールの長さ、質量）に対する汎化性能で、SNR PUNが既存の正則化手法（Dropout, Weight Decay, VIBなど）を大幅に上回ることを示しました [cite: 2897, 3154] (Table 1)。
    * [cite_start]物理的なCartpole実機への転移実験（sim-to-real）を行い、シミュレーションで汎化性能の高かったSNR PUNのみが実機でのタスク（振り上げ）に成功することを示しました [cite: 2898, 3313-3314] (Fig. 6)。

結論:

[cite_start]本研究は、RLの汎化性能を向上させるため、パラメータの不確実性を「SNR（信号対雑音比）」で正則化する新しい手法「SNR PUN」を提案しました。SNR PUNは、従来のKLダイバージェンスによる正則化の課題を克服し、シミュレーションと実世界の両方で高い汎化性能を示しました。特に、より複雑な環境では適切なSNRのバランスを見つけることが重要であり、本手法はそのトレードオフを制御する有効な手段となります [cite: 3304, 3322-3323]。
</div></details>
- Keywords : `Generalization in Reinforcement Learning`, `Regularization`, `Parameter Uncertainty`, `Signal-to-Noise Ratio (SNR)`, `PPO`, `Sim-to-Real`

### Zero-Shot Reinforcement Learning via Function Encoders
[[Paper]](https://raw.githubusercontent.com/mlresearch/v235/main/assets/ingebrand24a/ingebrand24a.pdf)
[[bibtex]](https://proceedings.mlr.press/v235/ingebrand24a.html)
<details><summary>summary</summary><div>

概要:

[cite_start]強化学習（RL）は多くの困難な逐次的意思決定問題を解決できますが、関連するタスク間での「ゼロショット転移」（追加学習なしでの適応）は依然として課題です [cite: 4][cite_start]。この困難さは、現在のタスクが過去に経験したタスクとどう関連しているかをエージェントが理解するための、良い「タスク表現」を見つける点にあります [cite: 5][cite_start]。本研究は、ゼロショット転移を達成するために「関数エンコーダ（Function Encoder）」という新しい表現学習アルゴリズムを提案します [cite: 6][cite_start]。関数エンコーダは、ある関数（例：報酬関数 $R$ や遷移関数 $T$）を、学習された非線形の「基底関数」の重み付き線形結合として表現します [cite: 6-7][cite_start]。この重み（係数）ベクトルは、現在のタスクが過去のタスクとどう関連しているかを示す一貫した表現となり、エージェントはこれ（$c_f$）を方策 $\pi(s, c_f)$ や価値関数 $Q(s, a, c_f)$ の追加入力として受け取ります [cite: 7, 189][cite_start]。これにより、エージェントは実行時に追加の訓練なしで関連タスクに適応（ゼロショット転移）できます [cite: 8]。

主な貢献:
* **関数エンコーダ (FE) の提案:**
    * [cite_start]ある関数 $f$ を、学習された非線形基底関数 $\{\hat{g}_k\}$ の線形結合 $f(x) = \sum c_k g_k(x)$ として表現する、新しい汎用的な表現学習アルゴリズムを提案しました [cite: 6, 47, 163]。
* **効率的な表現の計算:**
    * [cite_start]個別のタスク関数 $f$ の表現 $c_f$（係数ベクトル）は、その関数からのサンプルデータ $\{(x_i, f(x_i))\}$ を用いたモンテカルロ積分（実質的な内積計算）によって効率的に計算されます [cite: 140-141, 148, 161]。
* **汎化性能の理論的保証:**
    * [cite_start]関数 $f$ からその表現 $c_f$ へのマッピングは「線形作用素」であること（Theorem 1）を証明しました [cite: 171, 176]。
    * [cite_start]これにより、訓練で使われた関数の線形結合で表される「未知の」関数に対しても、FEが正確な表現を生成できることが保証され、高い汎化性能を持ちます [cite: 179-180]。
* **RLへのシームレスな統合:**
    * [cite_start]FEで得られたタスク表現 $c_f$ を、あらゆる標準的なRLアルゴリズムの方策や価値関数に追加の入力として渡すだけで、ゼロショットRLを実現できることを示しました [cite: 46, 62, 189-190]。
* **SOTA性能の実証:**
    * [cite_start]隠れパラメータを持つシステム同定（教師あり学習）、マルチエージェントRL、マルチタスクRLという3つの異なる分野において、FEを既存のRLアルゴリズムに組み込むだけで、データ効率、漸近性能、学習安定性の全てでSOTAを達成することを示しました [cite: 9, 52-55]。

結論:

[cite_start]本研究は、関数を学習された非線形基底関数の線形結合として符号化する、汎用的な表現学習アルゴリズム「関数エンコーダ」を導入しました [cite: 478][cite_start]。このエンコーダは線形作用素であるため、学習した表現は一般化可能であり、未知のタスクに対しても予測可能な表現を生成します [cite: 479][cite_start]。この関数エンコーダをタスク表現の生成に用いることで、基本的なRLアルゴリズムが、タスク（報酬関数や遷移関数）の表現ベクトルを追加の入力として受け取るだけで、関連タスク間でのゼロショット転移を達成できることを示しました [cite: 480-481][cite_start]。この手法は、基本的なRLアルゴリズムの単純さを保ちつつ、安定性、データ効率、および高い漸近性能を実現します [cite: 482]。
</div></details>
- Keywords : `Zero-Shot Reinforcement Learning`, `Representation Learning`, `Function Encoder`, `Multi-Task RL`, `System Identification`, `Basis Functions`

### RLSAC: Reinforcement Learning enhanced Sample Consensus for End-to-End Robust Estimation
[[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Nie_RLSAC_Reinforcement_Learning_Enhanced_Sample_Consensus_for_End-to-End_Robust_Estimation_ICCV_2023_paper.pdf)
[[bibtex]](https://openaccess.thecvf.com/content/ICCV2023/html/Nie_RLSAC_Reinforcement_Learning_Enhanced_Sample_Consensus_for_End-to-End_Robust_Estimation_ICCV_2023_paper.html)
<details><summary>summary</summary><div>

概要:

[cite_start]ロバスト推定（ノイズの多いデータからモデルパラメータを推定するタスク）は、コンピュータビジョンにおいて非常に重要ですが、依然として困難な課題です [cite: 13, 25][cite_start]。RANSAC [cite: 50] [cite_start]に代表される従来のサンプリングコンセンサス（標本合意）に基づくアルゴリズムは、ランダムサンプリングを繰り返すことでロバスト性を担保しますが、データの特徴や履歴情報を効果的に利用できず、非微分可能であるため学習ベースのパイプラインに組み込めないという問題がありました [cite: 14, 55-57][cite_start]。本研究は、このサンプリングコンセンサスのプロセスを強化学習（RL）の問題として再定式化する、**RLSAC (Reinforcement Learning enhanced SAmple Consensus)** という新しいエンドツーエンドのロバスト推定フレームワークを提案します [cite: 15, 61-62]。

主な貢献:
* **RLによるサンプリングコンセンサスの再定式化:**
    * [cite_start]サンプリングコンセンサスのプロセスを、RLのエージェントと環境の相互作用としてモデル化しました [cite: 62]。
    * [cite_start]エージェント（ニューラルネットワーク）がデータから「最小セット」をサンプリングすることを「行動（Action）」と見なします [cite: 63]。
    * [cite_start]環境がその最小セットから仮説（Hypothesis）を生成し、その品質（例：インライア率）を「報酬（Reward）」としてエージェントにフィードバックします [cite: 64, 70]。
* **グラフニューラルネットワークによるエージェント:**
    * [cite_start]エージェントの方策ネットワーク（Policy Network）として、グラフニューラルネットワーク（GNN）を採用しました [cite: 16]。
    * [cite_start]これにより、データの特徴（例：対応点の記述子）間の相互関係を考慮し、次にサンプリングすべき「最小セット」を賢く選択（探索）できます [cite: 203-205]。
* **微分不要なエンドツーエンド学習:**
    * [cite_start]仮説の品質（インライア率など）を報酬として利用するため、サンプリングプロセス自体が微分不可能であっても、RL（SAC-Discrete [cite: 266][cite_start]）を用いて方策ネットワークを教師なしで訓練できます [cite: 17, 70]。
    * [cite_start]これにより、下流タスク（例：ロバスト推定）のフィードバックに基づいたエンドツーエンドの学習が可能になります [cite: 18, 71, 242]。
* **状態（State）エンコーディング:**
    * [cite_start]RLの状態（State）として、元のデータ特徴量に加え、「メモリ特徴量」を導入しました [cite: 19, 67]。
    * [cite_start]メモリ特徴量には、現在のアクション（どのデータが選ばれたか）、仮説に対するデータの残差、および過去のサンプリング履歴（データが何回選ばれたか）が含まれます [cite: 67, 245, 254]。
    * [cite_start]これにより、エージェントは過去のアクションの品質を評価し、より良い仮説を徐々に探索できます [cite: 69, 317]。

結論:

[cite_start]本研究は、サンプリングコンセンサスを強化学習で強化する新しいフレームワークRLSACを提案しました。RLSACは、GNNを用いてデータ特徴とメモリ特徴を活用し、より良い仮説を徐々に探索します [cite: 20][cite_start]。報酬ベースの教師なし学習により、微分不可能なプロセスを含むエンドツーエンドのロバスト推定を実現しました [cite: 86][cite_start]。2Dラインフィッティングや基本行列推定といったタスクにおいて、RLSACは高いロバスト性とSOTAの性能を達成しました [cite: 87-88][cite_start]。本フレームワークは特定のタスクに限定されず、他のサンプリングコンセンサスベースのロバスト推定問題にも容易に応用可能です [cite: 21, 89]。
</div></details>
- Keywords : `Robust Estimation`, `RANSAC`, `Sample Consensus`, `Reinforcement Learning`, `End-to-End Learning`, `Graph Neural Network`

[[Paper]]()
[[bibtex]]()
