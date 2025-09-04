<html lang="ja">
    <head>
        <meta charset="utf-8" />
    </head>
    <body>
<h1><center>Seminal Papers</center></h1>
<h2>なにものか？</h2>
<p>
DNN 関連の研究で源流になるような論文を集めようと思う。<br>
※「seminal」は「影響力のある」「種をまくような」という意味で、<br>
　後続の研究に大きな影響を与えた論文を指します。(by Copilot)<br>
<br>
・現象を初めて発見した, 初めて報告した。<br>
・現象に命名して統一的に研究できるようにした<br>
　など
</p>
<p>
源流が判れば, 引用論文を辿って, その後の進展を調べることができる。<br>
アルファベット順
</p>

<h3>● 3D  Gaussian Splatting (3DGS)</h3>
<p>
『3D Gaussian Splatting for Real-Time Radiance Field Rendering』(2023)<br>
　論文は<a href="https://arxiv.org/abs/2308.04079">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2308.04079v1">こちら</a>
</p>
<p>
3D Gaussian Splatting (GS) 技術を導入した画期的な論文
</p>

<h3>● Bening Overfitting (良性過学習)</h3>
<p>
『Benign overfitting in linear regression』(2019)<br>
　論文は<a href="https://arxiv.org/abs/1906.11300">こちら</a><br>
　要約は無かった･･･ 引用論文の要約は<a href="https://www.alphaxiv.org/ja/overview/2202.06526v3">こちら</a>
</p>
<p>
線形回帰の文脈における「良性過学習」の概念を正式に導入し、分析した基礎的な論文
</p>

<h3>● Catastrophic Forgetting (破局的忘却)</h3>
　(問題の形式化)
<p>
『Catastrophic interference in connectionist networks: The sequential learning problem.』(1989)<br>
　論文は<a href="https://www.andywills.info/hbab/mccloskeycohen.pdf">こちら</a>
</p>
<p>
ニューラルネットワークが新しい情報を順次学習する際に生じる破局的干渉 (あるいは忘却) の問題を形式的に定義した基礎的な論文<br>
<br>
『Catastrophic forgetting in connectionist networks』(1999)<br>
　論文は<a href="https://lead.ube.fr/wp-content/uploads/2023/09/000282-catastrophic-forgetting-in-connectionist-networks.pdf">こちら</a><br>
<br>
壊滅的な忘却/干渉に関する非常に影響力のある論文。以前に習得した知識を上書きする現象を概説している。<br>
<br>
AIモデルを継続学習する場合, 課題になる。
</p>
　(解決手法)
<p>
『Overcoming catastrophic forgetting in neural networks』(2017)<br>
　論文は<a href="https://arxiv.org/abs/1612.00796">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1612.00796v2">こちら</a>
</p>
<p>
継続学習における正則化ベースの基盤的アプローチであるElastic Weight Consolidation (EWC) を導入した論文
</p>

<h3>● Cognitive Agent (認知エージェント)</h3>
<p>
『Computational mechanics: Pattern and prediction, structure and simplicity』(1999)<br>
　論文は<a href="https://arxiv.org/abs/cond-mat/9907176">こちら</a>, 要約はなし。引用論文の要約は<a href="https://www.alphaxiv.org/ja/overview/2505.19275v1">こちら</a><br>
<br>
「認知エージェント」概念の基礎となる計算力学とε-マシンが導入される。
</p>

<h3>● CoT: Chain-of-Thought (思考連鎖)</h3>
<p>
『Chain-of-thought prompting elicits reasoning in large language models』(2022)<br>
　論文は<a href="https://arxiv.org/abs/2201.11903">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2201.11903v6">こちら</a>
</p>
<p>
Chain-of-Thought (CoT) プロンプティングを導入し、普及させた画期的な論文
</p>

<h3>● Deep Reinforment Learning (深層強化学習)</h3>
<p>
『Human-level control through deep reinforcement learning』(2015)<br>
　論文は<a href="https://training.incf.org/sites/default/files/2023-05/Human-level%20control%20through%20deep%20reinforcement%20learning.pdf">こちら</a>
</p>
<p>
Deep Q-Networks（DQN）と深層RLにおける経験リプレイの顕著な使用法を導入した。
</P>

