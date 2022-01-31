---
header:
  overlay_image: /assets/images/header.jpg
  caption: "*Photo credit: Roman Mager*"
permalink: /portfolio/BayeML/
date: 2021-01-19
toc: true
toc_label: "Contents"
---

# Bayesian Meta-Learning
## Bayesian Meta-Learning Basics
Meta-learning, or learning to learn, has emerged as a promising paradigm to address data heterogeneity and scarcity in medical applications. It starts with the assumption that test data distribution is unseen and different from the training data. In contrast to learning a model from scratch (supervised learning) or transferring features (domain adaptation), meta-learning leverages knowledge from multiple tasks to improve the learning mechanism. Once learned, a meta-learning model can adjust itself to a new data distribution rapidly using only a few labeled examples. This technology's high computational and data efficiency potentially increases the accuracy, development speed, and deployment efficiency of computer-aided diagnosis systems. Bayesian method, on the other hand, can help the machine learning model to give a distribution over prediction and prevent the overfitting problem. Combine the Bayesian learning and meta-learning can provide us a safety-critical few-shot model. We can also leverage the uncertainty information to actively annotate new samples, which can enhance the interaction between human and machine learning models.

### Outline
*(For detail of this presentation[^fnote1], check the [slides][1].)*
- Introduction
    - Why Bayesian meta-learning?
    - The evidence lower bound (ELBO) 
- Bayesian meta-learning approaches based on
    - Amortized variational inference 
        - Black-box
        - Optimization
    - Bayesian ensembles 
    - Bayesian neural networks
- Bayesian meta-learning evaluation
    - Qualitative visualization
    - Quantitative evaluation
    - Active-learning evaluation

## Active Bayesian meta-learning for brain cell classification
Deep Neural Networks (or DNNs) must constantly cope with
distribution changes in the input data when the task of interest or the
data collection protocol changes. Retraining a network from scratch to
combat this issue poses a significant cost. Meta-learning aims to deliver an adaptive model that is sensitive to these underlying distribution
changes, but requires many tasks during the meta-training process. In
this paper, we propose a tAsk-auGmented actIve meta-LEarning (AGILE) method to efficiently adapt DNNs to new tasks by using a small
number of training examples. AGILE combines a meta-learning algorithm with a novel task augmentation technique which we use to generate an initial adaptive model. It then uses Bayesian dropout uncertainty
estimates to actively select the most difficult samples when updating the
model to a new task. This allows AGILE to learn with fewer tasks and
a few informative samples, achieving high performance with a limited
dataset. We perform our experiments using the brain cell classification
task and compare the results to a plain meta-learning model trained
from scratch. We show that the proposed task-augmented meta-learning
framework can learn to classify new cell types after a single gradient step
with a limited number of training samples. We show that active learning
with Bayesian uncertainty can further improve the performance when
the number of training samples is extremely small. Using only 1% of the
training data and a single update step, we achieved 90% accuracy on
the new cell type classification task, a 50% points improvement over a
state-of-the-art meta-learning algorithm.

### Outline
*(For detail of this presentation[^fnote2], check the [slides][2].)*
- What is meta-learning?
    - Problem of supervised-learning
    - Model-agnostic meta-learning (MAML) 
- tAsk-auGmented actIve meta-LEarning (AGILE)
    - Problems of MAML 
    - Task augmentations 
    - Active-learning in real-task
- Experiments and results

## Useful links
- Bayesian Meta-Learning Tutorial \\
    [\[website\]][6]
- Bayesian Meta-Learning Basics \\
    [\[slides\]][1][\[presentation\]][3] 
- Active Bayesian meta-learning for brain cell classification \\
    [\[slides\]][2][\[presentation\]][4][\[paper\]][5] 

[^fnote1]: Bayesian meta-learning approaches and evaluation methods.
	
[^fnote2]: Using Bayesian meta-learning in brain cell type classification task.


[1]: /assets/presentations/Bayesian meta learning.pdf
[2]: /assets/presentations/Active Bayesian meta-learning for brain cell classification.pdf
[3]: https://drive.google.com/file/d/1tyfWdpL94bDe3CAZ40iHChPYYVZWzvHh/view?usp=sharing
[4]: https://drive.google.com/file/d/1_9mNKAa1tDVluAKqcl109LMSOd5q-gm3/view?usp=sharing
[5]: https://arxiv.org/pdf/2007.05009.pdf
[6]: https://www.hvnguyen.com/metalearning
