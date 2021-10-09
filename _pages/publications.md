---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

# Machine Learning and Deep Learning

* S. Shi, **Z. Tang**, X. Chu, C. Liu, W. Wang, and B. Li. A quantitative surveyof communication optimizations in distributed deep learning.IEEE Network,35(3):230–237, 2021.

* S. Shi, **Z. Tang**, Q. Wang, K. Zhao, and X. Chu. Layer-wise adaptive gradientsparsification for distributed deep learning with convergence guarantees. In ECAI 2020 - 24th European Conference on Artificial Intelligence, pages 1467–1474. IOS Press, 2020.


* **Z. Tang**, S. Shi, and X. Chu. Communication-efficient decentralized learning withsparsification and adaptive peer selection. In40th IEEE International Conference onDistributed Computing Systems, ICDCS 2020, Singapore, November 29 - December1, 2020, pages 1207–1208. IEEE, 2020.


* **Z. Tang**, Y. Wang, Q. Wang, and X. Chu. The impact of gpu dvfs on the energy andperformance of deep learning: An empirical study. InProceedings of the Tenth ACMInternational Conference on Future Energy Systems, e-Energy ’19, page 315–325,New York, NY, USA, 2019. Association for Computing Machinery.

* S. Shi, K. Zhao, Q. Wang, **Z. Tang**, and X. Chu.  A convergence analysis ofdistributed sgd with communication-efficient gradient sparsification. InProceedingsof the Twenty-Eighth International Joint Conference on Artificial Intelligence,IJCAI-19, pages 3411–3417. International Joint Conferences on Artificial IntelligenceOrganization, 7 2019.

* S. Shi, Q. Wang, K. Zhao, **Z. Tang**, Y. Wang, X. Huang, and X. Chu. A distributedsynchronous sgd algorithm with global top-k sparsification for low bandwidthnetworks. In 2019 IEEE 39th International Conference on Distributed ComputingSystems (ICDCS), pages 2238–2247, 2019.


* X. Zhou, **Z. Tang**, W. Xu, F. Meng, X. Chu, K. Xin, and G. Fu. Deep learningidentifies accurate burst locations in water distribution networks. Water Research,166:115058, 2019.

* X. He, S. Wang, S. Shi, **Z. Tang**, Y. Wang, Z. Zhao, J. Dai, R. Ni, X. Zhang, X. Liu,Z. Wu, W. Yu, and X. Chu. Computer-aided clinical skin disease diagnosis usingcnn and object detection models. In 2019 IEEE International Conference on BigData (Big Data), pages 4839–4844, 2019.


# Preprint
* **Z. Tang**, S. Shi, X. Chu, W. Wang, and B. Li. Communication-efficient distributeddeep learning: A comprehensive survey.CoRR, abs/2003.06307, 2020.





{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