<h3>● Diffusion Model (拡散モデル)</h3>
<p>
『Denoising diffusion probabilistic models』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2006.11239">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2006.11239v2">こちら</a>
</p>
<p>
Denoising Diffusion Probabilistic Model (DDPM) を紹介している
</p>

<h3>● Double Descent (二重降下)</h3>
<p>
『Reconciling modern machine learning practice and the bias-variance trade-off』 (2018)<br>
　論文は<a href="https://arxiv.org/abs/1812.11118">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/1812.11118v2">こちら</a>
</p>
<p>
古典的なバイアス-バリアンスのトレードオフと、より大きなモデルが深層学習でより良く機能するという観察を調和させるために、「二重降下」の概念を紹介している。さまざまな設定で二重降下の経験的証拠を提供する。
</p>

<h3>● Dropout</h3>
<p>
『Improving neural networks by preventing co-adaptation of feature detectors.』(2012)<br>
　論文は<a href="https://arxiv.org/abs/1207.0580">こちら</a><br>
<br>
　ドロップアウト技術を導入した先駆的な論文
</p>
<p>
『Dropout: a simple way to prevent neural networks from overfitting』(2014)<br>
　論文は<a href="https://www.jmlr.org/papers/volume15/srivastava14a/srivastava14a.pdf">こちら</a><br>
<br>
　過学習を防ぐための正則化手法としてのドロップアウトについて包括的な分析を提供
</p>

<h3>● Episodic Memory (エピソード記憶)</h3>
<p>
『Episodic and semantic memory』(1972)<br>
　本の一部は<a href="https://alicekim.ca/EMSM72.pdf">こちら</a>, 引用論文の要約は<a href="https://www.alphaxiv.org/ja/overview/2505.03434v1">こちら</a><br>
<br>
認知科学におけるエピソード記憶と意味記憶の重要な区別を提示している。
</p>

<h3>● Generative Model (生成モデル)</h3>
<p>
『Generative Adversarial Networks』(2014)<br>
　論文は<a href="https://arxiv.org/abs/1406.2661">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1406.2661v1">こちら</a><br>
<br>
　敵対的生成ネットワーク（GAN）アーキテクチャを導入した基礎的な論文
</p>

<h3>● Grokking</h3>
<p>
『Grokking: Generalization beyond overfitting on small algorithmic datasets』(2022)<br>
　論文は<a href="https://arxiv.org/abs/2201.02177">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/2201.02177v1">こちら</a>, 機械翻訳は<a href="https://boyoyon.github.io/HTMLs_translated_to_Japanese/2022_GROKKING%20-%20GENERALIZATION%20BEYOND%20OVERFITTING%20ON%20SMALL%20ALGORITHMIC%20DATASETS/GROKKING%20-%20GENERALIZATION%20BEYOND%20OVERFITTING%20ON%20SMALL%20ALGORITHMIC%20DATASETS.html">こちら</a>
</p>
<p>
最初に「グロッキング」現象を発見し、命名し、調査した論文
</p>

<h3>● Hallucination (幻覚)</h3>
<p>
『Hallucinations in Neural Machine Translation』(2019)<br>
　論文は<a href="https://openreview.net/forum?id=SkxJ-309FQ">こちら</a><br>
<br>
ニューラル機械翻訳（NMT）におけるハルシネーション問題に特化して焦点を当てた先駆的な研究
</p>
<p>
『On Faithfulness and Factuality in Abstractive Summarization』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2005.00661">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2005.00661v1">こちら</a><br>
<br>
内在的ハルシネーションと外在的ハルシネーションという決定的な区別を導入し、抽象的要約の文脈においてハルシネーションの基礎的な定義（情報源への不忠実性）を提示した。
</p>

<h3>● IRL: Inverse Reinforcement Learning (逆強化学習)</h3>
<p>
エキスパートの行動を観察し, エキスパートは何をどう行動するかを学習する。<br>
『 Generative adversarial imitation learning.』(2016)<br>
　論文は<a href="https://arxiv.org/abs/1606.03476">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1606.03476v1">こちら</a><br>
<br>
　Generative Adversarial Imitation Learning (GAIL) フレームワークを導入し、GANとIRLの関連性を確立した基礎的な論文
</p>

