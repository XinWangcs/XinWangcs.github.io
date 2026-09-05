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


You can find all my papers on my [Google Scholar](https://scholar.google.com/citations?user=K9-1BcQAAAAJ)

---
(*: corresponding author)

<!--
## LLM Reasoning and Adaptation

*Methods for improving how large language models reason and adapt, so they learn efficiently, reason reliably, and generalize across tasks and domains.*

- **Mental-R1: Aligning LLM Reasoning for Mental Health Assessment.**  
 **Xin Wang**, Boyan Gao, Yibo Yang, David A Clifton  
Preprint, arXiv:2606.13176 [[pdf](http://arxiv.org/abs/2606.13176)]

- **Optimization-Inspired Few-Shot Adaptation for Large Language Models.**  
Boyan Gao, **Xin Wang**, Yibo Yang, David A Clifton  
Advances in Neural Information Processing Systems (**NeurIPS 2025, Spotlight**) [[pdf](https://arxiv.org/abs/2505.19107)]


## AI for Mental Health

*AI methods for understanding mental health from language, image, and behavioral signals, spanning representation learning, stress detection, fine-grained categorization, and stressor identification.*

- **MISE: Meta-knowledge Inheritance for Social Media-Based Stressor Estimation.**  
 **Xin Wang**, Ling Feng, Huijun Zhang, Lei Cao, Kaisheng Zeng, Qi Li, Yang Ding, Yi Dai, David A Clifton  
Proceedings of the ACM Web Conference (**WWW 2025, Oral**) [[pdf](https://arxiv.org/abs/2505.03827)][[code](https://github.com/xin-wang18/MISE)][[data](https://www.kaggle.com/datasets/xinwangcs/stressor-cause-of-mental-health-problem-dataset)]

- **Contrastive Learning of Stress-specific Word Embedding for Social Media-based Stress Detection.**  
 **Xin Wang**, Huijun Zhang, Lei Cao, Kaisheng Zeng, Qi Li, Ningyun Li, Ling Feng  
Proceedings of the ACM SIGKDD Conference on Knowledge Discovery and Data Mining (**KDD 2023**) [[pdf](https://dl.acm.org/doi/pdf/10.1145/3580305.3599795)][[code](https://github.com/xin-wang18/SSE)][[data](https://github.com/xin-wang18/SSE)]

- **A Meta-learning based Stress Category Detection Framework on Social Media.**  
 **Xin Wang**, Lei Cao, Huijun Zhang, Ling Feng, Yang Ding, Ningyun Li  
Proceedings of the ACM Web Conference (**WWW 2022**) [[pdf](https://dl.acm.org/doi/pdf/10.1145/3485447.3512013)][[data](https://github.com/xin-wang18/Categroy-Dataset)]

- **Integrating Content-Semantics-World Knowledge to Detect Stress from Videos.**  
Yang Ding, Yi Dai, **Xin Wang\***, Ling Feng\*, Lei Cao, Huijun Zhang  
Proceedings of the ACM International Conference on Multimedia (**MM 2024**) [[pdf](https://dl.acm.org/doi/pdf/10.1145/3664647.3680584)]

- **Leverage Social Media for Personalized Stress Detection.**  
 **Xin Wang**, Huijun Zhang, Lei Cao, Ling Feng  
Proceedings of the ACM International Conference on Multimedia (**MM 2020**) [[pdf](https://dl.acm.org/doi/pdf/10.1145/3394171.3413596)]

## AI for Biomedicine

*AI methods for biomedical discovery, spanning multimodal representation learning, knowledge graph reasoning, and predictive modeling for biological interactions and cold-start settings.*

- **IPM-DTI: An Interaction-Pattern-Driven Multimodal Framework for Drug–Target Interaction Prediction via Knowledge Graphs.**  
Yao Liu, Yifei Zhou, **Xin Wang**, Lei Zhao  
Journal of Chemical Information and Modeling (**JCIM 2026**) [[pdf](https://pubs.acs.org/doi/10.1021/acs.jcim.6c00740)]

- **MuRL-DTI: A Multimodal Feature Fusion Reinforcement Learning Approach for Cold Start in Drug–Target Interactions.**  
Yao Liu, **Xin Wang**, Ye Liu, Dandan Dou  
IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP 2025**) [[pdf](https://ieeexplore.ieee.org/abstract/document/10888048)]

- **SAGS-DynamicBio: Integrating Semantic-Aware and Graph Structure-Aware Embedding for Dynamic Biological Data with Knowledge Graphs.**  
Yao Liu, Yongfei Zhang, **Xin Wang**  
European Conference on Machine Learning and Knowledge Discovery in Databases (**ECML PKDD 2024**) [[pdf](https://dl.acm.org/doi/10.1007/978-3-031-70378-2_18)]

-->

## Publications

- **Mental-R1: Aligning LLM Reasoning for Mental Health Assessment.**  
**Xin Wang**, Boyan Gao, Yibo Yang, David A. Clifton  
Preprint, arXiv:2606.13176 [[pdf](http://arxiv.org/abs/2606.13176)]

- **Optimization-Inspired Few-Shot Adaptation for Large Language Models.**  
Boyan Gao, **Xin Wang**, Yibo Yang, David A. Clifton  
Advances in Neural Information Processing Systems (**NeurIPS 2025, Spotlight**) **[CORE A\* · CCF A]** [[pdf](https://arxiv.org/abs/2505.19107)]

- **MISE: Meta-knowledge Inheritance for Social Media-Based Stressor Estimation.**  
**Xin Wang**, Ling Feng, Huijun Zhang, Lei Cao, Kaisheng Zeng, Qi Li, Yang Ding, Yi Dai, David A. Clifton  
Proceedings of the ACM Web Conference (**WWW 2025, Oral**) **[CORE A\* · CCF A]** [[pdf](https://arxiv.org/abs/2505.03827)] [[code](https://github.com/xin-wang18/MISE)] [[data](https://www.kaggle.com/datasets/xinwangcs/stressor-cause-of-mental-health-problem-dataset)]

- **MuRL-DTI: A Multimodal Feature Fusion Reinforcement Learning Approach for Cold Start in Drug–Target Interactions.**  
Yao Liu, **Xin Wang**, Ye Liu, Dandan Dou  
IEEE International Conference on Acoustics, Speech, and Signal Processing (**ICASSP 2025**) **[CORE B · CCF B]** [[pdf](https://ieeexplore.ieee.org/abstract/document/10888048)]

- **Integrating Content-Semantics-World Knowledge to Detect Stress from Videos.**  
Yang Ding, Yi Dai, **Xin Wang\***, Ling Feng\*, Lei Cao, Huijun Zhang  
Proceedings of the ACM International Conference on Multimedia (**MM 2024**) **[CORE A\* · CCF A]** [[pdf](https://dl.acm.org/doi/pdf/10.1145/3664647.3680584)]

- **SAGS-DynamicBio: Integrating Semantic-Aware and Graph Structure-Aware Embedding for Dynamic Biological Data with Knowledge Graphs.**  
Yao Liu, Yongfei Zhang, **Xin Wang**  
European Conference on Machine Learning and Knowledge Discovery in Databases (**ECML PKDD 2024**) **[CORE A · CCF B]** [[pdf](https://dl.acm.org/doi/10.1007/978-3-031-70378-2_18)]

- **Contrastive Learning of Stress-specific Word Embedding for Social Media-based Stress Detection.**  
**Xin Wang**, Huijun Zhang, Lei Cao, Kaisheng Zeng, Qi Li, Ningyun Li, Ling Feng  
Proceedings of the ACM SIGKDD Conference on Knowledge Discovery and Data Mining (**KDD 2023**) **[CORE A\* · CCF A]** [[pdf](https://dl.acm.org/doi/pdf/10.1145/3580305.3599795)] [[code](https://github.com/xin-wang18/SSE)] [[data](https://github.com/xin-wang18/SSE)]

- **A Meta-learning based Stress Category Detection Framework on Social Media.**  
**Xin Wang**, Lei Cao, Huijun Zhang, Ling Feng, Yang Ding, Ningyun Li  
Proceedings of the ACM Web Conference (**WWW 2022**) **[CORE A\* · CCF A]** [[pdf](https://dl.acm.org/doi/pdf/10.1145/3485447.3512013)] [[data](https://github.com/xin-wang18/Categroy-Dataset)]

- **Leverage Social Media for Personalized Stress Detection.**  
**Xin Wang**, Huijun Zhang, Lei Cao, Ling Feng  
Proceedings of the ACM International Conference on Multimedia (**MM 2020**) **[CORE A\* · CCF A]** [[pdf](https://dl.acm.org/doi/pdf/10.1145/3394171.3413596)]

