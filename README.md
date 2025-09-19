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

<h3>● Acquiescence Bias (黙認バイアス)</h3>
<p>
『Acquiescence Bias in Large Language Models』(2025)<br>
　(大規模言語モデルにおける黙認バイアス)<br>
　論文は<a href="https://arxiv.org/abs/2509.08480">こちら</a><br>
<br>
　「天気は良いですか、悪いですか？」という質問は、「天気は良いですか？」という質問とは異なる回答を導き出す可能性がある。この現象は「黙認バイアス」と呼ばれ、十分に文書化されており、数十年にわたって研究されてきた。
(アンケート回答者が、自分の本心とは関係なく、ある発言に同意する傾向がある場合、同意バイアスまたは「イエス」バイアスとも呼ばれる黙認バイアスを示すと言われている)。異なるモデル、タスク、言語（英語、ドイツ語、ポーランド語）におけるLLMの黙認バイアスの存在を調査した。結果は、人間とは対照的に、LLMは同意か不同意かに関わらず、「いいえ」と答える傾向を示すことを示唆している。
</p>

<h3>●Adversarial Vulnerabilities (敵対的脆弱性)</h3>
<p>
『Intriguing properties of neural networks』(2013)<br>
　(ニューラルネットワークの興味深い特性)<br>
　論文は<a href="https://arxiv.org/abs/1312.6199">こちら</a><br>
<br>
　ニューラルネットワークにおける敵対的脆弱性を初めて発見したもの。
</p>
<p>
『Explaining and Harnessing Adversarial Examples』(2014)<Br>
　(敵対的サンプルの解明と活用)<br>
　論文は<a href="https://arxiv.org/abs/1412.6572">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1412.6572v3">こちら</a><br>
<br>
パンダ画像に少しノイズを加えるとテナガザルと誤認識する、という例の論文。
最先端のモデルが知覚できない摂動によって体系的に騙されることを実証することで、安全性に重要なアプリケーションに展開されているAIシステムにおける重大な脆弱性を浮き彫りにした。
</p>
<p>
『Extracting training data from large language models』(2020)<br>
　(大規模言語モデルからの学習データ抽出)<br>
　論文は<a href="https://arxiv.org/abs/2012.07805">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2012.07805v2">こちら</a><br>
<br>
この画期的な研究は、大規模言語モデルからの学習データ抽出における具体的なリスクを実証し、プライバシーの脆弱性に対する重要な証拠を提供
した。
</p>
<p>
『The secret sharer: Evaluating and testing unintended memorization in neural networks』(2018)<br>
　(秘密の共有者：ニューラルネットワークにおける意図せざる記憶の評価と検証)<br>
　論文は<a href="https://arxiv.org/abs/1802.08232">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1802.08232v3">こちら</a><br>
<br>
　「カナリア」挿入を用いてニューラルネットワークから学習データを抽出する概念を確立。

</p>
<p>
『Membership inference attacks against machine learning models』(2016)<br>
　(機械学習モデルに対するメンバーシップ推論攻撃)<br>
　論文は<a href="https://arxiv.org/abs/1610.05820">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1610.05820v2">こちら</a><br>
<br>
攻撃者が特定の例が訓練セットに含まれていたかどうかを判断する、密接に関連した問題であるメンバーシップ推論攻撃に関する基礎的な研究
</p>

<h3>● AI Alignment (AIアライメント), RLHF, DPO</h3>
・人間の意図する目的や嗜好、倫理原則に合致させること<br>
・RLHF: Reinforment Learning from Human Feedback<br>
・DPO: Direct Preference Optimization<br>
<br>
<p>
『Direct preference optimization: Your language model is secretly a reward model』(2023)<br>
　(ダイレクト選好最適化：あなたの言語モデルは密かに報酬モデルである)<br>
　論文は<a href="https://arxiv.org/abs/2305.18290">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2305.18290v3">こちら</a><br>
<br>
　人間からのフィードバックによる強化学習（RLHF:Reinforcement Learning from Human Feedback）の複雑さを回避し、大規模言語モデルを人間の好みに合わせてファインチューニングする手法を導入してい
</p>

<p>
『Training language models to follow instructions with human feedback』(2022)<br>
　(人間からのフィードバックによる指示追従言語モデルの訓練)<br>
　論文は<a href="https://arxiv.org/abs/2203.02155">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2203.02155v1">こちら</a><br>　
<br>
多段階の人間からのフィードバックによる強化学習（RLHF）パイプラインを確立した
</p>
<p>
『A general language assistant as a laboratory for alignment』(2021)<br>
　(アライメントの実験室としての一般言語アシスタント)<br>
　論文は<a href="https://arxiv.org/abs/2112.00861">こちら</a><br>
<br>
　有用性、正直さ、無害さに焦点を当てたアライメント評価のフレームワーク
</p>

<h3>● AI-image detectors</h3>
<p>
『CNN-generated images are surprisingly easy to spot... for now』(2019)<br>
　(CNN生成画像は驚くほど見破りやすい…今のところは)<br>
　論文は<a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_CNN-Generated_Images_Are_Surprisingly_Easy_to_Spot..._for_Now_CVPR_2020_paper.pdf">こちら</a><br>
<br>
　AI画像検出器における汎化問題を初めて浮き彫りにした基礎的な論文    
</p>

<h3>● Attention Sinks</h3>
<p>
　『Efficient streaming language models with attention sinks』(2023)<br>
　論文は<a href="https://arxiv.org/abs/2309.17453">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2309.17453v4">こちら</a><br>
<br>
　「アテンションシンク」現象を初めて特定し、命名した基礎的な論文    
</p>
<p>
『Massive activations in large language models』(2024)<br>
　(大規模言語モデルにおける大規模な活性化)<br>
　論文は<a href="https://arxiv.org/abs/2402.17762">こちら</a>,要約は<a href="https://www.alphaxiv.org/ja/overview/2402.17762v2">こちら</a><br>
<br>
言語モデルにおける「大規模な活性化 (massive activations)」が「アテンションシンク (attention sinks)」を引き起こすという並行現象を特定しており、トランスフォーマーにおける高ノルムトークンの問題に対し、より広範な文脈を提供する
</p>
<p>
『Vision Transformers Don't Need Trained Registers』(2025)<br>
　(ビジョン・トランスフォーマーに学習済みレジスタは不要)<br>
　論文は<a href="">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2506.08010v4">こちら</a><br>
<br>

Vision Transformer (ViT) のMLPブロック内の特定の「レジスタニューロン」が、高ノルムトークンの因果的な発生源であることを特定した。未学習のトークンを付加し、これらの高ノルム活性をリダイレクトする訓練不要の手法「テスト時レジスタ」を導入した。これにより、よりクリーンなアテンションマップ、密な視覚タスクと物体発見における性能向上、そしてVision-Languageモデルにおける解釈可能性の向上がもたらされた。<br>
<br>
言語モデルにおける同様の現象（「アテンションシンク」）と関連しており、このような計算パターンがモダリティを超えたトランスフォーマーアーキテクチャにとって基本的なものである可能性を示唆している。
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
<p>
『Why there are complementary learning systems in the hippocampus and neocortex: insights from the successes and failures of connectionist models of learning and memory』(1995)<br>
　(海馬と新皮質に相補的学習システムが存在する理由：学習と記憶のコネクショニストモデルの成功と失敗から得られた知見)<br>
　論文は Google Scholar で検索すると pdf に辿り着ける<br>
<br>
　海馬が新しい情報の迅速な学習を可能にし、大脳新皮質が既存の知識への緩やかな統合をサポートするという相補的学習システム理論を提唱した基礎論文。脳がどのように安定性-可塑性ジレンマを解決し、AIにおける中心的な問題である壊滅的忘却を回避するかを説明
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
<p>
『Large language models are zero-shot reasoners』(2022)<br>
　(大規模言語モデルはゼロショット推論器である)<br>
　論文は<a href="https://arxiv.org/abs/2205.11916">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2205.11916v4">こちら</a><br>
<br>
本論文は、影響力のある「Let's think step by step」プロンプトを導入し、zero-shot Chain-of-Thought (CoT) パラダイムを確立した。
</p>

<h3>● Continual Learning (継続学習), Lifelong Learning(生涯学習)</h3>
<p>
  『Lifelong machine learning』(2018)<br>
　　論文は<a href="https://link.springer.com/content/pdf/bfm:978-3-031-01581-6/1?pdf=chapter+toc">こちら</a><br>
<br>
    継続学習（CL）、別名「生涯学習」の分野を定義した。
