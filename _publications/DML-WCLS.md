---
title: "A Meta-Learning Method for Estimation of Causal Excursion Effects to Assess Time-Varying Moderation"
collection: publications
permalink: /publication/DML-WCLS-MRT
date: 2023-6-28
venue: 'Arxiv'
---


[Download paper here](https://arxiv.org/abs/2306.16297)    [(Code)](https://github.com/Herashi/DML-WCLS)


Twin revolutions in wearable technologies and smartphone-delivered digital health interventions have significantly expanded the accessibility and uptake of mobile health (mHealth) interventions across various health science domains. Sequentially randomized experiments called micro-randomized trials (MRTs) have grown in popularity to empirically evaluate the effectiveness of these mHealth intervention components. MRTs have given rise to a new class of causal estimands known as "causal excursion effects", which enable health scientists to assess how intervention effectiveness changes over time or is moderated by individual characteristics, context, or responses in the past. However, current data analysis methods for estimating causal excursion effects require pre-specified features of the observed high-dimensional history to construct a working model of an important nuisance parameter. While machine learning algorithms are ideal for automatic feature construction, their naive application to causal excursion estimation can lead to bias under model misspecification, potentially yielding incorrect conclusions about intervention effectiveness. To address this issue, this paper revisits the estimation of causal excursion effects from a meta-learner perspective, where the analyst remains agnostic to the choices of supervised learning algorithms used to estimate nuisance parameters. The paper presents asymptotic properties of the novel estimators and compares them theoretically and through extensive simulation experiments, demonstrating relative efficiency gains and supporting the recommendation for a doubly robust alternative to existing methods. Finally, the practical utility of the proposed methods is demonstrated by analyzing data from a multi-institution cohort of first-year medical residents in the United States (NeCamp et al., 2020).
