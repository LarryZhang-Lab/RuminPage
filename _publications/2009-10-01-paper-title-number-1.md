---
title: "CAT: Continual Adapter Tuning for aspect sentiment classification"
collection: publications
category: Journal
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper is about a continual adapter initialization technique to transfer knowledge from preceding tasks.'
date: 2024-02-17
venue: 'Neurocomputing'
paperurl: 'http://academicpages.github.io/files/CAT - Continual Adapter Tuning for aspect sentiment classification.pdf'
citation: 'Qiangpu Chen, Jiahua Huang , Wushao Wen, Qingling Li, Rumin Zhang , Jinghui Qin, CAT: Continual Adapter Tuning for aspect sentiment classification. Neurocomputing ,Vol.580, (2024)'
---

Humans can continually acquire, improve, and transfer knowledge throughout their lifespan so that they can accurately identify sentiment polarities of the data attributed to different domains. However, the continual learning of incrementally available aspect sentiment classification (ASC) tasks from different domains with non-stationary data distributions remains a long-standing challenge for learning-based models due to the catastrophic forgetting problem, which is the tendency to completely and abruptly forget previously learned knowledge upon learning new knowledge. In this work, we present Continual Adapter Tuning (CAT), a parameter-efficient framework that not only avoids catastrophic forgetting but also enables knowledge transfer from learned ASC tasks to new ASC tasks. To avoid catastrophic forgetting, we only learn and store a task-specific adapter for each ASC task while freezing the backbone pre-trained model. To promote new task learning, we propose a continual adapter initialization technique to transfer knowledge from preceding tasks. Besides, we also develop a novel label-aware contrastive learning to simultaneously learn the features of input samples and the parameters of classifiers in the same space so that we can efficiently classify a sample with the help of label semantics. To eliminate the need for task IDs in testing, we propose a simple yet efficient majority sentiment polarity voting strategy to obtain final sentiment polarities according to the polarities predicted by all reasoning paths in the adapter architecture. Experimental results show the high effectiveness of our CAT by achieving new state-of-the-art performance