</p>
<p>
『What Neuroscience Can Teach AI About Learning in Continuously Changing Environments』(2025)<br>
　(神経科学がAIに教えうる、継続的に変化する環境における学習)<br>
　論文は<a href="https://arxiv.org/abs/2507.02103">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2507.02103v1">こちら</a><br>
　神経科学の原理が、絶えず変化する環境で学習できるAIシステムの開発にどのように役立つかを探る。    
</p>
<p>
『Embracing change: Continual learning in deep neural networks』(2020)<br>
　(変化を受け入れる：深層ニューラルネットワークにおける継続学習)<br>
　論文は<a href="https://www.cell.com/trends/cognitive-sciences/pdf/S1364-6613(20)30219-9.pdf">こちら</a><br>
<br>
継続学習分野における主要な課題と方向性をまとめた、影響力のある展望論文
</p>

<h3>● Contrastive Learning (対照学習)</h3>
<p>
 『A simple framework for contrastive learning of visual representations』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2002.05709">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2002.05709v3">こちら</a><br>
<br>
　画期的なコントラスト学習手法であるSimCLRを導入   
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

<h3>● Dimensional Collapse (次元崩壊)</h3>
<p>
『Understanding dimensional collapse in contrastive self-supervised learning』(2021)<br>
　論文は<a href="https://arxiv.org/abs/2110.09348">こちら</a><br>
<br>
　表現がより低次元のサブスペースを占める「次元崩壊」を特定し分析した   
</p>

<h3>● Distributed representations  (分散表現)</h3>
<p>
　『Distributed representations of words and phrases and their compositionality』(2013)<br>
　(単語とフレーズの分散表現およびその構成性)<br>
　論文は<a href="https://arxiv.org/abs/1310.4546">こちら</a><br>
<br>
word2vecに関するこの記念碑的な論文は、言語モデルが構造的な関係性を捉える「分布的意味論」を学習するという重要な証拠を提供。
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

<h3>●DVS: Dynamic Vision Sensors. Event Camera, Temporal Trailing(時間的引きずり)</h3>
<p>
『From video frames to realistic dvs events』(2021)<br>
　(v2e: ビデオフレームから現実的なDVSイベントへ)<br>
　論文は<a href="https://arxiv.org/abs/2006.07722">こちら</a><br>
<br>
センサーがローパスフィルターのように振る舞うという物理モデルが、低照度下でのイベントの「時間的引きずり（temporal trailing）」現象を説明する
</p>

<h3>● Episodic Memory (エピソード記憶)</h3>
<p>
『Episodic and semantic memory』(1972)<br>
　本の一部は<a href="https://alicekim.ca/EMSM72.pdf">こちら</a>, 引用論文の要約は<a href="https://www.alphaxiv.org/ja/overview/2505.03434v1">こちら</a><br>
<br>
認知科学におけるエピソード記憶と意味記憶の重要な区別を提示している。
</p>
<p>
『Episodic memory in AI agents poses risks that should be studied and mitigated』(2025)<br>
　(AIエージェントのエピソード記憶は研究され軽減されるべきリスクをもたらす)<br>
　論文は<a href="https://arxiv.org/abs/2501.11739">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2501.11739v2">こちら</a><br>
<br>
著者は、AIエージェントがより洗練され、より長期間にわたって動作するにつれて、人間と同様のエピソード記憶能力を必然的に開発するだろうと主張します。この進歩は、計画、問題解決、経験からの学習においてAIのパフォーマンスを大幅に向上させる可能性があります。<br>
しかし、それはまた、AI安全コミュニティがこれらの能力が普及する前に、積極的に対処すべき新しい種類の危険をもたらします。
</p>

<h3>● Generative Model (生成モデル)</h3>
<p>
『Generative Adversarial Networks』(2014)<br>
　論文は<a href="https://arxiv.org/abs/1406.2661">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1406.2661v1">こちら</a><br>
<br>
　敵対的生成ネットワーク（GAN）アーキテクチャを導入した基礎的な論文
</p>
<p>
『The GAN is dead; long live the GAN! A Modern GAN Baseline』(2025)<br>
　(GANは死んだ。GAN万歳！現代のGANベースライン)<br>
※ タイトルは英語の古い慣用句「The king is dead; long live the king!（王は死んだ、王万歳！）」をもじったもの。前の王が亡くなった瞬間に新しい王が即位することを意味し、王位の継続性を強調する表現。<br>
　論文は<a href="https://arxiv.org/abs/2501.05441">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2501.05441v1">こちら</a><br>
<br>
アドホックなトリックをすべて捨て、一般的なGANで使用されている時代遅れのバックボーンを現代的なアーキテクチャに置き換えた。
FFHQ、ImageNet、CIFAR、Stacked MNIST データセットで StyleGAN2 を上回り、最先端の GAN や拡散モデルと比べても遜色ない。
</p>

<h3>● GNN: Graph Neural Networks</h3>
<p>
『Semi-supervised classification with graph convolutional networks』(2016)<br>
　(グラフ畳み込みネットワークを用いた半教師あり分類)<br>
　論文は<a href="https://arxiv.org/abs/1609.02907">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1609.02907v4">こちら</a><br>
<br>
　グラフニューラルネットワーク（GNNs）の基本的な種類の一つであるグラフ畳み込みネットワーク（GCNs）を導入した記念碑的な論文
</p>
<p>
『Graph attention networks』(2017)<br>
　論文は<a href="https://arxiv.org/abs/1710.10903">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1710.10903v3">こちら</a><br>
<br>
　アテンション機構が組み込みの解釈性を提供するGNNアーキテクチャであるGraph Attention Networks（GAT）を導入した。
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
<p>
『Why language models hallucinate』(2025)<br>
　(なぜ言語モデルはハルシネーションを起こすか)<br>
　論文は<a href="https://www.arxiv.org/abs/2509.04664">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2509.04664v1">こちら</a><br>
<br>
難問に直面する学生のように、大規模言語モデルは不確実な状況において推測を行い、不確実性を認める代わりに、もっともらしくも誤った記述を生成することがある。<br>
「幻覚」は, 学習と評価の手順において、不確実性を認めるよりも推測を優先させるためだと主張する。<br>

幻覚は必ずしも不可解なものではなく、単に二値分類における誤りとして発生する。<br>

言語モデルが優れた受験者になるように最適化され、不確実な状況において推測を行うことでテストの成績が向上するために、幻覚が根強く残ると主張する。
</p>

<h3>● Hubness (ハブ性)</h3>
<p>
　『Hubs in space: Popular nearest neighbors in high-dimensional data』(2010)<br>
　論文は<a href="https://www.jmlr.org/papers/volume11/radovanovic10a/radovanovic10a.pdf">こちら</a><br>
<br>
　高次元データにおけるハブ性現象を提唱し、定義した基礎的な論文
</p>

<h3>●Implicit Bias (暗黙のバイアス)</h3>
<p>
『Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings』(2016)<br>
　(男性とコンピュータープログラマーの関係は、女性と主婦の関係と同じ？単語埋め込みのバイアス除去する)<br>
　論文は<a href="https://arxiv.org/abs/1607.06520">こちら</a><br>
<br>
　影響力のある論文。言語モデルにおけるバイアスへの懸念を高めた主要な研究の一つ。
単語埋め込みにおける強い性別ステレオタイプを実証している。
</p>

<h3>●intent extraction (意図抽出), goal understanding (目標理解)</h3>
<p>
『Identifying User Goals from UI Trajectories』(2024)<br>
　(UI軌跡からのユーザー目標の特定)<br>
　論文は<a href="https://arxiv.org/abs/2406.14314">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2406.14314v2">こちら</a><br>
<br>
　UI軌跡からの目標識別の最初の形式的な定義を提供し、タスクの成功裏の完了とユーザーの熟練度に関する明確な前提を確立した。
<p>
『Learning Intents behind Interactions with Knowledge Graph for Recommendation』(2021)
　(推薦のための知識グラフを用いたインタラクションの背後にある意図学習)<br>
　論文は<a href="https://arxiv.org/abs/2102.07057">こちら</a><br>
<br>
　インタラクションデータのみからユーザーの意図をモデル化し、知識グラフを用いてユーザーの嗜好の多様な側面を捉えるための基礎的な研究
</p>

