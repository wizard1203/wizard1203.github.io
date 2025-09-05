---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm a Post-doctoral Researcher at [The Hong Kong University of Science and Technology](https://hkust.edu.hk/) under supervision of [Prof. Bo Li](https://www.cse.ust.hk/~bli/) and [Prof. Xiaowen Chu](https://sites.google.com/view/chuxiaowen). 
Previously, I obtained my PhD degree of Computer Science from [Hong Kong Baptist University](https://www.hkbu.edu.hk) under the supervision of [Prof. Xiaowen Chu](https://sites.google.com/view/chuxiaowen) and [Prof. Amelie Chi Zhou](https://www.comp.hkbu.edu.hk/~amelieczhou/), and co-supervised by [Prof. Bo Han](https://bhanml.github.io/). Before that, I got my Bachelor degree from [HUST](https://www.hust.edu.cn/).

<!-- Hi! This year, I'm expected to graduate as a Computer Science PhD in [Hong Kong Baptist University](https://www.hkbu.edu.hk) under the supervision of [Prof. Xiaowen Chu](https://sites.google.com/view/chuxiaowen) and [Prof. Amelie Chi Zhou](https://www.comp.hkbu.edu.hk/~amelieczhou/), and co-supervised by [Prof. Bo Han](https://bhanml.github.io/). After PhD journey, I'm going to work as a Postdoctoral Fellow in HKUST under supervision of [Prof. Bo Li](https://www.cse.ust.hk/~bli/) and [Prof. Xiaowen Chu](https://sites.google.com/view/chuxiaowen). Before HKBU, I got my Bachelor degree of HUST. -->


**Research Interests**
I am interested in undersanding how deep learning models are optimized and how they learn knowledge and do reasoning. In next at least one year, I will delve into studying LLM reasoning mechanisms, agent workflow, fast finetuning and inference, and some practical LLMs' applications in CS or other areas in which knowledge can be conveniently represented digitally.

<!-- workflow -->

<!-- With better understanding and interpretation, I devote to design high-performance, privacy preserved and trustworthy ML algorithms and systems.  -->
<!-- 
* Training: ML optimizer, Distributed training (and federated learning), HPO, ML-system co-designs, Fault-tolerance training.
* Inference: Memory saving, Model compression, MoE routing, Accelerating LLM inference (both edge and server).
* Understanding Deep Learning/LLM: How model/LLM is trained, how knowledge is stored in the model/LLM, how knowledge is retrieved from the model/LLM.
* Data-centric: RAG, Dataset selection, Data quality, Data generation.
* LLM privacy: Privacy preserved inference.  -->

I'm open for academic collaborations. If you are interested, please feel free to contact me.

<!-- Democratizing large deep learning models needs high efficiency, scalability, robustness and privacy. Achieving these goals needs to understand *both ML and systems* at first. To this end, I'm studying following aspects:

* Training: ML optimizer, Distributed training (and federated learning), HPO, ML-system co-designs, Fault-tolerance training.
* Inference: Memory saving, Model compression, MoE routing, Accelerating LLM inference (both edge and server).
* Understanding Deep Learning/LLM: How model/LLM is trained, how knowledge is stored in the model/LLM, how knowledge is retrieved from the model/LLM.
* Data-centric: RAG, Dataset selection, Data quality, Data generation.
* LLM privacy: Privacy preserved inference. -->


# 🔥 News
[See all news items](/news)


* [2025.07] &nbsp;🎉🎉 One paper is accepted at <strong><font color=red>COLM 2025</font></strong>.
* [2025.06] &nbsp;🎉🎉 One paper is accepted at <strong><font color=red>ACL 2025 Findings</font></strong>.
* [2025.05] &nbsp;🎉🎉 One paper is accepted at <strong><font color=red>ICML 2025</font></strong> and four papers are accepted at <strong><font color=red>ICML Workshop 2025</font></strong>.
* [2025.01] &nbsp;🎉🎉 Our paper "Hot-pluggable Federated Learning: Briding General and 
Personalized FL via Dynamic Selection" is selected at <strong><font color=red>ICLR 2025</font></strong>. This paper proposes a selective federated learning approach to integate 
personalized modules into general federated learning. ([Paper](https://openreview.net/
forum?id=B8akWa62Da))
* [2025.01] &nbsp;🎉🎉 Our paper "STBLLM: Breaking the 1-Bit Barrier with Structured 
Binary LLMs" is selected at <strong><font color=red>ICLR 2025</font></strong>. This 
paper introduces STBLLM, a novel approach that breaks the 1-bit barrier in language 
models by leveraging Structured Binary LLMs. ([Paper](https://openreview.net/forum?
id=6XUSDvBFkV))
* [2025.01] &nbsp;🎉🎉 Our paper "The Lottery LLM Hypothesis, Rethinking What Abilities 
Should LLM Compression Preserve?" is selected as <strong><font color=red>ICLR Blogpost 
2025</font></strong>. This blog proposes a lottery LLM hypothesis suggesting that for a 
given LLM and task, there exists a smaller lottery LLM capable of producing the same 
performance with the original LLM with the assistances of multi-step reasoning and 
external tools. ([Paper](https://openreview.net/forum?id=Vq3noyDfJI))
* [2025.01] &nbsp;🎉🎉 Our paper "Can LLM Simulations Truly Reflect Humanity? A Deep 
Dive." is selected as <strong><font color=red>ICLR Blogpost 2025</font></strong>. This 
blog rethinks LLM-based simulations by emphasizing both their limitations and the 
necessities for advancing LLM simulations. It offer actionable insights and strategies 
for enhancing the applicability of LLM simulations in human society in the future. 
([Paper](https://openreview.net/forum?id=dMrhmQdrdW))
* [2025.01] &nbsp;🎉🎉 Our paper "ParZC: Parametric Zero-Cost Proxies for Efficient NAS.
" is selected at <strong><font color=red>AAAI 2025</font></strong> for <strong><font 
color=red>Oral Presentation</font></strong>!
* [2024.12] &nbsp;🎉🎉 Our paper "ParZC: Parametric Zero-Cost Proxies for Efficient NAS.
" is accepted at <strong><font color=red>AAAI 2025</font></strong>! Parametric Zero-Cost 
Proxies (ParZC) method improves zero-shot Neural Architecture Search by addressing 
unequal node importance and using novel techniques for uncertainty estimation and 
architecture ranking. ([paper]() and [codes]() will come soon...)
* [2024.11] &nbsp;🎉🎉 I'm selected as the <strong><font color=red>Top Reviewer of 
NeurIPS 2024</font></strong> for both main and D&B tracks ([Link](https://nips.cc/
Conferences/2024/ProgramCommittee#top-reviewers)).
* [2024.10] &nbsp;🎉🎉 Our paper "Hot Pluggable Federated Learning." has been selected 
by the FL@FM-NeurIPS'24 workshop to receive the <strong><font color=red>Outstanding 
Student Paper Award</font></strong>!. Congratulations to all co-authors!
* [2024.10] &nbsp;🎉🎉 Our paper "FSMoE: A Flexible and Scalable Training System for 
Sparse Mixture-of-Experts Models." is accepted In <strong><font color=red>ASPLOS 2025</font></strong>! In this paper, we design and implement a new training system modularizes 
various operators in the entire MoE model, providing more fine-grained computation and 
communication scheduling, and achieving better computation communication overlap through 
appropriate gradient segmentation.. ([paper]() and [codes]() will come soon...)
* [2024.09] &nbsp;🎉🎉 Our paper "Hot Pluggable Federated Learning." is accepted at 
Workshop Federated Foundation Models@NeurIPS 2024  as an <strong><font color=red>Oral</font></strong> paper!. In this paper, we propose a new method to regard model heads as 
pluggable modules appended after the model backbone. ([paper]() and [codes]() will come 
soon...)
* [2024.09] &nbsp;🎉🎉 Our paper "FuseFL: One-Shot Federated Learning through the Lens 
of Causality with Progressive Model Fusion." is accepted at <strong><font 
color=red>NeurIPS 2024 as a Spotlight</font></strong> paper ! This work identifies the 
cause of low performance of one-shot FL, and proposes FuseFL to progressively train and 
fuses DNN model following a bottom-up manner, reducing communication costs to an 
extremely low degree. ([paper]() and [codes]() will come soon...)
* [2024.09] &nbsp;🎉🎉 Our paper "Discovering Sparsity Allocation for Layer-wise Pruning 
of Large Language Models." is accepted at <strong><font color=red>NeurIPS 2024</font></
strong>. In this paper, we present a new method for optimizing layerwise sparsity 
allocation in large language models. ([paper]() and [codes]() will come soon...)
* [2024.09] &nbsp;🎉🎉 Our paper "Should We Really Edit Language Models? On the 
Evaluation of Edited Language Models." is accepted at <strong><font color=red>NeurIPS 
2024</font></strong>. In this paper, we benchmark the methods of editing LLMs and see 
how they influence LLM performance. ([paper]() and [codes]() will come soon...)

## 📖 Educations
- *2020.09 - 2024.08*, Hong Kong Baptist University, PhD in Computer Science
- *2014.09 - 2018.06*, Huazhong University of Science and Technology, Bachelor in Telecommunications Engineering。

## 💻 Work & Research Experience 
* 09/2024-present: PostDoc Researcher, The Hong Kong University of Science and Technology, advised by [Prof. Bo Li](https://www.cse.ust.hk/~bli/) and [Prof. Xiaowen Chu](https://sites.google.com/view/chuxiaowen).
* 09/2023-08/2024: Visiting Researcher, The Hong Kong University of Science and Technology (Guangzhou), advised by [Prof. Xiaowen Chu](https://sites.google.com/view/chuxiaowen).
* 02/2023-05/2023: Visiting Researcher, National University of Singapore, advised by [Prof. Bingsheng He](https://www.comp.nus.edu.sg/~hebs/).
* 06/2022-10/2022: Research Intern, [FedML Inc](https://www.fedml.ai/), advised by [Dr. Chaoyang He](https://chaoyanghe.com/).
* 10/2018-09/2020: Research Assistant, Hong Kong Baptist University, advised by [Prof. Xiaowen Chu](https://sites.google.com/view/chuxiaowen).





# 📝 Selected Publications 
[See full publication list](/publications) and Google Scholar [link](https://scholar.google.com/citations?user=DhtAFkwAAAAJ&hl=en).

The \* represents equal contribution, 📧 corresponding author.

* Q. Wang, Z. Lou, **Z. Tang**, N. Chen, X. Zhao, W. Zhang, D. Song, B. He. Assessing Judging Bias in Large Reasoning Models: An Empirical Study. In COLM 2025.

* Y. Zhu\*, **Z. Tang**\*, X. Liu, A. Li, B. Li, X. Chu, B. Han. OracleKV: Oracle Guidance for Question-Independent KV Cache Eviction. ICML 2025 Workshop LCFM. (<strong>Oral</strong>)

* Q. Wang\*, **Z. Tang**\*, Z. Jiang, N. Chen, T. Wang, B. He. AgentTaxo: Dissecting and Benchmarking Token Distribution of LLM Multi-Agent Systems. ICML 2025 Workshop MAS.

* F. Wei\*, **Z. Tang**\*, R. Zeng, T. Liu, C. Zhang, X. Chu, B. Han. JailbreakLoRA: Your Downloaded LoRA from Sharing Platforms might be Unsafe. In ICML Workshop DIG-BUG 2025.

* Z. Tang\*, **Z. Tang**\*, G. Pan, B. Liu, K. Lai, X. Chu, B. Li. Ghost in the Cloud: Your Geo-Distributed Large Language Models Training is Easily Manipulated. In ICML Workshop DIG-BUG 2025.

* P. Dong\*, **Z. Tang**\*, X. Liu, L. Li, X. Chu, Bo Li. Can Compressed LLMs Truly Act? An Empirical Evaluation of Agentic Capabilities in LLM Compression. In ICML 2025.

* Q. Wang, T. Wang, **Z. Tang**, Q. Li, N. Chen, J. Liang, B. He. MegaAgent: A Large-Scale Autonomous LLM-based Multi-Agent System Without Predefined SOPs. In ACL 2025 Findings.


* K. Lai\*, **Z. Tang**\*, X. Pan, P. Dong, X. Liu, H. Chen, L. Shen, B. Li, X. Chu. Mediator: Memory-efficient LLM Merging with Less Parameter Conflicts and Uncertainty Based Routing. Arxiv 2025.

* X. Liu\*, **Z. Tang**\*, P. Dong, Z. Li, B. Li, X. Hu, X. Chu. ChunkKV: Semantic-Preserving KV Cache Compression for Efficient Long-Context LLM Inference. Arxiv 2025.

* X. Liu, **Z. Tang**, H. Chen, P. Dong, Z. Li, X. Zhou, B. Li, X. Hu, X. Chu. Can LLMs Maintain Fundamental Abilities under KV Cache Compression? Arxiv 2025.

* L. Shen\*, **Z. Tang**\*, L. Wu, Y. Zhang, X. Chu, T. Qin, B. Han. Hot-pluggable Federated Learning: briding General and Personalized FL via Dynamic Selection. In ICLR 2025.

* **Z. Tang**, X. Liu, Q. Wang, P. Dong, B. He, X. Chu, B. Li. The Lottery LLM Hypothesis, Rethinking What Abilities Should LLM Compression Preserve? ICLR Blogpost Track 2025.

* Q. Wang, **Z. Tang**, B. He. Can LLM Simulations Truly Reflect Humanity? A Deep Dive. ICLR Blogpost Track 2025.

* P. Dong, L. Li, Y. Zhong, D. Du, R. Fan, Y. Chen, **Z. Tang**, Q. Wang, W. Xue, Y. Guo, X. Chu. STBLLM: Breaking the 1-Bit Barrier with Structured Binary LLMs. In ICLR 2025.


* P. Dong, L. Li, **Z. Tang**, X. Liu, Z. Wei, Q. Wang, X. Chu. ParZC: Parametric Zero-Cost Proxies for Efficient NAS. In AAAI 2025.

* X. Pan, W. Lin, L. Zhang, S. Shi, **Z. Tang**, R. Wang, B. Li, X. Chu. FSMoE: A Flexible and Scalable Training System for Sparse Mixture-of-Experts Models. In ASPLOS 2025.

* **Z. Tang**, Y. Zhang, P. Dong, Y. Cheung, A. C. Zhou, B. Han, X. Chu. FuseFL: One-Shot Federated Learning through the Lens of Causality with Progressive Model Fusion." In NeurIPS 2024 (<strong>SPOTLIGHT</strong>).

* L. Shen\*, **Z. Tang**\*💡 , L. Wu, Y. Zhang, X. Chu, T. Qin, B. Han. "Hot Pluggable Federated Learning." In Workshop of Federated Foundation Models@NeurIPS 2024 (<strong>Oral</strong>, <strong>Outstanding Student Paper Award</strong>).

* L. Li, P. Dong, **Z. Tang**, X. Liu, Q. Wang, W. Luo, W. Xue, Q. Liu, X. Chu, Y. Guo. Discovering Sparsity Allocation for Layer-wise Pruning of Large Language Models. In NeurIPS 2024.

* Q. Li, X. Liu, **Z. Tang**, P. Dong, Z. Li, X. Pan, X. Chu. Should We Really Edit Language Models? On the Evaluation of Edited Language Models. In NeurIPS 2024.

* Z. Tang, J. Huang, R. Yan, Y. Wang, **Z. Tang**💡📧, S. Shi, A. C. Zhou, X. Chu📧. Bandwidth-Aware and Overlap-Weighted Compression for Communication-Efficient Federated Learning. In ICPP 2024.

* P. Dong, L. Li, **Z. Tang**, X. Liu, X. Pan, Q. Wang, X. Chu📧. Evolving Symbolic Pruning Metric From Scratch for Large Language Models. In ICML 2024.

* **Z. Tang**, Y. Zhang, S. Shi, X. Tian, T. Liu, B. Han, X.📧 Chu. FedImpro: Measuring and Improving Client Update in Federated Learning. In ICLR 2024.


* Y. Wang, Y. Chen, Z. Li, **Z. Tang**, R. Guo, X. Wang, Q. Wang, AC Zhou, X. Chu📧. BurstGPT: A Real-world Workload Dataset to Optimize LLM Serving Systems. arXiv preprint arXiv:2401.17644.


* Y. Wang, S. Shi, X. He, **Z. Tang**, X. Pan, Y. Zheng, X. Wu, AC Zhou, B. He, X. Chu📧. Reliable and Efficient In-Memory Fault Tolerance of Large Language Model Pretraining. arXiv preprint arXiv:2310.12670.


* **Z. Tang**, Y. Wang, X. He, L. Zhang, X. Pan, Q. Wang, R. Zeng, K. Zhao, S. Shi📧, B. He, X. Chu📧. FusionAI: Decentralized Training and Deploying LLMs with Massive Consumer-Level GPUs. In IJCAI-LLM Workshop 2023.09., 

* **Z. Tang**, S. Shi, B. Li, X. Chu📧. GossipFL: A Decentralized Federated Learning Framework with Sparsified and Adaptive Communication. In IEEE Transactions on Parallel and Distributed Systems, 2022.


* **Z. Tang**, Y. Zhang\*, S. Shi, X. He, B. Han, X. Chu📧. Virtual Homogeneity Learning: Defending against Data Heterogeneity in Federated Learning. In Proceedings of the 39th International Conference on Machine Learning, 2022.

* C. He, A. D. Shah, **Z. Tang**, D. Fan, A. N. Sivashunmugam, K. Bhogaraju, M. Shimpi, L. Shen, X. Chu, M. Soltanolkotabi and S. Avestimehr. FedCV: A Federated Learning Framework for Diverse Computer Vision Tasks. In FL-AAAI-22 workshop, 2022.


* **Z. Tang**, Zhikai Hu, Shaohuai Shi, Yiu-ming Cheung, Yilun Jin, Zhenghang Ren, Xiaowen Chu📧. Data Resampling for Federated Learning with Non-IID Labels. In FTL-IJCAI workshop, 2021.


* **Z. Tang**, S. Shi, and X. Chu📧. Communication-efficient decentralized learning withsparsification and adaptive peer selection. In ICDCS 2020.


* **Z. Tang**, Y. Wang, Q. Wang, and X. Chu. The impact of gpu dvfs on the energy andperformance of deep learning: An empirical study. In Proceedings of the Tenth ACM International Conference on Future Energy Systems, e-Energy '19.


* **Z. Tang**, X. Chu, R. Ran, S. Lee, S. Shi, Y. Zhang, Y. Wang, A. Liang, S. Avestimehr, C. He📧. FedML Parrot: A Scalable Federated Learning System via Heterogeneity-aware Scheduling on Sequential and Hierarchical Training. arXiv preprint arXiv:2303.01778.

* **Z. Tang**, S. Shi, W. Wang, B. Li and X. Chu📧. Communication-efficient distributeddeep learning: A comprehensive survey. CoRR, abs/2003.06307, 2020.




# 👔 Professional Activities
* Invited Area Chair:
    * NeurIPS 2025

* Invited Program Committee Member (Reviewer):
    * Machine Learning: KDD'23, ICML'22,23,24,25, NeurIPS'22,23,24, ICLR'23,24,25,26, AAAI'23,25, AISTATS'23'25, UAI'22, IJCAI-ECAI'22, COLM'25, ACL'25, EMNLP'25.
    * Networking & Systems: HPCC'21, ICDCS'22,23, ICPADS'22, IWQOS'23,24.

* Invited Reviewer for Journals
    * Machine Learning: 
        * IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
        * Transactions on Machine Learning Research (TMLR)
        * IEEE Transactions on Neural Networks and Learning Systems (TNNS)
        * Journal of Artificial Intelligence Research (JAIR)
    * Networking & Systems:
        * ACM Transactions on Architecture and Code Optimization (TACO)
        * IEEE Transactions on Parallel and Distributed Systems (TPDS)
        * IEEE Journal on Selected Areas in Communications (JSAC)
        * IEEE Network Magzines
        * IEEE Transactions on Networking (ToN)
        * IEEE Transactions on Network Science and Engineering (TNSE)
        * IEEE Transactions on Intelligent Systems and Technology (TIST)
        * IEEE Computational Intelligence Magazine
        * Journal of Parallel and Distributed Computing (JPDC)
    * General:
        * ACM Computing Surveys




# 🎖 Honors and Awards


* 2023/24 Fall, Research Performance Award, HKBU CS Department ([Link](https://www.comp.hkbu.edu.hk/v1/?pid=48)).
* 2024, NeurIPS Top Reviewer ([Link](https://nips.cc/Conferences/2024/ProgramCommittee#top-reviewers)).
* 2024, Outstanding Student Paper Award of FL@FM-NeurIPS'24 workshop.
* 2024, NeurIPS Scholar Award. 
* 2024, ICLR Scholar Award. 
* 2023/24 Spring, Research Performance Award, HKBU CS Department ([Link](https://www.comp.hkbu.edu.hk/v1/?pid=48)).
* 2022/23, Research Performance Award, HKBU CS Department ([Link](https://www.comp.hkbu.edu.hk/v1/?pid=48)).
* 2022/23 Fall, Teaching Performance Award, HKBU CS Department ([Link](https://www.comp.hkbu.edu.hk/v1/?pid=48)).
* 2021/22, Research Performance Award, HKBU CS Department ([Link](https://www.comp.hkbu.edu.hk/v1/?pid=48)).
* 2021/22 Fall, Teaching Performance Award, HKBU CS Department ([Link](https://www.comp.hkbu.edu.hk/v1/?pid=48)).
* 2020, Scholarship for Nominees of Hong Kong PhD Fellowship Scheme, HKBU CS Department ([Link](https://www.comp.hkbu.edu.hk/v1/?pid=48)).
* 2018, Outstanding Graduate, HUST
* 2016, Scholarship of Academic Excellence, HUST



<!-- # 🎤 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->






# 📕 Teaching
* Teaching Assistant at HKBU
    * 2023 Spring Semester, COMP7940 Cloud Computing
    * 2022 Fall Semester, COMP7015 Artiﬁcial Intelligence 
    * 2022 Spring Semester, COMP 7550 IT Project Management
    * 2021 Fall Semester, COMP 7015, Artificial Intelligence
    * 2021 Spring Semester, COMP 7930, Big Data Analytics





# 🛠️ Projects 
- [FedCV](https://github.com/FedML-AI/FedML)
<img src="https://img.shields.io/github/stars/FedML-AI/FedML?color=yellow&label=Star" alt="Stars" >
- [FedML Parrot](https://github.com/FedML-AI/FedML)
<img src="https://img.shields.io/github/stars/FedML-AI/FedML?color=yellow&label=Star" alt="Stars" >
- [FedImpro](https://github.com/wizard1203/FedImpro)
<img src="https://img.shields.io/github/stars/wizard1203/FedImpro?color=yellow&label=Star" alt="Stars" >
- [Pruner-Zero (LLM pruning)](https://github.com/pprp/Pruner-Zero)
<img src="https://img.shields.io/github/stars/pprp/Pruner-Zero?color=yellow&label=Star" alt="Stars" >
- [Virtual Homogeneity Learning](https://github.com/wizard1203/VHL)
<img src="https://img.shields.io/github/stars/wizard1203/VHL?color=yellow&label=Star" alt="Stars" >
- [G-TopK S-SGD](https://github.com/hclhkbu/gtopkssgd)
<img src="https://img.shields.io/github/stars/hclhkbu/gtopkssgd?color=yellow&label=Star" alt="Stars" >
- [GossipFL](https://github.com/wizard1203/GossipFL)
<img src="https://img.shields.io/github/stars/wizard1203/GossipFL?color=yellow&label=Star" alt="Stars" >
- [Fully-linear DenseNet](https://github.com/wizard1203/waternn)
<img src="https://img.shields.io/github/stars/wizard1203/waternn?color=yellow&label=Star" alt="Stars" >



# 🎥 Videos
Some videos and articles that I think are very profound.

【80岁老人分享他们人生中最大的遗憾】 https://www.bilibili.com/video/BV1bGthzXEAB/?share_source=copy_web&vd_source=4c597ac434557f6d100f2f904035d775





<!-- # 📚 Resources -->







<!-- 
[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun -->

<!-- 
[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->



<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=pd4PWlhO8snuZVDPncMjkvKKyv494Zg_6KY07jDtkhI&cl=ffffff&w=a"></script>














