---
title: "On the Universal Truthfulness Hyperplane Inside LLMs"
collection: publications
category: conferences
permalink: /publication/llm-truthfulness-2024
search: true
excerpt: 'We uncover and characterize a universal truthfulness hyperplane in the activation space of large language models, providing insights into LLM truthfulness.'
date: 2024-11-18
venue: 'EMNLP 2024'
paperurl: 'https://aclanthology.org/2024.emnlp-main.346'
citation: 'Junteng Liu et al. (2024). On the Universal Truthfulness Hyperplane Inside LLMs. In Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing (EMNLP).'
coauthor_names: 'Shiqi Chen, Yu Cheng, Junxian He'
---

Large language models (LLMs) are known to be prone to hallucinations. In this work, we systematically investigate the internal mechanism driving LLM's truthfulness. We hypothesize and demonstrate the existence of a universal discriminative structure in their activation space, which we visually characterize and verify as acting as a linear truthfulness hyperplane.

Our analysis across several popular LLM families reveals that this hyperplane consistently captures a surprising amount of truthfulness-related information, enabling both the separation of truthful vs. hallucinated tokens and the prediction of likely hallucinations at inference time.

We further provide an algorithm for discovering such hyperplanes with minimal overhead, offering a line of inquiry for improving LLM reliability.

**Code:** [Universal_Truthfulness_Hyperplane on GitHub](https://github.com/Vicent0205/Universal_Truthfulness_Hyperplane)

**EMNLP 2024:** [Link](https://aclanthology.org/2024.emnlp-main.346)