<h3>● IRL: Inverse Reinforcement Learning (逆強化学習)</h3>
<p>
エキスパートの行動を観察し, エキスパートは何を報酬として, どう行動するか(Policy)を学習する。
</p>
<p>
『Algorithms for inverse reinforcement learning』(2000)<br>
　(逆強化学習のアルゴリズム)<br>
　論文は<a href="https://ai.stanford.edu/~ang/papers/icml00-irl.pdf">こちら</a><br>
<br>
　IRLの基礎論文。
</p>
<p>
『 Generative adversarial imitation learning.』(2016)<br>
　論文は<a href="https://arxiv.org/abs/1606.03476">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1606.03476v1">こちら</a><br>
<br>
　Generative Adversarial Imitation Learning (GAIL) フレームワークを導入し、GANとIRLの関連性を確立した基礎的な論文
</p>
<p>
『Inverse Reinforcement Learning without Reinforcement Learning』(2023)<br>
　(強化学習なしの逆強化学習)<br>
　論文は<a href="https://arxiv.org/abs/2303.14623v4">こちら</a><br>
<br>
　逆強化学習（IRL）は、熟練者のデモンストレーションを合理化する報酬関数の学習を目的とする、模倣学習のための強力な手法群である。従来のIRL手法には計算上の弱点があり、難しい強化学習（RL）問題をサブルーチンとして繰り返し解く必要があった。
模倣学習というより容易な問題を、より困難なRL問題を繰り返し解く問題に縮約した。理論上は指数関数的な高速化を実現する。実際に、連続制御タスクにおいて従来技術を大幅に高速化できることが分かった。
</p>
<p>
『Inverse Reinforcement Learning Meets Large Language Model Post-Training: Basics, Advances, and Opportunities』(2025)<br>
　(逆強化学習と大規模言語モデルの追加学習の融合：基礎、進展、そして機会)<br>
　論文は<a href="https://arxiv.org/abs/2507.13158">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2507.13158v1">こちら</a><br>
<br>
　大規模言語モデル（LLM）の生成を、報酬関数が事前に定義されていないマルコフ決定過程（MDP\R）として捉え、逆強化学習（IRL）がLLMの学習後調整とアライメント(人間の価値観に合うように調整すること)にどのように適用されるかを包括的にレビューしたチュートリアル。
RLHFやDPOといった手法がIRLの一種であることを示している。
</p>

<h3>● Knowledge Distillation (知識蒸留)</h3>
<p>
『Distilling the knowledge in a neural network』(2015)<br>
　論文は<a href="https://arxiv.org/abs/1503.02531">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1503.02531v1">こちら</a>
</p>
<p>
より小さな「生徒」ネットワークがより大きな「教師」ネットワークから学習するという、知識蒸留（KD）の概念を導入した基礎となる論文。<br>
蒸留のインスピレーションはお酒かと思ったら昆虫で, 「教師」が「幼虫」. 「生徒」が「成虫」というのも意外･･･<br>
人が与えるワンホットの正解では「生徒」モデルは学習困難 (「間違いです」としか言ってもらえない)。<br>
「教師」モデルの出力(Softmax 適用前の Logit。Dark Knowlegeと呼ばれる)があると,「おしい」とか「全然違う」とか<br>
ヒントが貰えるので「生徒」モデルでも学習がはかどる･･･という感じ
</p>
<p>
『Fantastic Gains and Where to Find Them: On the Existence and Prospect of General Knowledge Transfer between Any Pretrained Model』(2023)<br>
　(目覚ましい成果とその見つけ方：あらゆる事前学習済みモデル間での汎用的な知識転移の存在と展望)<br>
　論文は<a href="https://arxiv.org/abs/2310.17653">こちら</a>, 要約は<a href="目覚ましい成果とその見つけ方：あらゆる事前学習済みモデル間での汎用的な知識転移の存在と展望">こちら</a><br>
<br>
事前学習済み深層学習モデルの任意のペア間で、弱いモデルから強いモデルへの転送を含め、相補的な知識を一貫して転送し、学生モデルの精度を向上させる手法を提案している。信頼度に基づくデータ分割を伴う継続的知識蒸留（KL-Dist + DP）は、多様なモデルの組み合わせにおいて、ポジティブな知識転送で92.5%の中央値成功率を達成した。
</p>
<p>
『Merge-of-Thought Distillation』(2025)<br>
　(思考の統合蒸留)<br>
　論文は<a href="https://arxiv.org/abs/2509.08814">こちら</a><br>
<br>
　生徒ごとに「最適な教師」が異なり、同じ生徒であってもデータセットごとに最適な教師が異なる場合があることを観察した。そこで、複数の教師の推論能力を生徒に統合し、様々な教師の教師間の矛盾を克服するために、我々はMerge-of-Thought Distillation（MoT）を提案する。
</p>

<h3>● Linear mode connectivity (線形モード接続性)</h3>
<p>
『Linear mode connectivity and the lottery ticket hypothesis』(2019)<br>
　論文は<a href="https://arxiv.org/abs/1912.05671">こちら</a><br>
<br>
同じ初期化から訓練されたモデルが損失ランドスケープ内で連結され得ることを示唆
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

<h3>● Lost in the Middle (「真ん中が失われる」現象)</h3>
<p>
『Lost in the middle: How language models use long contexts』(2023)<br>
　(中間での情報喪失：言語モデルはいかに長いコンテキストを利用するか)<br>
　論文は<a href="https://arxiv.org/abs/2307.03172">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2307.03172v3">こちら</a><br>
<br>
LLMの注意バイアスである「真ん中が失われる」現象を特定してい
</p>
<p>
『The serial position effect of free recall』(1962)<br>
　(自由想起における系列位置効果)<br>
<br>
この基礎的な心理学の論文は、「"serial-position effect(系列位置効果)」という概念を導入してる。
</p>
<p>
『Sharp nearby, fuzzy far away: How neural language models use context』(2018)<br>
　(近くは鮮明に、遠くはぼやけて：ニューラル言語モデルは文脈をどのように利用するか)<br>
　論文は<a href="https://aclanthology.org/P18-1027/">こちら</a><br>
<br>
　言語モデルが強い直近性バイアス（遠い文脈よりも近い文脈をより良く利用する傾向）を持つことを確立した。
</p>
<p>
『Principled Content Selection to Generate Diverse and Personalized Multi-Document Summaries』
　(多様でパーソナライズされた複数文書要約のための原則に基づいたコンテンツ選択)<br>
　論文は<a href="https://arxiv.org/abs/2505.21859">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2505.21859v1">こちら</a><br>
<br>

「中間を見失う(lost in the middle)」現象の経験的証拠を提供し、原理に基づいたコンテンツ選択がLLM固有の限界をどのように克服できるかを示している。
</p>


<h3>● LTH: Lottery Ticket Hyposis (宝くじ仮説)</h3>
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

<h3>● Model soups (モデルスープ)</h3>
<p>
『Model soups: averaging weights of multiple fine-tuned models improves accuracy without increasing inference time』(2022)<br>
　(モデルスープ：複数のファインチューニング済みモデルの重み平均による、推論時間増加なしの精度向上)<br>
　論文は<a href="https://arxiv.org/abs/2203.05482">こちら</a><br>
<br>
この影響力のある論文は、単純な重み平均の力を実証することで、モデルマージングの普及に貢献した。その成功は、モデルマージングの実用的な関連性と潜在的なセキュリティリスクを浮き彫りにし、MergeLockのような保護ソリューションの開発を直接的に動機付けた。
</p>

<h3>●MoE: Mixture-of-Experts (専門家混合)</h3>
<p>
『Outrageously large neural networks: The sparsely-gated mixture-of-experts layer』(2017)<br>
　(途方もなく巨大なニューラルネットワーク：疎にゲートされた専門家混合層)<br>
　論文は<a href="https://openreview.net/forum?id=B1ckMDqlg">こちら</a><br>
<br>
　スパース活性化に対する基礎的な学習ベースのアプローチであるスパースゲート型混合専門家（MoE）層を導入した画期的な論文。
</p>

<h3>● NAS: Neural Architecture Search</h3>
<p>
『Efficient Global Neural Architecture Search』(2025)<br>
　(効率的なグローバルニューラルアーキテクチャ探索)<br>
　論文は<a href="https://arxiv.org/abs/2502.03553">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/2502.03553v1">こちら</a><br>
<br>
　効率的なグローバルニューラルアーキテクチャ探索（NAS）フレームワークは、ニューラルネットワークのエンドツーエンド設計を自動化し、非常に正確でパラメータ効率の高いモデルを生成する。EMNISTやKMNISTなどのデータセットで最先端の結果を達成し、CIFARで競合する性能を発揮するとともに、探索時間を大幅に短縮し、実世界の顔認識タスクへの高い転用可能性を示している。
</p>
<p>
『Neural architecture search with reinforcement learning.』(2016)<br>
　(強化学習を用いたニューラルアーキテクチャ探索)<br>
　論文は<a href="https://arxiv.org/abs/1611.01578">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1611.01578v2">こちら</a><br>
<br>
強化学習を用いてニューラルアーキテクチャ探索（NAS）の概念を導入した記念碑的な論文
</p>
<p>
『Random search for hyper-parameter optimization』(2012)<br>
　(ハイパーパラメータ最適化におけるランダム探索)<br>
　論文は<a href="https://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a.pdf">こちら</a><br>
<br>
ハイパーパラメータ最適化における強力なベースラインとしてランダムサーチを確立した。
</p>

