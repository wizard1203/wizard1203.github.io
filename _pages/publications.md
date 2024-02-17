---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


<!-- # Machine Learning and Deep Learning -->

* **Z. Tang**, Y. Zhang, S. Shi, X. Tian, T. Liu, B. Han, X. Chu. FedImpro: Measuring and Improving Client Update in Federated Learning. In ICLR 2024.


* Y. Wang, Y. Chen, Z. Li, **Z. Tang**, R. Guo, X. Wang, Q. Wang, AC Zhou, X. Chu. Towards Efficient and Reliable LLM Serving: A Real-World Workload Study. arXiv preprint arXiv:2401.17644.


* Y. Wang, S. Shi, X. He, **Z. Tang**, X. Pan, Y. Zheng, X. Wu, AC Zhou, B. He, X. Chu. Reliable and Efficient In-Memory Fault Tolerance of Large Language Model Pretraining. arXiv preprint arXiv:2310.12670.


* **Z. Tang**, Yuxin Wang, Xin He, Longteng Zhang, Xinglin Pan, Qiang Wang, Rongfei Zeng, Kaiyong Zhao, Shaohuai Shi, Bingsheng He, Xiaowen Chu. \textbf{FusionAI: Decentralized Training and Deploying LLMs with Massive Consumer-Level GPUs}. In IJCAI-LLM Workshop 2023.09., Y. Wang, X. He, L. Zhang, X. Pan, Q. Wang, R. Zeng, K. Zhao, S. Shi, B. He, X. Chu. FusionAI: Decentralized Training and Deploying LLMs with Massive Consumer-Level GPUs. In IJCAI-LLM Workshop 2023.09.

* **Z. Tang**, S. Shi, B. Li, X. Chu. GossipFL: A Decentralized Federated Learning Framework with Sparsified and Adaptive Communication. In IEEE Transactions on Parallel and Distributed Systems, 2022.


* X. He , J. Yao, Y. Wang, **Z. Tang**, C. K. Chun, S. Simon, B. Han, and X. Chu. NAS-LID: Efficient Neural Architecture Search with Local Intrinsic Dimension. In AAAI 2023.

* **Z. Tang\***, Y. Zhang\*, S. Shi, X. He, B. Han, X. Chu. Virtual Homogeneity Learning: Defending against Data Heterogeneity in Federated Learning. In Proceedings of the 39th International Conference on Machine Learning, 2022.

* C. He, A. D. Shah, **Zhenheng Tang**, D. Fan, A. N. Sivashunmugam, K. Bhogaraju, M. Shimpi, L. Shen, X. Chu, M. Soltanolkotabi and S. Avestimehr. FedCV: A Federated Learning Framework for Diverse Computer Vision Tasks. In FL-AAAI-22 workshop, 2022. [Best Paper Award]
* Z. Liao, H. Yan, **Z. Tang**, X. Chu, T. Tao. Deep learning identifies leak in water pipeline system using transient frequency response. In Process Safety and Environmental Protection 2021.


* **Z. Tang**, Zhikai Hu, Shaohuai Shi, Yiu-ming Cheung, Yilun Jin, Zhenghang Ren, Xiaowen Chu. \textbf{Data Resampling for Federated Learning with Non-IID Labels. In FTL-IJCAI workshop, 2021.

* S. Shi, **Z. Tang**, X. Chu, C. Liu, W. Wang, and B. Li. A quantitative surveyof communication optimizations in distributed deep learning. IEEE Network,35(3):230–237, 2021.

* S. Shi, **Z. Tang**, Q. Wang, K. Zhao, and X. Chu. Layer-wise adaptive gradientsparsification for distributed deep learning with convergence guarantees. In ECAI 2020 * 24th European Conference on Artificial Intelligence, pages 1467–1474. IOS Press, 2020.

* **Z. Tang**, S. Shi, and X. Chu. Communication-efficient decentralized learning withsparsification and adaptive peer selection. In ICDCS 2020.

* Y. Wang, Q. Wang, S. Shi, X. He, **Z. Tang**, K. Zhao, X. Chu. Benchmarking the Performance and Energy Efficiency of AI Accelerators for AI Training. In CCGRID 2020.

* **Z. Tang**, Y. Wang, Q. Wang, and X. Chu. The impact of gpu dvfs on the energy andperformance of deep learning: An empirical study. In Proceedings of the Tenth ACM International Conference on Future Energy Systems, e-Energy ’19.

* S. Shi, K. Zhao, Q. Wang, **Z. Tang**, and X. Chu.  A convergence analysis ofdistributed sgd with communication-efficient gradient sparsification. IJCAI-19.

* S. Shi, Q. Wang, K. Zhao, **Z. Tang**, Y. Wang, X. Huang, and X. Chu. A distributedsynchronous sgd algorithm with global top-k sparsification for low bandwidthnetworks. In ICDCS 2019.


* X. Zhou, **Z. Tang**, W. Xu, F. Meng, X. Chu, K. Xin, and G. Fu. Deep learningidentifies accurate burst locations in water distribution networks. Water Research,166:115058, 2019.

* X. He, S. Wang, S. Shi, **Z. Tang**, Y. Wang, Z. Zhao, J. Dai, R. Ni, X. Zhang, X. Liu,Z. Wu, W. Yu, and X. Chu. Computer-aided clinical skin disease diagnosis usingcnn and object detection models. In 2019 IEEE International Conference on BigData (Big Data), pages 4839–4844, 2019.


# Preprint

* **Z. Tang**, X. Chu, R. Ran, S. Lee, S. Shi, Y. Zhang, Y. Wang, A. Liang, S. Avestimehr, C. He. FedML Parrot: A Scalable Federated Learning System via Heterogeneity-aware Scheduling on Sequential and Hierarchical Training. arXiv preprint arXiv:2303.01778.

* **Z. Tang**, S. Shi, X. Chu, W. Wang, and B. Li. Communication-efficient distributeddeep learning: A comprehensive survey. CoRR, abs/2003.06307, 2020.





{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
