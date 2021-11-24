---
title: "Multitask Balanced and Recalibrated Network for Medical Code Prediction"
collection: publications
permalink: /publication/2021-09-06-paper-title-number-2
excerpt: 'Human coders assign standardized medical codes to clinical documents generated during patients’ hospitalization, which is
error-prone and labor-intensive. Automated medical coding approaches have been developed using machine learning methods such
as deep neural networks. Nevertheless, automated medical coding is still challenging because of the imbalanced class problem,
complex code association, and noise in lengthy documents. To solve these issues, we propose a novel neural network called Multitask
Balanced and Recalibrated Neural Network. Significantly, the multitask learning scheme shares the relationship knowledge between
different code branches to capture the code association. A recalibrated aggregation module is developed by cascading convolutional
blocks to extract high-level semantic features that mitigate the impact of noise in documents. Also, the cascaded structure of the
recalibrated module can benefit the learning from lengthy notes. To solve the class imbalanced problem, we deploy the focal loss to
redistribute the attention of low and high-frequency medical codes. Experimental results show that our proposed model outperforms
competitive baselines on a real-world clinical dataset MIMIC-III.'
date: 2021-09-06
venue: 'Preprint'
paperurl: 'https://arxiv.org/pdf/2109.02418.pdf'
citation: 'Sun, Wei, et al. "Multitask Balanced and Recalibrated Network for Medical Code Prediction." arXiv preprint arXiv:2109.02418 (2021).'
---
We extend our previous work~(MT-RAM) to a more advanced model called~(MARN).
MARN leverages focal loss to deal with the imbalanced class problem of MIMIC-III dataset.
Multitask learning scheme can capture code associations by joint-training two coding branches.
RAM is designed to refine textual features extracted from lengthy and noisy clinical notes.

[Download paper here](https://arxiv.org/pdf/2109.02418.pdf)

Recommended citation: Sun, Wei, et al. "Multitask Balanced and Recalibrated Network for Medical Code Prediction." arXiv preprint arXiv:2109.02418 (2021).