<h3>● NeRF</h3>
<p>
『NeRF: Representing scenes as neural radiance fields for view synthesis』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2003.08934">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2003.08934v2">こちら</a>
</p>
<p>
　Neural Radiance Fields (NeRF)を導入した論文
</p>

<h3>● Neural Collapse </h3>
<p>
『Prevalence of neural collapse during the terminal phase of deep learning training』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2008.08186">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/2008.08186v2">こちら</a>
</p>
<p>
　深層学習の訓練中にデータの特徴が単純で規則的な幾何学構造に収束するという「Neural Collapse(NC)」現象を観察、命名し、包括的に文書化した画期的な論文
</p>
<p>
『Neural Collapse versus Low-rank Bias: Is Deep Neural Collapse Really Optimal?』(2024)<br>
　(ニューラル縮退 対 低ランクバイアス：深層ニューラル縮退は本当に最適なのか？)<br>
　論文は<a href="https://arxiv.org/abs/2405.14468">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2405.14468v2">こちら</a><br>
<br>
　多層、多クラスの深層ニューラルネットワークにおいて、特にクラス平均の直交性に関して、ディープニューラルコラプス（DNC）が一般的に最適ではないことを実証しました。彼らは、正則化における暗黙の低ランクバイアスが、より優れた低損失の解、例えば大幅に低い中間ランクを持つ彼らの新しい「Strongly Regular Graph (SRG) 解」につながることを特定しました。
</p>

<h3>● Neural ODE</h3>
<p>
『Stable architectures for deep neural networks』(2017)<br>
　論文は<a href="https://arxiv.org/abs/1705.03341">こちら</a><br>
<br>
　残差ネットワーク（Residual Networks）のようなモデルが、連続的な変換のオイラー離散化として解釈できるという重要な洞察を提供している
</p>
『Neural Ordinary Differential Equations』(2018)<br>
　論文は<a href="https://arxiv.org/abs/1806.07366">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1806.07366v5">こちら</a><br>
<p>
　ネットワーク層を常微分方程式に支配される連続的な変換としてモデル化する新しい深層学習アーキテクチャであるニューラル常微分方程式（Neural ODEs）を導入した。
</p>

<h3>● NTK: Neural Tanget Kernel</h3>
<p>
『Neural tangent kernel: convergence and generalization in neural networks』(2018)<br>
　論文は<a href="https://arxiv.org/abs/1806.07572">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1806.07572v4">こちら</a>
</p>
<p>
Neural Tangent Kernel (NTK) を導入した画期的な論文
</p>

<h3>● NTM: Neural Turing Machines</h3>
<p>
　『Neural turing machines』(2014)<br>  
　論文は<a href="https://arxiv.org/abs/1410.5401">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1410.5401v2">こちら</a><br>
<br>
    ニューラルネットワークに外部メモリを付加することに関する画期的な論文<br>
</p>

<h3>● Over-Squashing</h3>
<p>
『On the bottleneck of graph neural networks and its practical implications』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2006.05205">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2006.05205v4">こちら</a><br>
<br>
　GNNにおける「オーバースクワッシング」問題を初めて特定し命名した点で、現在の研究の基礎となっている。   
</p>

