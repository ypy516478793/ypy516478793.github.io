---
header:
  overlay_image: /assets/images/braincell.jpeg
  caption: "**Brain cell**, *Figure credit: whitehoune*"
permalink: /portfolio/AGILE/
date: 2021-01-19
toc: true
toc_label: "Contents"
---

# Few Is Enough: Task-Augmented Active Meta-Learning for Brain Cell Classification
*MICCAI 2020* \\
**Pengyu Yuan**, Aryan Mobiny, Jahandar Jahanipour, Xiaoyang Li, Pietro Antonio Cicalese, Badrinath Roysam, Vishal M. Patel, Maric Dragan, Hien Van Nguyen

## Abstract

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

## Useful links

[\[arXiv\]][1][\[BibTeX\]][2]


[1]: https://arxiv.org/pdf/2007.05009.pdf
[2]: /assets/bibtex/AGILE.txt
