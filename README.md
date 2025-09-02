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
<h3>● CoT (Chain-of-Thought 思考連鎖)</h3>
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

<h3>● Grokking</h3>
<p>
『Grokking: Generalization beyond overfitting on small algorithmic datasets』(2022)<br>
　論文は<a href="https://arxiv.org/abs/2201.02177">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/2201.02177v1">こちら</a>, 機械翻訳は<a href="https://boyoyon.github.io/HTMLs_translated_to_Japanese/2022_GROKKING%20-%20GENERALIZATION%20BEYOND%20OVERFITTING%20ON%20SMALL%20ALGORITHMIC%20DATASETS/GROKKING%20-%20GENERALIZATION%20BEYOND%20OVERFITTING%20ON%20SMALL%20ALGORITHMIC%20DATASETS.html">こちら</a>
</p>
<p>
最初に「グロッキング」現象を発見し、命名し、調査した論文
</p>

<h3>● Knowledge Distillation (知識蒸留)</h3>
<p>
『Distilling the knowledge in a neural network』(2015)<br>
　論文は<a href="https://arxiv.org/abs/1503.02531">こちら</a>, 要約は<a href="https://www.alphaxiv.org/ja/overview/1503.02531v1">こちら</a>
</p>
<p>
より小さな「生徒」ネットワークがより大きな「教師」ネットワークから学習するという、知識蒸留（KD）の概念を導入した基礎となる論文。<br>
蒸留のインスピレーションはお酒かと思ったら昆虫で, 「教師」が「幼虫」. 「生徒」が「成虫」というのも意外･･･
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
→ 大きなモデルの中に当りくじモデルが含まれている?<br>

</p>

<h3>● Neural Collapse </h3>
<p>
『Prevalence of neural collapse during the terminal phase of deep learning training』(2020)<br>
　論文は<a href="https://arxiv.org/abs/2008.08186">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/2008.08186v2">こちら</a>
</p>
<p>
最初に「ニューラルコラプス」（NC）現象を観察、命名し、包括的に文書化した画期的な論文
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

<h3>● Primacy Bias (プライマシーバイアス, 初頭バイアス)</h3>
<p>
『The role of first impression in operant learning』(2012)<br>
　論文は<a href="https://loewenstein.huji.ac.il/sites/default/files/yonatanloewenstein/files/2012-23008-001_2013.pdf">こちら</a>
</p>
<p>
「Primacy Bias」の概念的起源と命名法を提供している<br>
AIモデルを継続学習する場合, 課題になる。
</p>

<h3>● Pruning (枝刈り)</h3>
<p>
『Optimal Brain Damage』(1989)<br>
　論文は<a href="https://proceedings.neurips.cc/paper/1989/file/6c9882bbac1c7093bd25041881277658-Paper.pdf">こちら</a>
</p>
<p>
タイトル(最適脳損傷)が怖い･･･
</p>

<h3>● Self-Play(自己対局), Without human knowledge (人間知識なし)</h3>
<p>
『Mastering the game of go without human knowledge』(2017)<br>
　論文は<a href="https://discovery.ucl.ac.uk/id/eprint/10045895/1/agz_unformatted_nature.pdf">こちら</a>
</p>
<p>
人間データなしでの自己対局による強化学習という中核的な手法を確立した。
</p>

<h3>● Transformer</h3>
<p>
『Attention is all you need』(2017) <br>
　論文は<a href="https://arxiv.org/abs/1706.03762">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/1706.03762v7">こちら</a>
</p>
<p>
Transformerアーキテクチャを導入した。
</p>

<h3>● World Model</h3>
<p>
『Recurrent world models facilitate policy evolution』(2018)<br>
　論文は<a href="https://arxiv.org/abs/1809.01999">こちら</a>,　要約は<a href="https://www.alphaxiv.org/ja/overview/1809.01999v1">こちら</a>
</p>
<p>
「ワールドモデル」の概念を定義した初期の研究の一つ。
</p>
    </body>
</html>









