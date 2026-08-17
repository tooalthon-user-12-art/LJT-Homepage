---
title: "Composing Parameter-Efficient Modules with Arithmetic Operations"
collection: publications
category: conferences
permalink: /publication/pe-modules-2023
search: true
excerpt: 'We explore the composition of parameter-efficient fine-tuning modules using arithmetic operations of their parameters.'
date: 2023-12-02
venue: 'NeurIPS 2023'
paperurl: 'https://arxiv.org/abs/2310.18445'
citation: 'Jinghan Zhang et al. (2023). Composing Parameter-Efficient Modules with Arithmetic Operations. In Advances in Neural Information Processing Systems (NeurIPS).'
coauthor_names: 'Jinghan Zhang, Shiqi Chen, Junteng Liu, Junxian He'
---

Parameter-efficient fine-tuning (PEFT) has emerged as a widely used approach for adapting large pretrained models to downstream tasks. Different PEFT modules (e.g., LoRA, Prompt Tuning) have been developed. However, how to combine the effectiveness of different PEFT modules without catastrophic interference remains an open question.

This paper explores the composition of different PEFT modules via arithmetic operations (e.g., addition, subtraction) of their learned parameters.

We show that composition via addition is largely ineffective due to task conflicts and parameter dimension mismatches. We instead propose a new composition approach: (1) learning a shared PEFT module across tasks, and (2) using arithmetic subtraction to simulate fine-grained task-specific residual adapters.

Our experiments on COPA and SUPER-GLUE demonstrate... significant improvements over alternatives.

**ArXiv:** [Composing Parameter-Efficient Modules with Arithmetic Operations](https://arxiv.org/abs/2310.18445)
