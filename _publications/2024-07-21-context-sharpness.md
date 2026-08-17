---
title: "In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation"
collection: publications
category: conferences
permalink: /publication/context-sharpness-2024
search: true
excerpt: 'We propose using in-context sharpness as an alert mechanism based on the inner representation perspective to detect and mitigate hallucination in LLMs.'
date: 2024-07-21
venue: 'ICML 2024'
paperurl: 'https://arxiv.org/abs/2403.02732'
citation: 'Shiqi Chen et al. (2024). In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation. In International Conference on Machine Learning (ICML).'
coauthor_names: 'Shiqi Chen, Miao Xiong, Junteng Liu, Zhengxuan Wu, Teng Xiao, Siyang Gao, Junxian He'
---

Large language models (LLMs) exhibit hallucination behavior that can be exploited for their misuse and may have critical security implications under certain contexts. Hallucination mitigation at inference time is ideal, given its relevance in real-world deployments.

In this paper, we define in-context sharpness as a fine-grained yet efficient proxy for measuring visual and semantic hallucination. We discover that in-context sharpness arises directly from the inner representations of vision-language models and propose to use it as a hallucination detection and mitigation mechanism without any additional training.

We introduce ABC-H, an inference-time hallucination mitigation approach that fuses in-context sharpness as alerts with Attention-Based Consistency reduction. Extensive evaluations on hallucination detection and mitigation tasks show that ABC-H can effectively demystify and counter hallucination in VLMs.

**ArXiv:** [In-Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation](https://arxiv.org/abs/2403.02732)

**ICML 2024:** [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/...)