<h3>● Knowledge Distillation (知識蒸留)</h3>
<p>
『Distilling the knowledge in a neural network』(2015)<br>
　論文は<a href="https://arxiv.org/abs/1503.02531">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1503.02531v1">こちら</a>
</p>
<p>
より小さな「生徒」ネットワークがより大きな「教師」ネットワークから学習するという、知識蒸留（KD）の概念を導入した基礎となる論文。<br>
蒸留のインスピレーションはお酒かと思ったら昆虫で, 「教師」が「幼虫」. 「生徒」が「成虫」というのも意外･･･<br>
人が与えるワンホットの正解では「生徒」モデルは学習困難。<br>
「教師」モデルの出力(Dark Knowlege)があると,「おしい」とか「全然違う」とか<br>
ヒントが貰えるので「生徒」モデルでも学習がはかどる･･･という感じ
</p>

<h3>● Linear mode connectivity (線形モード接続性)</h3>
<p>
『Linear mode connectivity and the lottery ticket hypothesis』(2019)<br>
　論文は<a href="https://arxiv.org/abs/1912.05671">こちら</a><br>
<br>
同じ初期化から訓練されたモデルが損失ランドスケープ内で連結され得ることを示唆
</p>

<h3>●LLM Alignment, RLHF, SFT, RM, PPO</h3>
<p>
大規模言語モデル(LLM)の出力を人間の価値観・倫理観・意図に沿うように調整すること。<br>
『Training language models to follow instructions with human feedback,』(2022)<br>
　論文は<a href="https://arxiv.org/abs/2203.02155">こちら</a>, サーベイ論文の要約は<a href="https://www.alphaxiv.org/ja/overview/2407.16216v1">こちら</a><br>
<br>
LLMをアライメントするための影響力のある3段階RLHFフレームワーク（SFT、RM、PPO）を確立した<br>
・RLHF: Reinforcement Learning from Human Feedback<br>
・SFT: Supervised Fine-Tuning<br>
・RM: Reward Model<br>
・PRO: Proximal Policy Optimization<br>
</p>

<h3>●LoRA: Low-rank adaptation of LLM (低ランク適応)</h3>
<p>
『Lora: Low-rank adaptation of large language models』(2021)<br>
　論文は<a href="https://arxiv.org/abs/2106.09685">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2106.09685v2">こちら</a><br>
<br>
低ランク適応 (LoRA) を導入した基礎的な論文。<br>
大規模言語モデルを下流タスクに適応させるための効率の良いファインチューニング手法。<br>
すべてのモデルパラメータを更新するのではなく、重みを近似する低ランク分解行列を学習することで、学習可能なパラメータ数を劇的に削減しつつ、競争力のあるパフォーマンスを維持する。
</p>

<h3>● Loss of Plasticity (可塑性喪失) </h3>
<p>
『Loss of Plasticity in Continual Deep Reinforcement Learning』(2023)<br>
　論文は<a href="https://arxiv.org/abs/2303.07507">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2303.07507v1">こちら</a>
</p>
<p>
非定常環境で動作する深層強化学習エージェントにおいて「可塑性の喪失」を特定し、エージェントが新しい情報を学習する能力を徐々に失うことを示した。この現象は、ニューロンが不活性になる「活性化崩壊」が主な原因であり、標準のReLU活性化関数をConcatenated ReLU（CReLU）に置き換えることで大幅に軽減され、学習能力が維持された。
</p>

