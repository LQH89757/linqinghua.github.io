
# 📝 Publications 
## 🎙 Image Segmentation


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EAAI 2023</div><img src='images/DeepCrackAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DeepCrackAT: An effective crack segmentation framework based on learning multi-scale crack features](https://papers.nips.cc/paper/DeepCrackAT.pdf) \\
**Qinghua Lin**, Wei Li, Xiangpan Zheng, Haoyi Fan, Zuoyong Li

[**Project**](https://github.com/AlchemyEmperor/DeepCrackAT) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- We propose a deep crack convolutional network, named DeepCrackAT, which utilizes an Attention mechanism to fuse multi-scale features from convolution and Tokenized MLP for crack segmentation.
- For irregularly distributed cracks, we use the hybrid dilated convolutions to increase the receptive field of convolutional operations and capture more crack features. Additionally, the proposed method employs a tokenized multilayer perceptron to project high-dimensional crack features into a low dimension space, enhancing the network’s ability of noise resistance.
- We introduce the convolutional block attention module to construct an attentional skip-layer fusion block for multi-scale feature fusion. This helps to enhance the network’s perception of the critical crack region and alleviate the problem of information loss in thick crack segmentation.
</div>
</div>

## 🎙 Image Classification
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA 2024</div><img src='images/FireMatch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ FireMatch: A semi-supervised video fire detection network based on consistency and distribution alignment](https://arxiv.org/abs/2006.04558) \\
**Qinghua Lin**, Zuoyong Li, Kun Zeng, Haoyi Fan, Wei Li, Xiaoguang Zhou

[**Project**](https://speechresearch.github.io/fastspeech2/) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong>
- To fully leverage unlabeled data, we extend consistency regularization with a self-adaptive pseudo-label to the video classification field. Generating enough high-quality pseudo-label data for training helps the model achieve accurate fire video classification.
- For addressing the problem of imbalanced labeled and unlabeled data leading to mismatched sampling experiences, we propose video cross-set sample augmentation combined with adversarial distribution alignment to generate additional labeled samples and alleviate this bias.
- We conduct extensive experiments and ablation studies on public datasets and compare our method with state-of-the-art semi supervised methods. The experimental results demonstrate the effectiveness of the proposed method.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ESWA 2024</div><img src='images/ReCLR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Leukocyte classification using relative-relationship-guided contrastive learning](https://arxiv.org/abs/2006.04558) \\
Zuoyong Li, **Qinghua Lin**, Jiawei Wu, Taotao Lai, Rongteng Wu, David Zhang

[**Project**](https://github.com/AlchemyEmperor/ReCLR) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:LkGwnXOMwfcC'></span></strong>
- We introduce the heuristic-guided strategy of contrastive learning, which provides positive and negative samples based on relative distance knowledge. This strategy addresses the bottleneck of contrast views in contrast learning resulting from different classes being sensitive to different data expansions.
- We propose a Relative-Relationship-Guided Contrastive Learning Representation (ReCLR) framework for the leukocyte classification, which introduces the prior distance knowledge to mine positive pairs with the adversarial relative relationship and negative pairs with entropy constraint.
- We conduct extensive experiments and compare ReCLR with several state-of-the-art methods on real leukocyte datasets. The results show that our method achieves better classification performance in different evaluation protocols, including linear evaluation, domain transfer, and finetuning, which shows the effectiveness of proposed method.
</div>
</div>


## 🧑‍🎨 Generative Model


## Others
- `NeurIPS 2023` [Unsupervised Video Domain Adaptation for Action Recognition: A Disentanglement Perspective](https://openreview.net/forum?id=Rp4PA0ez0m), Pengfei Wei, Lingdong Kong, Xinghua Qu, **Yi Ren**, et al.
- ``ACM-MM 2022`` [Video-Guided Curriculum Learning for Spoken Video Grounding](), Yan Xia, Zhou Zhao, Shangwei Ye, Yang Zhao, Haoyuan Li, **Yi Ren**