<h3>● Perceptual Metric (知覚メトリック, 知覚的距離)</h3>
<p>
『The Unreasonable Effectiveness of Deep Features as a Perceptual Metric』(2018)
　(深層特徴量の知覚メトリックとしての不合理な有効性)<br>
　論文は<a href="https://arxiv.org/abs/1801.03924">こちら</a>, 機械翻訳は<a href="https://boyoyon.github.io/HTMLs_translated_to_Japanese/2018_LPIPS/2018_The%20Unreasonable%20Effectiveness%20of%20Deep%20Features%20as%20a%20Perceptual%20Metric.html">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1801.03924v2">こちら</a><br>
<br>
　人間の知覚的類似性のメトリックとしての深層特徴の有効性を経験的に評価し、従来のメソッドに対する優位性を示している。LPIPS（Learned Perceptual Image Patch Similarity）という新しいメトリックと大規模データセットを導入した。
</p>
<p>
『Perceptual losses for real-time style transfer and super-resolution』(2016<br>
　(リアルタイムスタイル変換と超解像のための知覚損失)<br>
　論文は<a href="https://arxiv.org/abs/1603.08155">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1603.08155v1">こちら</a><br>
<br>
　事前学習済み深層ネットワーク（VGGなど）からの特徴量を「知覚損失（perceptual loss）」として画像合成や超解像タスクに用いる手法を普及させた
</p>
<p>
『Image quality assessment: from error visibility to structural similarity』(2004)<br>
　(画質評価：誤差可視性から構造類似性へ)<br>
　論文は<a href="https://ece.uwaterloo.ca/~z70wang/publications/ssim.pdf">こちら</a><br>
<br>
　非常に影響力があり広く用いられている従来の知覚評価指標である構造的類似度指標 (SSIM:Structural similarity index measure) を導入した。
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
論文は Google Scholar で検索すると pdf に辿り着ける<br>
<br>
現代の物理情報ニューラルネットワーク (PINN) フレームワークを導入した
</p>

<h3>●Policy Optimization(方策最適化), GRPO, PPO, A3C, CPI</h3>

<p>
『DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models』(2024)<br>
　(DeepSeekMath: オープン言語モデルにおける数学的推論の限界を押し広げる)<br>
　論文は<a href="https://arxiv.org/abs/2402.03300">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2402.03300v3">こちら</a><br>
<br>
　近接方策最適化（PPO）に代わる、メモリ効率の高いグループ相対方策最適化（GRPO）を導入した。
</p>

<p>
『Proximal policy optimization algorithms』(2017)<br>
　(近接方策最適化アルゴリズム)<br>
　論文は<ahref="https://arxiv.org/abs/1707.06347">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1707.06347v2">こちら</a><br>
<br>
　近接方策最適化（PPO）を導入した。
</p>

<p>
『Trust region policy optimization』(2015)<br>
　(信頼領域方策最適化)<br>
　論文は<a href="https://arxiv.org/abs/1502.05477">こちら</a>, 要約は<a href="https://www.alphaxiv.org/overview/1502.05477v5">こちら</a><br>
<br>
PPOの直接の前身であるTrust Region Policy Optimization（TRPO）を
導入した。
</p>

<p>
『Asynchronous methods for deep reinforcement learning』(2016)<br>
　(深層強化学習における非同期手法)<br>
　論文は<a href="https://arxiv.org/abs/1602.01783">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1602.01783v2">こちら</a><br>
<br>
主要なオンライン方策勾配手法であるAsynchronous Advantage Actor-Critic (A3C) が提案された。
</p>

<p>
『Approximately optimal approximate reinforcement learning』(2002)<br>
　(近似最適な近似強化学習)<br>
　論文は<a href="https://people.eecs.berkeley.edu/~pabbeel/cs287-fa09/readings/KakadeLangford-icml2002.pdf">こちら</a><br>
<br>
　PPOが最適化する代理目的関数の理論的基盤を提供する保守的方策反復 (CPI) を導入した。
</p>

<h3>● POMDPs: Partially Observable Markov Decision Proces (部分観測マルコフ決定過程)</h3>
<p>
『Planning and acting in partially observable stochastic domains』(1998)<br>
　論文は Google Scholar で検索すると pdf に辿り着ける<br>
<br>
　部分観測マルコフ決定過程 (POMDPs) に関する基礎的な論文   
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
<p>
『What Can Grokking Teach Us About Learning Under Nonstationarity?』(2025<br>
　(非定常性下での学習についてグロッキングから何が学べるでしょうか?)<br>
　論文は<a href="https://arxiv.org/abs/2507.20057">こちら</a>, 機械翻訳は<a href="https://boyoyon.github.io/HTMLs_translated_to_Japanese/2025_WHAT%20CAN%20GROKKING%20TEACH%20US%20ABOUT%20LEARNING/WHAT%20CAN%20GROKKING%20TEACH%20US%20ABOUT%20LEARNING%20UNDER%20NONSTATIONARITY.html">こちら</a><br>
<br>
　Grokkingを加速することができるなら, primacy bias に打ち勝って継続的に学習できる
</p>
<img src="images/primacy_bias.png">

<h3>● Priming</h3>
<p>
『Automaticity of social behavior: Direct effects of trait construct and stereotype activation on action』(1996)<br>
　(社会的行動の自動性：特性構成概念とステレオタイプ活性化の行動への直接的効果)<br>
　論文は<a href="https://acs.ist.psu.edu/misc/dirk-files/Papers/Automaticity%20of%20social%20behavior/AutomaticitySocBeh_BarghChenBurrows.pdf">こちら</a><br>
<br>
認知心理学における記念碑的な論文。プライミングの概念を確立した。<br>
<br>
プライミング･･･先行する刺激や情報が、後続の認知や行動に無意識的に影響を与える現象。<br>
(神様視点だと入れ知恵っぽい感じ)<br>
LLM, AIエージェントの社会などで同様の現象が研究されている。
</p>

<h3>● Proxy Token</h3>
<p>
『Generalized Decoupled Learning for Enhancing Open-Vocabulary Dense Perception』(2025)<br>
　(汎用デカップル学習によるオープンボキャブラリ密認識の強化)<br>
　論文は<a href="https://arxiv.org/abs/2508.11256">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2508.11256v1">こちら</a><br>

CLIPのアテンションメカニズムの詳細な分析を通じて、CLIPのアーキテクチャにおける重大な問題を特定した。
CLIPの画像トークンは「密な相関の消失」を示す。つまり、意味的または空間的に関連する領域に注意を向ける代わりに、特定の「プロキシトークン」に焦点を当てる。
DeCLIPは、CLIPの自己注意を分離し、「コンテンツ」と「コンテキスト」の特徴をVFMとStable Diffusionを用いて個別にガイドすることで、空間的一貫性と局所的な識別性を向上させる
</p>

<h3>● Pruning (枝刈り)</h3>
<p>
『Optimal Brain Damage』(1989)<br>
　論文は<a href="https://proceedings.neurips.cc/paper/1989/file/6c9882bbac1c7093bd25041881277658-Paper.pdf">こちら</a>
</p>
<p>
タイトル(最適脳損傷)が怖い･･･
</p>

<h3>● Qualia (クオリア)</h3>
<p>
『Constructive Approach to Bidirectional Influence between Qualia Structure and Language Emergence』(2024)<br>
(クオリア構造と言語創発の相互影響への構成的アプローチ)<br>
　論文は<a href="https://arxiv.org/abs/2409.09413">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2409.09413v2">こちら</a><br>
<br>
　言語の出現と主観的経験の関係構造（クオリア構造）の双方向的な影響を調査するための構成的アプローチを提案 
</p>
<p>
『The Qualia Structure Paradigm: towards a construction of a Qualia Periodic Table for the dissolution of the Hard Problem of Consciousness』(2024)<br>
　(クオリア構造パラダイム：意識の難問解決のためのクオリア周期表の構築に向けて)<br>
　論文は<a href="https://osf.io/492hu_v1/download/">こちら</a><br>
<br>
クオリア間の類似性が距離の公理（最小性、対称性、三角不等式）を満たすかどうかといった根本的な疑問さえも未だ解決されていない。
クオリアの「空間」については様々な種類が提案されているが、すべてのクオリアを何らかの高次元空間内の点とみなせるかどうかは不明である。現段階では、クオリアのための何らかの空間の存在を仮定するのではなく、一歩下がってクオリアの数学的「構造」の可能性を探る方がよいかもしれない。これが、「クオリア構造」パラダイムである。
圏論は構造を変換する形式的な方法として発明され、「自然変換」として導入された。自然変換を定義するために、関手が導入され, 関手を定義するために、圏論が導入された。圏論は幾何学や代数といった異なる「構造」間の「同一性」を、ある種の「変換」として特徴付けるために構築された。変換と類似性は関連しているが、後者は2つの実体間のある種の「距離」とより深く関係している。2つのクオリア構造間の類似性は、2つの構造間の同一性と同様に、圏論という数学的枠組みによって扱うことができると仮定している。
</p>
<p>
『Is my “red” your “red”?: Evaluating structural correspondences between color similarity judgments using unsupervised alignment』(2025)<br>
　(私の「赤」はあなたの「赤」か？：教師なしアラインメントを用いた色彩類似判断間の構造的対応の評価)

　論文は<a href="https://www.sciencedirect.com/science/article/pii/S2589004225002895">こちら</a><br>
<br>
「クオリア構造」を（色の類似性判断を通じて）経験的に測定し、それらをAIモデルの表現と、「教師なしアライメント」手法を用いて比較する方法を実証している。   
</P>

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
 論文は<a href="https://www.rctn.org/bruno/public/papers/Fukushima1980.pdf">こちら</a>,日本語の解説論文は<a href="https://www.jstage.jst.go.jp/article/mii/36/2/36_17/_pdf/-char/en#:~:text=ネオコグニトロンは、変形,正しくパターンを認識する．">こちら</a><br>
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

<h3>●Representation Biases (表現バイアス)</h3>

<p>
『Representation biases: will we achieve complete understanding by analyzing representations?』(2025)<br>
　(表現バイアス：表現の分析を通じて、我々は完全な理解に到達できるのか？)

　論文は<a href="https://arxiv.org/abs/2507.22216">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2507.22216v2">こちら</a><br>
<br>
深層学習モデルの内部表現に顕著なバイアスがある。
これらのバイアスは、PCAやRSAのような一般的な分析方法を使用する際に誤解を招く推論につながり、表現の強度が計算上の重要性を確実に示すという前提に異議を唱えている。
神経科学と機械学習の研究者全体にとって重要な警告となる。それは、広く用いられている分析的仮定が体系的に破られ得ることを示しており、システムの機能に関して不完全または誤解を招く結論につながる可能性がある。
</p>
<p>
『Could a neuroscientist understand a microprocessor? 』(2017)<br>
　(神経科学者はマイクロプロセッサを理解し得るか？)<br>
　論文は<a href="https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005268">こちら</a><br>
<br>
この影響力のある論文は、標準的な神経科学の分析手法が、既知の計算システムを正確に説明できない可能性があると論じている。
</p>

<h3>● Reward Hacking (報酬ハッキング)</h3>
<p>
『Defining and Characterizing Reward Hacking』(2022)<br>
　(報酬ハッキングの定義と特徴づけ)<br>
　論文は<a href="https://arxiv.org/abs/2209.13085">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2209.13085v2">こちら</a><br>
<br>
　強化学習における報酬ハッキングに対し、「hackability(ハッキング可能性)」と名付けられた初の正式な定義を提供した。
報酬ハッキングは、安全でアラインされた(=人間の価値観に沿った) 人工知能システムを開発する上での最も重要な課題の一つである。
AIエージェントが真の人間目標ではなく不完全な代理報酬を最適化すると、代理スコアは高くなるものの、実際の目標においては壊滅的に失敗する予期せぬ行動を発見する可能性がある。報酬ハッキングがいつ、なぜ発生するのかを理解するための初の形式的な数学的フレームワークを提供し、逸話的な証拠を超えて厳密な理論分析を行っている。
</p>
<p>
『The Effects of Reward Misspecification: Mapping and Mitigating Misaligned Models』(2022)<br>
　(報酬誤設定の影響：乖離モデルの把握と改善)<br>
　論文は<a href="https://arxiv.org/abs/2201.03544">こちら</a><br>
<br>
報酬ハッキングに特化して焦点を当てた初の査読済み研究であり、その現象の実証研究を提示していると指摘している。
</p>

<p>
『Reinforcement learning with a corrupted reward channel』(2017)<br>
　(汚染された報酬チャネルを持つ強化学習)<br>
　論文は<a href="https://arxiv.org/abs/1705.08417">こちら</a><br>
<br>
　エージェントが破損した報酬信号を受け取る状況をモデル化する形式モデルであるCorrupt Reward Markov Decision Process
（CRMDP）を導入した。
</p>

<p>
『Consequences of misaligned AI』(2021)<br>
　(不整合(人間の価値観に沿わない)AIの帰結)<br>
　論文は<a href="https://arxiv.org/abs/2102.03896">こちら</a><br>
<br>
　代理報酬関数が真の報酬の持つ特徴の一部のみを使用する場合に何が起こるかを検証した。
</p>

<p>
『Specification gaming: the flip side of AI ingenuity』(2020)<br>
　(仕様の悪用：AIの創意工夫の負の側面)<br>
　ブログは<a href="https://deepmind.google/discover/blog/specification-gaming-the-flip-side-of-ai-ingenuity/">こちら</a><br>
<br>
　（「仕様ゲーム」と称される）報酬ハッキングの豊富な事例を広範に提供している
</p>

<h3>● Scaling Law (べき則)</h3>
<p>
　『Scaling laws for neural language models』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2001.08361">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2001.08361v1">こちら</a><br>
 <br>
ディープラーニングにおけるスケーリングの予測可能性を探求し、経験的結果と性能を結びつけている。べき乗則スケーリングに関する発見にとって重要な文脈を提供している。<br>
<br>
『Deep learning scaling is predictable, empirically』(2017)<br>
　論文は<a href="https://arxiv.org/abs/1712.00409">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1712.00409v1">こちら</a><br>
<br>
「スケーリング則」を確立。言語モデルの性能が、スケール（より多くのパラメータ、データ、計算資源）の増加に伴って、滑らかに、かつ予測可能な形で向上すると予測している。<br>
<br>
　『A Universal Theorem on Learning Curves』(1993)<br>
　論文は<a href="https://bsi-ni.brain.riken.jp/database/file/134/132.pdf">こちら</a><br>
<br>
 甘利さんの論文。べき乗則の学習曲線を予測するもう1つの重要な理論論文。べき乗則の学習曲線の期待に対する理論的根拠を追加。<br>
<br>
　『Four Types of Learning Curves』(1992)<br>
　論文は<a href="https://bsi-ni.brain.riken.jp/database/file/130/128.pdf">こちら</a><br>
<br>
甘利さんの論文。統計力学的手法を使用して、汎化誤差が指数-0.5、-1、または-2のべき乗則として減少することを示している。予測される指数は経験的に観察されたものとは異なるが、べき乗則の学習曲線を期待するための理論的な基礎を築く。
</p>

<h3>● Scientific Discovery (科学的発見),  Scientific Research (科学研究)</h3>
<p>
『Virtuous Machines: Towards Artificial General Science』(2025)<br>
　(高潔な機械：汎用人工科学の実現へ)<br>
　論文は<a href="https://arxiv.org/abs/2508.13421">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2508.13421v1">こちら</a><br>
<br>
　自律的なエンドツーエンドAIシステムが、仮説の策定からデータ収集、分析、報告に至るまで、人間を被験者とする実世界の科学実験を実施し、完全な論文を生成する。
</p>

<p>
『When AI Co-Scientists Fail: SPOT-a Benchmark for Automated Verification of Scientific Research』(2025)<br>
　(AI共同研究者の失敗：科学研究の自動検証のためのベンチマークSPOT)<br>
　論文は<a href="https://arxiv.org/abs/2505.11855">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2505.11855v1">こちら</a><br>
<br>
　83の公開論文と、訂正または撤回につながった91の確認されたエラーをペアにしたベンチマークデータセットSPOTを発表した。最先端の言語モデルでさえ、科学的エラーの検出において再現率21.1%、適合率6.1%しか達成できず、自信のキャリブレーションが不十分で、ドメイン知識において学生レベルの誤解に似た間違いを犯すことが明らかになった。
</p>

<p>
『Scaling Laws of Scientific Discovery with AI and Robot Scientists』(2025)<br>
　(AIとロボット科学者による科学的発見のスケーリング則：概要)<br>
　論文は<a href="https://arxiv.org/abs/2503.22444">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2503.22444v1">こちら</a><br>
<br>
　AIとロボット工学を統合して科学研究の全ライフサイクルを自動化するシステムである、自律型汎用科学者（AGS）の概念的フレームワークを提案
</p>

<p>
『The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery』(2024)<br>
　(AI科学者：完全自動化されたオープンエンドな科学的発見に向けて)<br>
　論文は<a href="">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2408.06292v1">こちら</a><br>
<br>
　LLMを活用してアイデア創出から論文発表までの科学プロセス全体を自動化する包括的なフレームワーク「The AI Scientist」を開発した。
</p>

<h3>● Scientific Surprise</h3>
<p>
『Language Model Perplexity Predicts Scientific Surprise and Transformative Impact』(2025)<br>
　(言語モデルのパープレキシティは、科学的驚きと変革的インパクトを予測する)<br>
　論文は<a href="https://arxiv.org/abs/2509.05591">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2509.05591v1">こちら</a><br>
<br>
　科学的斬新さの代理として言語モデルの予測の失敗を利用する
</p>

<h3>● Self-Play(自己対局), Without human knowledge (人間知識なし)</h3>
<p>
『Mastering the game of go without human knowledge』(2017)<br>
　論文は<a href="https://discovery.ucl.ac.uk/id/eprint/10045895/1/agz_unformatted_nature.pdf">こちら</a>
</p>
<p>
人間データなしでの自己対局による強化学習という中核的な手法を確立した。
</p>

<h3>● Self-Replicating (自己複製)</h3>
<p>
『Frontier AI systems have surpassed the self-replicating red line』(2024)<br>
　(フロンティアAIシステムが自己複製というレッドラインを超えた)<br>
　論文は<a href="https://arxiv.org/abs/2412.12140">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2412.12140v1">こちら</a><br>
<br>
人工知能システムが自己複製する能力は、AI開発における重要な安全上の閾値、または「レッドライン」として長らく考えられてきた。AIシステムが人間の介入なしに自身の機能的なコピーを作成できる場合、制御不能な拡散を可能にし、重大な安全上の懸念を引き起こす可能性がある。主要なAI企業は、自社の主要な大規模言語モデル（LLM）は自己複製能力をほとんど示さないと公に述べているが、この見解に異議を唱えています。彼らの方法論に従うと、MetaのLlama31-70B-InstructとAlibabaのQwen25-72B-Instructという、パラメータが少なく機能が弱い人気の大規模言語モデルを搭載した2つのAIシステムが、自己複製の危険域をすでに超えていることが初めてわかった。
</p>

<h3>● Self-rewarding (自己報酬)</h3>
<p>
『Self-rewarding language models』(2024)<br>
　論文は<a href="https://arxiv.org/abs/2401.10020">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2401.10020v3">こちら</a><br>
<br>
　モデルが自身の内発的な報酬信号を提供する自己報酬という中核的な概念における、先駆的な論文。<br>
　言語モデルにおける継続学習の基盤を確立。<br>
　人間のフィードバックのボトルネックから解放されることで、モデルが「超人的なフィードバック」を達成し、さまざまな領域で人間のレベルを超えるパフォーマンスを発揮する可能性が開かれる。<br>
　とはいえ, このアプローチの長期的な持続可能性は不明瞭であり、性能が飽和したり低下したりするまでに何回のイテレーションが可能であるかは不確か。<br>
　また, 報酬ハッキングに関する重要な問題を提起している。
</p>

<h3>● Semantic hub hypothesis (意味ハブ仮説)</h3>
<p>
『The semantic hub hypothesis: Language models share semantic representations across languages and modalities.』(2024)<br>
　(意味ハブ仮説：言語モデルは多言語・多モダリティ間で意味表現を共有する)<br>
　論文は<a href="https://arxiv.org/abs/2411.04986">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2411.04986v3">こちら</a><br>
<br>
　意味的ハブ仮説は、現代の言語モデルが、その中間層において、表面的な形式にかかわらず、意味的に類似した入力が互いにクラスターを形成するような、モダリティに依存しない表現空間を学習することを提案
</p>
<p>
『Where do you know what you know? the representation of semantic knowledge in the human brain』(2007<br>
　(知識はどこに宿るのか？：ヒトの脳における意味記憶の表象)<br>
　論文は Google Scholar で検索すると pdf に辿り着ける<br>
<br>
　神経科学のこの論文は、「ハブ・アンド・スポーク」モデルを導入している。このモデルは、人間の脳における意味知識が超モダリティハブを中心に構成されていると提唱している。
</p>

<h3>● Shortcut Learning</h3>
<p>
『Shortcut Learning in Deep Neural Networks』(2020)<br>
　(深層ニューラルネットワークにおけるショートカット学習)<br>
　論文は<a href="https://arxiv.org/abs/2004.07780">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2004.07780v5">こちら</a><br>
<br>
「ショートカット学習」の概念を定義した論文。
「標準的なベンチマークではうまく機能するものの、実世界のようなより困難なテスト条件には転用できない決定ルール」を学習する現象。
トレーニングデータセットに含まれる、無関係な特徴とターゲットラベルとの間に見せかけの相関。モデルは包括的な表現を学習する代わりに、「最も簡単な」利用可能なパターンを利用するようになる。
</p>

<p>
『ImageNet-trained CNNs are biased towards texture; increasing shape bias improves accuracy and robustness』(2018)<br>
　(ImageNet学習済みCNNはテクスチャバイアスを持つ：形状バイアスを高めることで精度とロバスト性が向上する)<br>
　論文は<a href="https://arxiv.org/abs/1811.12231">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1811.12231v3">こちら</a><br>
<br>
物体認識において、深層ニューラルネットワークが物体の全体的な形状ではなく、その質感に基づいて分類することを学習することで、しばしば「近道」を取ってしまうことを示している (質感バイアス)
</p>

<h3>● Small Data</h3>
<p>
『Dark, Beyond Deep: A Paradigm Shift to Cognitive AI with Humanlike Common Sense』(2020)<br>
　(深層のその先、そして深遠なる闇へ：人間のような常識を備えた認知的AIへのパラダイムシフト)<br>
　論文は<a href="https://arxiv.org/abs/2004.09044">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2004.09044v1">こちら</a><br>
<br>
現在の「小さなタスクのためのビッグデータ」アプローチから、人間のような常識推論を重視する「大きなタスクのための小さなデータ」フレームワークへの移行を説得力のある議論で提案
</p>


<p>
『Escaping the Big Data Paradigm with Compact Transformers』(2021)<br>
　(コンパクトトランスフォーマーによるビッグデータパラダイムからの脱却)<br>
　論文は<a href="https://arxiv.org/abs/2104.05704">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2104.05704v4">こちら</a><br>
<br>
Transformerベースのモデルが小さなデータセットでもスクラッチから効果的に学習でき、最先端のCNNと同等またはそれ以上の性能を達成できることを実証した。
</p>

<h3>● Softmax Collapse</h3>
<p>
『Grokking at the Edge of Numerical Stability』(2025)<br>
　論文は<a href="https://arxiv.org/abs/2501.04697">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2501.04697v2">こちら</a><br>
<br>
　grokkingとして知られる遅延汎化現象が、Softmax関数の数値的不安定性（「Softmax Collapse」(SC)と名付けられた）と「素朴な損失最小化」(NLM: Naive Loss Minimization)と呼ばれる特定の訓練ダイナミクスによって引き起こされることを明らかにしている。StableMaxでSCを防ぐこと、または⊥GradオプティマイザでNLMを軽減することが迅速な汎化を可能にし、grokkingにおける正則化とMSE損失の役割に対する統一的な説明を提供することを示している。
</p>

<h3>● SSL: Self-Supervised Learning (自己教師あり学習)</h3>
<p>
『Dimensionality reduction by learning an invariant mapping』(2006)<br>
　論文は<a href="https://hal.science/hal-05094360/document">こちら</a><br>
<br>
　表現学習のためのコントラスト損失という概念を導入した画期的な論文
</p>
<p>
『Momentum Contrast for Unsupervised Visual Representation Learning』(2019)<br>
　論文は<a href="https://arxiv.org/abs/1911.05722">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1911.05722v3">こちら</a><br>
<br>
　自己教師あり視覚表現学習のための汎用フレームワーク Momentum Contrast を導入。
MoCo として知られる論文。
</p>
<p>
『Bootstrap your own latent: A new approach to self-supervised learning』(2020)<br>
　論文は<a href="">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2006.07733v3">こちら</a><br>
<br>
　ネガティブサンプルを用いることなく表現学習を行うために、モーメンタムエンコーダを備えた教師-生徒フレームワークを使用。BYOLとして知られる論文。
</p>
<p>
『Emerging properties in self-supervised vision transformers』(2021)<br>
　論文は<a href="https://arxiv.org/abs/2104.14294">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2104.14294v2">こちら</a><br>
<br>
　学生-教師フレームワークを普及させた、基盤となる自己教師あり学習手法であるDINO(DIstillation with NO labels)を導入している。
</p>
<p>
 『Understanding contrastive representation learning through alignment and uniformity on the hypersphere』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2005.10242">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2005.10242v10">こちら</a><br>
<br>
　自己教師あり表現を評価するためのアライメントと均一性という指標を導入した基礎論文   
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

<h3>● Symbol Grounding (記号接地)</h3>
<p>
『The symbol grounding problem』(1990)<br>
　論文は<a href="https://arxiv.org/html/cs/9906002">こちら</a><br>
<br>
「記号接地問題」――すなわち抽象的な記号を知覚的な意味に結びつけるという根本的な課題――を定義した基礎的な論文
</p>

<h3>● Syntax Dependencies (統語的依存関係)</h3>
<p>
『Assessing the Ability of LSTMs to Learn Syntax-Sensitive Dependencies』
　(LSTMの統語的に敏感な依存関係学習能力の評価)<br>
　論文はこちら, 要約はこちら<br>
<br>
　LSTMsが文法的な依存関係を学習できるかを評価するために用いられる主語と動詞の一致タスクを導入した、記念碑的な論文
</p>


<h3>● Task Arithmetic (タスク算術)</h3>
<p>
『Editing Models with Task Arithmetic』(2022)<br>
　論文は<a href="https://arxiv.org/abs/2212.04089">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2212.04089v3">こちら</a><br>
<br>
「タスク算術」という中核的なモデル融合概念を導入した基礎研究。
ファインチューニングされたモデルの重みと事前学習済みの初期化との差が、タスク固有の知識をエンコードするベクトルとして扱えることを示している。   
</p>

<h3>● Technical Debt (技術的負債)</h3>
<p>
『Hidden technical debt in Machine learning systems』(2015)<br>
　(機械学習システムにおける隠れた技術的負債)<br>
　論文は<a href="https://proceedings.neurips.cc/paper_files/paper/2015/file/86df7dcfd896fcaf2674f757a2463eba-Paper.pdf">こちら</a><br>
<br>
技術的負債というソフトウェアエンジニアリングのフレームワークを用いることで、現実世界の機械学習システムでは、莫大な継続的な保守コストが発生することを示した。
</p>

<p>
『Towards AI-Native Software Engineering (SE 3.0): A Vision and a Challenge Roadmap』(2024)<br>
　(AIネイティブなソフトウェア工学（SE 3.0）へ：展望と課題ロードマップ)<br>
　論文は<a href="https://arxiv.org/abs/2410.06107">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2410.06107v1">こちら</a><br>
<br>
　現在のAI支援アプローチを超えるAIネイティブなソフトウェア開発のビジョンであるソフトウェアエンジニアリング3.0を提案。
</p>

<h3>● ToM: Theory of Mind (心の理論)</h3>
<p>
『Does the chimpanzee have a theory of mind? 』(1978)<br>
　(チンパンジーは心の理論を持つか?)<br>
　論文は Google Scholarで検索すると pdf に辿り着ける<br>
<br>
　「心の理論」(ToM) の概念を導入した画期的な論文
</p>

『Towards Cognitive Synergy in LLM-Based Multi-Agent Systems: Integrating Theory of Mind and Critical Evaluation』(2025)<br>
　(LLMベースのマルチエージェントシステムにおける認知的相乗効果に向けて：心の理論と批判的評価の統合)<br>
<br>
　論文は<a href="https://arxiv.org/abs/2507.21969">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2507.21969v1">こちら</a><br>
<br>

現在のLLMベースのマルチエージェントシステムにおける根本的な限界、すなわち、人間のような協調的知能を達成できないという問題に取り組んでいます。

LLMベースのマルチエージェントシステムにおける広範な研究に基づいており、動的な心の理論（ToM）と構造化された批判的評価という2つの重要な認知メカニズムを導入しています。
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

<h3>●VAE: Variational Auto Encoder</h3>
<p>
『Auto-Encoding Variational Bayes』(2013)<br>
　(オートエンコーディング変分ベイズ)<br>
　論文は<a href="https://arxiv.org/abs/1312.6114">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1809.01999v1">こちら</a><br>
<br>
　連続潜在変数を持つ有向確率モデルにおける効率的な推論と学習のために、リパラメトリゼーショントリックを特徴とする自己符号化変分ベイズ（AEVB）アルゴリズムを導入した。このアプローチにより、変分自己符号化器（VAE）が生まれ、生成モデルの堅牢な学習、効果的な周辺尤度推定、およびデータ生成のための構造化された潜在表現の学習能力が実証された。
</p>

<p>
『Stochastic Variational Inference』(2012)<br>
　(確率的変分推論)<br>
　論文は<a href="https://arxiv.org/abs/1206.7051">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1206.7051v3">こちら</a><br>
<br>
　確率的変分推論（SVI）の現代的な枠組みを確立した
</p>

<h3>● Vanishing gradient problems (勾配消失問題), gradient exploding  problems (勾配爆発問題)</h3>
<p>
　『Learning long-term dependencies with gradient descent is difficult』(1994)<br>
　論文は<a href="https://www.comp.hkbu.edu.hk/~markus/teaching/comp7650/tnn-94-gradient.pdf">こちら</a><br>
<br>
　勾配消失問題と勾配爆発問題という課題を初めて詳細に特定し、分析した基礎的な論文    
</p>

<h3>● Variable-Binding (変数束縛), VSA: Vector Symbolic Architectures </h3>
<p>
『Connectionism and cognitive architecture: A critical analysis』(1988)<br>
　(コネクショニズムと認知アーキテクチャ：批判的分析)<br>
　論文は<a href="https://uh.edu/~garson/F&P1.PDF">こちら</a><br>
<br>
　ニューラルネットワークが記号計算と人間の認知の重要な特徴である「変数束縛」を扱えないことを批判した。<br>
<br>
※ 例えば「Xは人間である」のような命題論理では, X に具体的な値
(例えばソクラテス)をバインドすることで推論が可能になる。
逆にバインドできなければ抽象的なルールを具体的な事例に適用できない。
このように、variable binding は「抽象的な知識を具体的な事例に適用するための橋渡し」のような役割を果たす。
</p>

<p>
『How Do Transformers Learn Variable Binding in Symbolic Programs?』(2025)<br>
　(Transformerはどのようにして記号プログラムにおける変数束縛を学習するのか？)<br>
　論文は<a href="https://arxiv.org/abs/2505.20896">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2505.20896v1">こちら</a><br>
<br>
　Transformerが変数バインディングを、明示的なアーキテクチャサポートなしに学習できることを示しており、ニューラルネットワークがパターン認識に限定されるという概念に異議を唱えている
</p>

<p>
『Developing a Foundation of Vector Symbolic Architectures Using Category Theory』
　(圏論を用いたベクトル記号アーキテクチャの基盤構築)<br>
　論文は<ahref="https://arxiv.org/abs/2501.05368">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2501.05368v2">こちら</a><br>
<br>
　圏論を用いてベクトル記号アーキテクチャ (VSA) のための基礎的な数学的枠組みを確立している。VSAの最適な結合およびバンドル操作が要素ごとの乗算と加算であることを厳密に導出し、多くの既存のVSA実装に理論的な正当性を提供するとともに、新しいアーキテクチャの原則に基づいた設計を可能にする。
</p>
     
<p>
『Discovering variable binding circuitry with desiderata』(2023)<br>
　(Desiderataによる変数結合回路の発見)<br>
　論文は<a href="https://arxiv.org/abs/2307.03637">こちら</a><br>
<br>
</p>

<p>
『Holographic reduced representations』(1995)
　(ホログラフィック縮約表現)<br>
　論文は<a href="https://pages.ucsd.edu/~msereno/_170_2006/readings/06-Holographic.pdf">こちら</a><br>
<br>
　代表的かつ影響力のあるVSA（Vector Symbolic Architectures）であるホログラフィック縮小表現 (HRR) を導入
</p>

<p>
『Tensor product variable binding and the representation of symbolic structures in connectionist systems』(1990)<br>
　(テンソル積変数束縛およびコネクショニストシステムにおける記号構造の表現)<br>
　論文は<a href="http://www.lscp.net/persons/dupoux/teaching/AT1_2012/papers/Smolensky_1990_TensorProductVariableBinding.AI.pdf">こちら</a><br>
<br>
　テンソル積表現（TPR）を導入。シンボル構造をニューラルネットで表現するために、テンソル積を使って「ロール」と「フィラー」を結びつける手法で, 最初のVSA。
</p>

<h3>● Visual Planning (視覚計画)</h3>
<p>
『Visual Planning: Let’s Think Only with Images』(2025)<br>
　(ビジュアルプランニング：画像だけで考えよう)<br>
　論文は<a href="https://arxiv.org/abs/2505.11409">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2505.11409v1">こちら</a>, ChatPaperは<a href="https://chatpaper.com/ja/paper/137226">こちら</a><br>
<br>
　テキストに依存せず、純粋な視覚表現を通じて計画を可能にする新しいパラダイム「視覚計画」を提案する。このパラダイムでは、計画は視覚領域における段階的推論を符号化した画像のシーケンスを介して実行され、人間が未来の行動をスケッチまたは視覚化する方法に類似している。
</p>
<p>
『Mental rotation of three-dimensional objects』(1971)<br>
　(立体の心的回転)<br>
　論文は<a href="https://facultypsy.hope.edu/psychlabs/exp/rotate/readings/ShepardMetzler_1971.pdf">こちら</a>, 機械翻訳は<a href="https://boyoyon.github.io/HTMLs_translated_to_Japanese/1971_Mental%20Rotation%20of%20Three-Dimensional%20Objects/Mental%20Rotation%20of%20Three-Dimensional%20Objects.html">こちら</a><br>
<br>
　メンタルイメージに関する画期的な論文。人間は推論のために簡略化された視覚的手がかりを精神的に構築し、操作する。
</p>

<h3>● Weak-to-strong generalization (弱から強への一般化)</h3>
<p>
『Weak-to-strong generalization: Eliciting strong capabilities with weak supervision』(2023)<br>
　(弱から強への一般化：弱い教師あり学習で強い能力を引き出す)<br>
　論文は<a href="https://arxiv.org/abs/2312.09390">こちら</a><br>
<br>
　弱い教師あり学習の下で、強力な生徒が弱い教師よりも優れた性能を発揮できる、弱から強への汎化という概念を初めて導入した。
</p>
<center><img src="images/weak-to-strong.png"></center>

<h3>● Word Embeddings (単語埋め込み) </h3>
<p>
『Unsupervised word embeddings capture latent knowledge from materials science literature』(2019)<br>
　(材料科学文献から潜在的知識を抽出する教師なし単語埋め込み)<br>
　論文は<a href="https://escholarship.org/content/qt082091b4/qt082091b4_noSplash_ddb3beb657d7f25dd560454fe4eccf99.pdf">こちら</a><br>
<br>
　単語埋め込みモデルがテキストから複雑な材料科学の概念を自律的に学習できることを実証した画期的な論文
</p>

<h3>● World Model</h3>
<p>
『Making the world differentiable』(1990)<br>
　論文は<a href="https://people.idsia.ch/~juergen/FKI-126-90_(revised)bw_ocr.pdf">こちら</a><br>
<br>
　RNN を予測的な世界モデルとして訓練する「コントローラー–モデル(C–M)アーキテクチャ」を最初に提案した論文のひとつ
</p>
<p>
『World models』(2018)<br>
　論文は<a href="https://arxiv.org/abs/1803.10122">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1803.10122v4">こちら</a><br>
<br>
　生成ニューラルネットワーク (VAEとMDN-RNN) を用いて環境の圧縮された予測モデルを学習し、効率的なエージェント制御を促進する。
</p>
<center><img src="images/world_model.png"></center>
<p>
『Recurrent world models facilitate policy evolution』(2018)<br>
　論文は<a href="https://arxiv.org/abs/1809.01999">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/1809.01999v1">こちら</a><br>
<br>
「ワールドモデル」の概念を定義した初期の研究の一つ。
</p>
<p>
『General agents need world models』()<br>
　(汎用エージェントは世界モデルを必要とする)<br>
　論文は<a href="https://arxiv.org/abs/2506.01622">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2506.01622v2">こちら</a><br>
<br>
　Google DeepMindによるこの研究は、多段階の目標指向タスクを確実に達成できるあらゆる人工エージェントが、その環境の正確な予測モデルを学習している必要があることを形式的に証明している。
</p>
<p>
『What Has a Foundation Model Found? Using Inductive Bias to Probe for World Models』(2025)<br>
　(基盤モデルは何を見出したのか？ 帰納バイアスを用いて世界モデルを探る)<br>
　論文は<a href="https://arxiv.org/abs/2507.06952">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/2507.06952v2">こちら</a><br>
<br>
　基盤モデルが真に根底にある「世界モデル」を学習しているのか、それとも単によく予測するだけなのかを評価するために「帰納バイアスプローブ」を導入している。この結果、これらのモデルは予測に優れている一方で、物理学、格子問題、ゲームの各ドメインにおいて、根本的な支配原理ではなく、タスク固有のヒューリスティックや粗い表現を学習していることが一貫して示され、真の世界モデルに対する帰納バイアスが弱いことが明らかになった。
</p>
    </body>
</html>