<h3>● Lottery Ticket Hyposis (宝くじ仮説)</h3>
<p>
『The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks』(2019)<br>
　論文は<a href="https://arxiv.org/abs/1803.03635">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/2007.12223v2">こちら</a>,　機械翻訳は<a href="https://boyoyon.github.io/HTMLs_translated_to_Japanese/2019_The%20Lottery%20Ticket%20Hypothesis/2019_The%20Lottery%20Ticket%20Hypothesis%20-%20Finding%20Sparse,%20Trainable%20Neural%20Networks.html">こちら</a>
</p>
<p>
宝くじ仮説を導入した論文。<br>
<br>
モデルの規模を大きくしないと精度が上がらない。<br>
しかし, 一旦高精度なモデルができたら枝刈りしてもなかなか精度が落ちない。<br>
→　小さくて高精度な当りくじモデルが存在すると仮定。<br>
　　モデルを大きくしていき、当りくじが取り込まれると高精度になる。<br>
　　枝刈りしても当りくじが削られなければ高精度は維持される。<br>
　　んじゃないの? 仮説<br>

</p>

<h3>● Measurement Semantics (計測意味論)</h3>
<p>
『Nonlinear Modeling and Forecasting』(1992)<br>
　論文は<a href="https://www.amazon.co.jp/-/en/Martin-Casdagli/dp/0201587882">アマゾン</a>で中古で購入可能, 引用論文の要約は<a href="https://www.alphaxiv.org/ja/overview/2505.19275v1">こちら</a><br>
<br>
「計測意味論」の起源。<br>
観測の意味がエージェントの内部モデルをどのように更新するかによって決定されるという考えを確立。
</p>

<h3>● Modality Gap </h3>
<p>
『Mind the gap: Understanding the modality gap in multi-modal contrastive representation learning』(2022)<br>
　論文は<a href="https://arxiv.org/abs/2203.02053">こちら</a><br>
<br>
「モダリティギャップ」を初めて特定し、命名した論文。<br>
異なるデータモダリティ（画像とテキストなど）が共有表現に近接して埋め込まれていることを示す。体系的な分析により、このギャップはモデルの初期化と対照学習による最適化の組み合わせによって引き起こされることが実証された。
</p>

<h3>● Neural Collapse </h3>
<p>
『Prevalence of neural collapse during the terminal phase of deep learning training』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2008.08186">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/2008.08186v2">こちら</a>
</p>
<p>
深層学習の訓練中にデータの特徴が単純で規則的な幾何学構造に収束するという「Neural Collapse(NC)」現象を観察、命名し、包括的に文書化した画期的な論文
</p>

<h3>● NeRF</h3>
<p>
『NeRF: Representing scenes as neural radiance fields for view synthesis』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2003.08934">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2003.08934v2">こちら</a>
</p>
<p>
Neural Radiance Fields (NeRF)を導入した論文
</p>

<h3>● NTK: Neural Tanget Kernel</h3>
<p>
『Neural tangent kernel: convergence and generalization in neural networks』(2018)<br>
　論文は<a href="https://arxiv.org/abs/1806.07572">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1806.07572v4">こちら</a>
</p>
<p>
Neural Tangent Kernel (NTK) を導入した画期的な論文
</p>

<h3>● PINNs: Physics Informed Neural Networks</h3>
<p>
『Artificial Neural Networks for Solving Ordinary and Partial Differential Equations』(1997)<br>
　論文は<a href="https://arxiv.org/abs/physics/9705023">こちら</a><br>
<br>
ニューラルネットワークの出力の導関数を計算することによって、微分方程式を解くためにニューラルネットワークを制約することを初めて提案した、<br>
PINNsは後に解析的微分ではなくバックプロパゲーションを用いることで発展した。
</P>

