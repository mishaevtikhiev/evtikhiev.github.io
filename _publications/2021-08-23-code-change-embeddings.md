---
title: "Unsupervised Learning of General-Purpose Embeddings for Code Changes"
authors: '<i>Mikhail Pravilov, Egor Bogomolov, Yaroslav Golubev, and Timofey Bryksin</i>'
status: "accepted"
collection: publications
permalink: /publication/2021-08-23-code-change-embeddings
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-08-23
venue: "<b>MaLTeSQuE'21</b>"
paperurl: 'https://arxiv.org/abs/2106.02087'
citation: 'Pravilov, M., Bogomolov, E., Golubev, Y., & Bryksin, T. (2021). Unsupervised Learning of General-Purpose Embeddings for Code Changes. arXiv preprint arXiv:2106.02087.'
---
Applying machine learning to tasks that operate with code changes requires their numerical representation. 
In this work, we propose an approach for obtaining such representations during pre-training and evaluate them on 
two different downstream tasks - applying changes to code and commit message generation. During pre-training, 
the model learns to apply the given code change in a correct way. This task requires only code changes themselves, 
which makes it unsupervised. In the task of applying code changes, our model outperforms baseline models by 5.9 
percentage points in accuracy. As for the commit message generation, our model demonstrated the same results as 
supervised models trained for this specific task, which indicates that it can encode code changes well and can be 
improved in the future by pre-training on a larger dataset of easily gathered code changes.

[Download paper here](https://arxiv.org/pdf/2106.02087.pdf)

Recommended citation: Pravilov, M., Bogomolov, E., Golubev, Y., & Bryksin, T. (2021). Unsupervised Learning of General-Purpose Embeddings for Code Changes. arXiv preprint arXiv:2106.02087.