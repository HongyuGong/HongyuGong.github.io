---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

(\* denotes equal contribution)

## Preprint

* [Adaptive Sparse Transformer for Multilingual Translation](https://arxiv.org/pdf/2104.07358.pdf) <br>
<b>Hongyu Gong</b>, Xian Li, Dmitriy Genzel. <br>

* [LAWDR: Language-Agnostic Weighted Document Representations from Pre-trained Models](https://arxiv.org/pdf/2106.03379.pdf) <br>
<b>Hongyu Gong</b>, Vishrav Chaudhary, Yuqing Tang, Francisco Guzmán. <br>

* [From Solving a Problem Boldly to Cutting the Gordian Knot: Idiomatic Text Generation](https://arxiv.org/pdf/2104.06541.pdf) <br>
Jianing Zhou, <b>Hongyu Gong</b>, Srihari Nanniyur, Suma Bhat. <br>


## 2023

* [SpeechMatrix: A Large-Scale Mined Corpus of Multilingual Speech-to-Speech Translations](https://arxiv.org/abs/2211.04508) <br>
Paul-Ambroise Duquenne\*, <b>Hongyu Gong\*</b>, Ning Dong, Jingfei Du, Ann Lee, Vedanuj Goswani, Changhan Wang, Juan Pino, Benoît Sagot, Holger Schwenk. <br>
In <i>The 61st Annual Meeting of the Association for Computational Linguistics</i> (ACL 2023).

* [Pre-training for Speech Translation: CTC Meets Optimal Transport](https://arxiv.org/abs/2301.11716) <br>
Phuong-Hang Le, <b>Hongyu Gong</b>, Changhan Wang, Juan Pino, Benjamin Lecouteux, Didier Schwab. <br>
In <i>2023 International Conference on Machine Learning</i> (ICML 2023).

* [Speech-to-Speech Translation For A Real-world Unwritten Language](https://arxiv.org/abs/2211.06474) <br>
Peng-Jen Chen, Kevin Tran, Yilin Yang, Jingfei Du, Justine Kao, Yu-An Chung, Paden Tomasello, Paul-Ambroise Duquenne, Holger Schwenk, <b>Hongyu Gong</b>, Hirofumi Inaguma, Sravya Popuri, Changhan Wang, Juan Pino, Wei-Ning Hsu, Ann Lee. <br>
In <i> Findings of the Association for Computational Linguistics</i> (ACL Findings 2023).

* [Improving Speech-to-Speech Translation Through Unlabeled Text](https://arxiv.org/abs/2210.14514) <br>
Xuan-Phi Nguyen, Sravya Popuri, Changhan Wang, Yun Tang, Ilia Kulikov, <b>Hongyu Gong</b>. <br>
In <i>IEEE International Conference on Acoustics, Speech, and Signal Processing</i> (ICASSP 2023).

* [Named Entity Detection and Injection for Direct Speech Translation](https://arxiv.org/abs/2210.11981) <br>
Marco Gaido, Yun Tang, Ilia Kulikov, Rongqing Huang, <b>Hongyu Gong</b>, Hirofumi Inaguma. <br>
In <i>IEEE International Conference on Acoustics, Speech, and Signal Processing</i> (ICASSP 2023).

* [A Holistic Cascade System, benchmark, and Human Evaluation Protocol for Expressive Speech-to-Speech Translation](https://arxiv.org/abs/2301.10606)
Wen-Chin Huang, Benjamin Peloquin, Justine Kao, Changhan Wang, <b>Hongyu Gong</b>, Elizabeth Salesky, Yossi Adi, Ann Lee, Peng-Jen Chen. <br>
In <i>IEEE International Conference on Acoustics, Speech, and Signal Processing</i> (ICASSP 2023).

## 2022

* [T-Modules: Translation Modules for Zero-Shot Cross-Modal Machine Translation](https://arxiv.org/abs/2205.12216) <br>
Paul-Ambroise Duquenne, <b>Hongyu Gong</b>, Benoît Sagot, Holger Schwenk. <br> 
In <i>Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing (EMNLP)</i> (EMNLP 2022).

* [Unified Speech-Text Pre-training for Speech Translation and Recognition](https://aclanthology.org/2022.acl-long.105/) <br>
Yun Tang, <b>Hongyu Gong</b>, Ning Dong, Changhan Wang, Wei-Ning Hsu, Jiatao Gu, Alexei Baevski, Xian Li, Abdelrahman Mohamed, Michael Auli, Juan Pino. <br>
In <i>Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics </i> (ACL 2022).

* [Textless Speech-to-Speech Translation on Real Data](https://aclanthology.org/2022.naacl-main.63/) <br>
Ann Lee, <b>Hongyu Gong</b>, Paul-Ambroise Duquenne, Holger Schwenk, Peng-Jen Chen, Changhan Wang, Sravya Popuri, Yossi Adi, Juan Pino, Jiatao Gu, Wei-Ning Hsu <br>
In <i>Proceedings of NAACL-HLT 2022 </i>.

* [Idiomatic Expression Paraphrasing without Strong Supervision](https://ojs.aaai.org/index.php/AAAI/article/view/21433) <br>
Jianing Zhou, Ziheng Zeng, <b>Hongyu Gong</b>, Suma Bhat. <br>
In <i>Proceedings of the AAAI Conference on Artificial Intelligence 2022</i> (AAAI 2022).

* [Contrastive Clustering to Mine Pseudo Parallel Data for Unsupervised Translation](https://openreview.net/forum?id=pN1JOdrSY9) <br>
Xuan-Phi Nguyen, <b>Hongyu Gong</b>, Yun Tang, Changhan Wang, Philipp Koehn, Shafiq Joty. <br>
In <i>International Conference on Learning Representations 2022</i> (ICLR 2022).

* [Incremental Speech Synthesis For Speech-To-Speech Translation](https://arxiv.org/abs/2110.08214) <br>
Danni Liu, Changhan Wang, <b>Hongyu Gong</b>, Xutai Ma, Yun Tang, Juan Pino. <br>
In <i>Interspeech 2022</i>.


## 2021

* [Pay Better Attention to Attention: Head Selection in Multilingual and Multi-Domain Sequence Modeling](https://arxiv.org/pdf/2106.10840v1.pdf) <br>
<b>Hongyu Gong</b>, Yun Tang, Juan Pino, Xian Li. <br> 
In <i>Advances in Neural Information Processing Systems</i> (NeurIPS 2021).

* [Multimodal and Multilingual Em- beddings for Large-Scale Speech Mining]() <br>
Paul-Ambroise Duquenne, <b>Hongyu Gong</b> and Holger Schwenk. <br>
In <i>Advances in Neural Information Processing Systems</i> (NeurIPS 2021).

* [Robust Optimization for Multilingual Translation with Imbalanced Data](https://arxiv.org/pdf/2104.07639.pdf) <br>
Xian Li, <b>Hongyu Gong</b>. <br>
In <i>Advances in Neural Information Processing Systems</i> (NeurIPS 2021).

* [Abusive Language Detection in Heterogeneous Contexts: Dataset Collection and the Role of Supervised Attention](https://arxiv.org/pdf/2105.11119.pdf) <br>
<b>Hongyu Gong</b>, Alberto Valido Delgado, Katherine Ingram, Giulia Fanti, Suma Bhat and Dorothy Espelage. <br>
In <i> AAAI 2021 (AI for Social Impact track)</i>.

* [Self-Supervised Euphemism Detection and Identification for Content Moderation](https://arxiv.org/abs/2103.16808) <br>
Wanzheng Zhu, <b>Hongyu Gong</b>, Rohan Bansal, Zachary Weinberg, Nicolas Christin, Giulia Fanti and Suma Bhat. <br>
Accepted by <i> IEEE Symposium on Security and Privacy 2021</i>.

* [FST: the FAIR Speech Translation System for the IWSLT21 Multilingual Shared Task](https://aclanthology.org/2021.iwslt-1.14/) <br>
Yun Tang\*, <b>Hongyu Gong\*</b>, Xian Li, Changhan Wang, Juan Pino, Holger Schwenk, Naman Goyal. <br>
In <i>Proceedings of the 18th International Conference on Spoken Language Translation</i> (IWSLT 2021). <br>

* [WikiMatrix: Mining 135M Parallel Sentences in 1620 Language Pairs from Wikipedia](https://www.aclweb.org/anthology/2021.eacl-main.115/) <br>
Holger Schwenk, Vishrav Chaudhary, Shuo Sun, <b>Hongyu Gong</b>, Francisco Guzmán. <br>
In <i>Proceedings of the 16th Conference of the European Chapter of the Association for Computational Linguistics</i> (EACL 2021). <br>

* [PIE: Parallel Idiomatic Expression Corpus for Idiomatic Sentence Generation and Paraphrasing]() <br>
Jianing Zhou, <b>Hongyu Gong</b> and Suma Bhat. <br>
In <i>the 17th Workshop on Multiword Expressions</i> (ACL Workshop 2021). <br>

## 2020

* [Recurrent Chunking Mechanisms for Long-Text Machine Reading Comprehension](https://www.aclweb.org/anthology/2020.acl-main.603/) <br>
<b>Hongyu Gong</b>, Yelong Shen, Dian Yu, Jianshu Chen and Dong Yu. <br>
In <i>Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics</i> (ACL 2020). <br>
[slides](https://github.com/HongyuGong/HongyuGong.github.io/blob/master/files/acl2020.pptx)

* [Enriching Word Embeddings with Temporal and Spatial Information](https://arxiv.org/abs/2010.00761) <br>
<b>Hongyu Gong</b>, Suma Bhat and Pramod Viswanath. <br>
In <i>The SIGNLL Conference on Computational Natural Language Learning</i> (CoNLL 2020). <br>
[slides](https://github.com/HongyuGong/HongyuGong.github.io/blob/master/files/conll2020_slides.pptx)

* [Rich Syntactic and Semantic Information Helps Unsupervised Text Style Transfer](https://aclanthology.org/2020.inlg-1.17/) <br>
<b>Hongyu Gong</b>, Linfeng Song, and Suma Bhat. <br>
In <i>International Conference on Natural Language Generation </i> (INLG 2020).

* [IlliniMet: Illinois System for Metaphor Detection with Contextual and Linguistic Information](https://www.aclweb.org/anthology/2020.figlang-1.21/) <br>
<b>Hongyu Gong</b>, Kshitij Gupta, Akriti Jain and Suma Bhat. <br>
In <i>Proceedings of the Second Workshop on Figurative Language Processing</i> (Fig-Lang@ACL 2020).

* [FUSE: Multi-Faceted Set Expansion by Coherent Clustering of Skip-grams](https://arxiv.org/abs/1910.04345) <br>
Wanzheng Zhu, <b>Hongyu Gong</b>, Jiaming Shen, Chao Zhang, Jingbo Shang, Suma Bhat Jiawei Han <br>
In <i>The European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD 2020)<i>.


## 2019
* [PaRe: A Paper-Reviewer Matching Approach Using a Common Topic Space](https://www.aclweb.org/anthology/D19-1049.pdf) <br>
Omer Anjum\*, <b>Hongyu Gong\*</b>, Suma Bhat, Jinjun Xiong and Wen-mei Hwu. <br>
In <i>Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing</i> (EMNLP 2019).

* [Reinforcement Learning Based Text Style Transfer without Parallel Training Corpus](https://arxiv.org/pdf/1903.10671.pdf) <br>
<b>Hongyu Gong</b>, Suma Bhat, Lingfei Wu, Jinjun Xiong and Wen-mei Hwu. <br>
In <i>Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies</i> (NAACL 2019). <br>
[slides](https://github.com/HongyuGong/HongyuGong.github.io/blob/master/files/naacl_slides.pptx)

* [Context-Sensitive Malicious Spelling Error Correction](https://arxiv.org/pdf/1901.07688.pdf) <br>
<b>Hongyu Gong</b>, Yuchen Li, Suma Bhat and Pramod Viswanath. <br>
In <i>World Wide Web Conference</i> (WWW 2019).

* [Equipping Educational Applications with Domain Knowledge](https://www.aclweb.org/anthology/W19-4448.pdf) <br>
Tarek Sakakini, <b>Hongyu Gong</b>, Jong Yoon Lee, Robert Schloss, Jinjun Xiong and Suma Bhat. <br>
In <i>Proceedings of the Fourteenth Workshop on Innovative Use of NLP for Building Educational Applications</i> (ACL Workshop 2019).

## 2018
* [Preposition Sense Disambiguation and Representation](https://www.aclweb.org/anthology/D18-1180.pdf) <br>
<b>Hongyu Gong</b>, Jiaqi Mu, Suma Bhat and Pramod Viswanath. <br>
In <i>Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing</i> (EMNLP 2018).

* [Document Similarity for Texts of Varying Lengths via Hidden Topics](https://arxiv.org/pdf/1903.10675.pdf) <br>
<b>Hongyu Gong</b>, Tarek Sakakini, Suma Bhat and Jinjun Xiong. <br>
In <i>Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics</i> (ACL 2018).

* [Embedding Syntax and Semantics of Prepositions via Tensor Decomposition](https://www.aclweb.org/anthology/N18-1082.pdf) <br>
<b>Hongyu Gong</b>, Suma Bhat and Pramod Viswanath. <br>
In <i>Proceedings of the 16th Annual Conference of the North American Chapter of the Association for Computational Linguistics</i>, (NAACL 2018).

## 2017
* [Geometry of Compositionality](https://arxiv.org/pdf/1611.09799.pdf) <br>
<b>Hongyu Gong</b>, Suma Bhat and Pramod Viswanath. <br>
In <i>Proceedings of the Thirty-First Conference on Artificial Intelligence</i>, (AAAI 2017).

* [Distributed Multicast Tree Construction in Wireless Sensor Networks](https://ieeexplore.ieee.org/abstract/document/7725956) <br>
<b>Hongyu Gong</b>, Luoyi Fu, Xinzhe Fu, Lutian Zhao, Kainan Wang and Xinbing Wang. <br>
In <i>IEEE Transactions on Information Theory</i>, 2017.

## 2015
* [A Distributed Algorithm to Construct Multicast Trees in WSNs: An Approximate Steiner Tree Approach](https://dl.acm.org/doi/10.1145/2746285.2746296) <br>
<b>Hongyu Gong</b>, Lutian Zhao, Kainan Wang, Xinbing Wang, and Weijie Wu. <br>
In <i>Proceedings of the 16th ACM International Symposium on Mobile Ad Hoc Networking and Computing</i>, (MobiHoc 2015).

* [A Distributed Algorithm to Construct Multicast Trees in Wireless Multi-hop Networks](https://ieeexplore.ieee.org/document/7249345) <br>
<b>Hongyu Gong</b>, Lutian Zhao, Kainan Wang, Weijie Wu and Xinbing Wang. <br>
In <i>IEEE International Conference on Communications</i>, (ICC 2015)