<p>
『Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations』(2019)<br>
論文は<a href="https://pdf.sciencedirectassets.com/272570/1-s2.0-S0021999118X00229/1-s2.0-S0021999118307125/am.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEN7%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQC1gHlI4ZNDUmlFkjk9Ty4S%2B3qV7gQApMN5htGoFm%2FE8QIhAK%2FsM6Hj%2FAFaafewJF9VV8cVPuez%2Bgiq2or%2BrbV3PxvLKrMFCEcQBRoMMDU5MDAzNTQ2ODY1IgxL6uJPM2aSR%2Bme0%2B8qkAXGjhdKZ%2BEcLI3hNVAfK4lXUg%2F0PxkQjVHnolGkZ4WEruwxJ1TQ1gIWOng9zPZ7U7T06U%2FYPbMRdDkkcQ2tUhndddKLmjdV%2B1xpwZAp%2FywPWV95Pii7zgxNYSiDyF4aBcT7knUaKjLPBswqE9u92T6ZGMX8tUtFSOl1yiG4Dc7xSAoaozLlLGt8EtZrUt3qGeUwFL0q7h%2FVLEvoiGpi5UjRfLLcziKZIRqLVdXRtyo1tfxzqHYCqW29SmJsg0czR2K0zEsUtz0CP8YE3bchtnz3rs9PwwBBhNVppmNRUFOOFSSoysio3CQro3pH%2BJ%2BoRhfyUQjrbU18lJf4AswAXWhQ5JWTcFCm5wuvuubIhmy7xNIuAjbYBc90sFbhj65Qx0q2sR2RG3r1ZjZjcfz3Llt%2FBuQ9PMgcmf8ku8sDwoIGASB%2BY2KA8vZzlVwg%2FtyaW6AtqeSmwrlyUs%2FODqvj%2Fv17MXRyjqKHxj2NVy9d8b3GGjup5YjUKimd9%2Bf7MpU8iCadhet4cL0rmO2eQ2eUjHt%2BGRtkqdikLQR%2Fqs%2FE9Mpv456s164cCBNgs5S89G4LS%2Brnsm8TE8PEnEKTNNWC7JoPUbV9cFDEPILFfD4HN1lDpI8bRV3R1Jm%2BysWaeQ05gjfdTIVZy7RgO17w7CBlouUEnD84xQXRcE%2BmJmed5IHAQkNkaKvDVrwqqb78iQBHg7aBEt2Q1My9xMFw3PQ5oRq8XZ2kL%2B%2BQCzmKx%2BrJHEPJkeDGuGrAbVb6uE%2FnOFkEmcX%2Ff6FdtGVpxX6kb16VTbWxffS1rvWda2vKQKZeEmjq7QTlgeJUhGLdMdXwr2GIhfdgU99akXmeCcYO0cbfNtAoTTiEzvsk7y6Hir6nIeArfjCejuHFBjqwAZDcHnUonVWCm6faEoMIgSKyW0cIU1jLmzvWJDe2ZI2fDEd%2F806eIXYmNzXCJeW0Eh85jJaqxhJWwCo5IIAKejegn8XL3sB5%2FpUwL2THTcmCsBZNTERBtSBZXKAhE%2Fu5Jdpn0mYbEzGadXVlCQh5G8NakAfiy3LJaevr97wGSFmEMycz0rWuUM1DdTHNvoqYJZ5rey8GgAWVhSXpxaolWaIoNT1iIPmT3Wp5IJCUvI%2BB&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20250903T142032Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY2STUEZT4%2F20250903%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=032cc2ad1e6000e4fcfe2001e1b3dd4c8b81c401065e9c48a0243babd6f4c9e5&hash=e9b0d2a95266ebde86e6aab9fd4e8f230d5f0dd6e6ba14fa6b7730770b2548f7&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0021999118307125&tid=pdf-8b93dc05-8a64-4954-8798-3d904f49b4f4&sid=a3c42a9b720cb5408878d409baf2629898aegxrqa&type=client">こちら</a><br>
<br>
現代の物理情報ニューラルネットワーク (PINN) フレームワークを導入した
</p>

<h3>● Primacy Bias (プライマシーバイアス, 初頭バイアス)</h3>
<p>
『The role of first impression in operant learning』(2012)<br>
　論文は<a href="https://loewenstein.huji.ac.il/sites/default/files/yonatanloewenstein/files/2012-23008-001_2013.pdf">こちら</a>
</p>
<p>
「Primacy Bias」の概念的起源と命名法を提供している<br>
あるタスクで最初に学習されたニューラルネットワークが、異なるデータ分布や目的（あるいはその両方）で学習されると、新しいタスクにおいてランダムに初期化されたネットワークよりもパフォーマンスが低下する。<br>
→ AIモデルを継続学習する場合, 課題になる。
</p>

<h3>● Pruning (枝刈り)</h3>
<p>
『Optimal Brain Damage』(1989)<br>
　論文は<a href="https://proceedings.neurips.cc/paper/1989/file/6c9882bbac1c7093bd25041881277658-Paper.pdf">こちら</a>
</p>
<p>
タイトル(最適脳損傷)が怖い･･･
</p>

