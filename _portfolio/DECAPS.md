---
header:
  overlay_image: /assets/images/chest.png
  caption: "**RSNA Pneumonia detection**, *Figure credit: Aryan Mobiny*"
permalink: /portfolio/DECAPS/
date: 2021-01-19
toc: true
toc_label: "Contents"
---

# DECAPS: Detail-Oriented Capsule Networks
*MICCAI 2020* \\
Aryan Mobiny, **Pengyu Yuan**, Pietro Antonio Cicalese, Hien Van Nguyen

## Abstract

Capsule Networks (CapsNets) have demonstrated to be a
promising alternative to Convolutional Neural Networks (CNNs). However, they often fall short of state-of-the-art accuracies on large-scale
high-dimensional datasets. We propose a Detail-Oriented Capsule Network (DECAPS) that combines the strength of CapsNets with several
novel techniques to boost its classification accuracies. First, DECAPS
uses an Inverted Dynamic Routing (IDR) mechanism to group lowerlevel capsules into heads before sending them to higher-level capsules.
This strategy enables capsules to selectively attend to small but informative details within the data which may be lost during pooling operations in CNNs. Second, DECAPS employs a Peekaboo training procedure, which encourages the network to focus on fine-grained information
through a second-level attention scheme. Finally, the distillation process
improves the robustness of DECAPS by averaging over the original and
attended image region predictions. We provide extensive experiments on
the CheXpert and RSNA Pneumonia datasets to validate the effectiveness of DECAPS. Our networks achieve state-of-the-art accuracies not
only in classification (increasing the average area under ROC curves from
87.24% to 92.82% on the CheXpert dataset) but also in the weaklysupervised localization of diseased areas (increasing average precision
from 41.7% to 80% for the RSNA Pneumonia detection dataset).

## Useful links

[\[arXiv\]][1][\[BibTeX\]][2]


[1]: https://arxiv.org/pdf/2007.05343.pdf
[2]: /assets/bibtex/DECAPS.txt
