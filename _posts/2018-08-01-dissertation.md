---
layout: post
title:  "Deep Neural Networks for Multi-Label Text Classification: Application to Coding Electronic Medical Records"
date:   2018-08-01 21:55:55 +0200
author: "Anthony Rios"
categories: Papers
---

## Abstract:
Coding Electronic Medical Records (EMRs) with diagnosis and procedure codes is an essential task for billing, secondary data analyses, and monitoring health trends. Both speed and accuracy of coding are critical. While coding errors could lead to more patient-side financial burden and misinterpretation of a patient’s well-being, timely coding is also needed to avoid backlogs and additional costs for the healthcare facility. Therefore, it is necessary to develop automated diagnosis and procedure code recommendation methods that can be used by professional medical coders.

The main difficulty with developing automated EMR coding methods is the nature of the label space. The standardized vocabularies used for medical coding contain over 10 thousand codes. The label space is large, and the label distribution is extremely unbalanced - most codes occur very infrequently, with a few codes occurring several orders of magnitude more than others. A few codes never occur in training dataset at all.

In this work, we present three methods to handle the large unbalanced label space. First, we study how to augment EMR training data with biomedical data (research articles indexed on PubMed) to improve the performance of standard neural networks for text classification. PubMed indexes more than 23 million citations. Many of the indexed articles contain relevant information about diagnosis and procedure codes. Therefore, we present a novel method of incorporating this unstructured data in PubMed using transfer learning. Second, we combine ideas from metric learning with recent advances in neural networks to form a novel neural architecture that better handles infrequent codes. And third, we present new methods to predict codes that have never appeared in the training dataset. Overall, our contributions constitute advances in neural multi-label text classification with potential consequences for improving EMR coding.

[<a href="https://uknowledge.uky.edu/cs_etds/71/">Link</a>]