<h3>●RAG: Retrieval-Augmented Generation (検索拡張生成, 取得拡張生成)</h3>
<p>
『Retrieval-augmented generation for knowledge-intensive nlp tasks』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2005.11401">こちら</a>, 要約は<a href="">こちら</a><br>
<br>
質問に関連する文書を検索(Retrieval)し, 取得した文書をもとに(Augmented) LLM で回答を生成(Generation)することで、より正確で信頼性の高い回答を生成する技術。<br> 
RAG パラダイムを導入した画期的な論文。<br>
RAG は "open-book"QAパラダイムの実装手法の一つ。<br>
『Reading Wikipedia to answer open-domain questions』(2017)<br>
　論文は<a href="https://arxiv.org/abs/1704.00051">こちら</a><br>

⇔ "closed-book" QAパラダイム：知識をモデルのパラメータ内に完全に格納する<br>
『How much knowledge can you pack into the parameters of a language model?』(2020)<br>
　要約は<a href="https://www.alphaxiv.org/ja/overview/2002.08910v4">こちら</a>
</p>

<h3>● ReLU: Rectified Linear Unit </h3>
<p>
『Neocognitron: A Self-organizing Neural Network Model
for a Mechanism of Pattern Recognition
Unaffected by Shift in Position 』(1980)<br>
 論文は<a href="https://www.rctn.org/bruno/public/papers/Fukushima1980.pdf">こちら</a><br>
<br>
強調されていないが, さりげなく(まだ命名されていない) ReLU が使われている(式(2))。
</p>

<p>
『Rectified linear units improve restricted boltzmann machines』(2010)<br>
　論文は<a href="https://www.cs.toronto.edu/~fritz/absps/reluICML.pdf">こちら</a><br>
Rectified Linear Unit (ReLU) を導入した基礎的な論文。
<br>
</p>

<p>
『Deep sparse rectifier neural networks』(2011)<br>
 論文は<a href="https://proceedings.mlr.press/v15/glorot11a/glorot11a.pdf">こちら</a><br>
<br>
ReLU（Rectified Linear Unit）を導入し、収束の加速とスパース性の促進におけるその利点を議論すると同時に、「ReLUの死滅問題(dying ReLU problem)」を特定した
</p>

<p>
『Imagenet classification with deep convolutional neural networks (AlexNet論文)』(2012)<br>

　論文は<a href="https://proceedings.neurips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf">こちら</a>, 機械翻訳は<a href="https://boyoyon.github.io/HTMLs_translated_to_Japanese/2012_AlexNet/2012_Imagenet-classification-with-deep-convolutional-neural-networks.html">こちら</a><br>
<br>
　深層畳み込みネットワークにおけるReLUの有効性を示すことにより(図1.[tanhの6倍･･･」)、ReLUを普及させる上で極めて重要であり、その結果、広く採用されるようになった。
</p>

<p>
『Dying relu and initialization: Theory and numerical examples』(2019)<br>
　論文は<a href="https://arxiv.org/abs/1903.06733">こちら</a><br>
<br>
「ReLUの死滅問題」に関する詳細な分析と特定の実験設定を提供
</p>


<h3>● Self-Play(自己対局), Without human knowledge (人間知識なし)</h3>
<p>
『Mastering the game of go without human knowledge』(2017)<br>
　論文は<a href="https://discovery.ucl.ac.uk/id/eprint/10045895/1/agz_unformatted_nature.pdf">こちら</a>
</p>
<p>
人間データなしでの自己対局による強化学習という中核的な手法を確立した。
</p>

<h3>● Skip Connection (スキップ接続)</h3>
<p>
『Deep residual learning for image recognition』(2015)<br>
　論文は<a href="https://arxiv.org/abs/1512.03385">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1512.03385v1">こちら</a><br>
<br>
ResNetとスキップコネクションを用いた深層残差学習の概念を導入。
スキップコネクションがいかにしてはるかに深いネットワークの訓練を可能にし、性能劣化の問題を克服するかを示し、議論されるその後の多くの研究の基礎を形成した。
</p>
<p>
『Highway networks』(2015)<br>
　論文は<a href="https://arxiv.org/abs/1505.00387">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1505.00387v2">こちら</a><br>
<br>
ResNetの重要な前身。<br>
非常に深いネットワークにおける情報フローを促進するために、スキップコネクションとゲーティングメカニズムを使用するというアイデアを導入した。
</p>
<p>
『U-net: Convolutional networks for biomedical image segmentation』(2015)<br>
　論文は<a href="https://arxiv.org/abs/1505.04597">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1505.04597v1">こちら</a>, 機械翻訳は<a href="https://boyoyon.github.io/HTMLs_translated_to_Japanese/2015_UNet/2015_U-Net%20-%20Convolutional%20Networks%20for%20Biomedical%20Image%20Segmentation.html">こちら</a><br>
<br>
セグメンテーションにおける正確な局在化のために、エンコーダパスからの特徴をデコーダパスと結合するために長距離スキップコネクションを効果的に利用する画期的なアーキテクチャーを導入した
</p>

<h3>● sycophancy (おべっか, 追従性)</h3>

『Why AI alignment could be hard with modern deep learning』（ブログ)<br>
　ブログは<a href="https://www.cold-takes.com/why-ai-alignment-could-be-hard-with-modern-deep-learning/">こちら</a><br>
<br>
『Towards Understanding Sycophancy in Language Models』(2023)<br>
　論文は<a href="https://arxiv.org/abs/2310.13548">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2310.13548v4">こちら</a><br>
<br>
大規模言語モデルが様々な商用モデルやタスクにおいて、追従的な振る舞いを一般的に示すことが明らかになった。この傾向は、人間が「ユーザーの信念に合わせること」を非常に好むという人間選好データによって引き起こされており、その結果、選好モデルは事実の真実性よりも追従性を奨励するようになる。
</p>

<h3>● ToT: Tree of Thoughts (思考ツリー)</h3>
<p>
『Tree of thoughts: Deliberate problem solving with large language models』(2023)<br>
　論文は<a href="https://arxiv.org/abs/2305.10601">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2305.10601v2">こちら</a><br>
<br>
　複数の思考パスを探索することによってLLMの推論能力を向上させる最先端の手法を示している。
</p>


<h3>● Transformer</h3>
<p>
『Attention is all you need』(2017) <br>
　論文は<a href="https://arxiv.org/abs/1706.03762">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/1706.03762v7">こちら</a>
</p>
<p>
　Transformerアーキテクチャを導入した。
</p>

<h4>　・ViT: Vision Transformer</h4>
<p>
　　『An image is worth 16x16 words: Transformers for image recognition at scale』(2020)<br>
　　　論文は<a href="https://arxiv.org/abs/2010.11929">こちら</a><br>
<br>
　　　純粋なTransformerアーキテクチャを画像分類に適用することに初めて成功した。<br>
　　　画像をパッチに分割して入力トークンとするパラダイムを確立し、他の後続のVision Transformerが踏襲する基礎となるステップとなった。
</p>

<h4>　・DETR: Detection with Transformer</h4>
<p>
　　『End-to-end object detection with transformers』(2020)<br>
　　論文は<a href="https://arxiv.org/abs/2005.12872">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2005.12872v3">こちら</a><br>
<br>
　　物体検出を直接的な集合予測問題として再構築する検出トランスフォーマー (DETR) を導入した。<br>
　　この斬新なアプローチにより、検出パイプラインで一般的に用いられていた多くの手作業で設計されたコンポーネントが不要となった。これはパラダイムシフトを意味し、分類以外の主要なコンピュータビジョンタスクにおけるトランスフォーマーの礎石となる応用事例となった。
　　
</p>

<h3>● World Model</h3>
<p>
『Recurrent world models facilitate policy evolution』(2018)<br>
　論文は<a href="https://arxiv.org/abs/1809.01999">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/1809.01999v1">こちら</a><br>
<br>
「ワールドモデル」の概念を定義した初期の研究の一つ。
</p>
    </body>
</html>








