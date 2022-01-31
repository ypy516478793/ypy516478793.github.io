---
header:
  overlay_image: /assets/images/lungNodule.png
  caption: "**Lung nodules**, *Figure credit: Aryan Mobiny*"
permalink: /portfolio/MAMCAP/
date: 2021-01-19
toc: true
toc_label: "Contents"
---

# Memory-Augmented Capsule Network for Adaptable Lung Nodule Classification
*IEEE Transactions on Medical Imaging 2021* \\
Aryan Mobiny , **Pengyu Yuan**, Pietro A. Cicalese , Supratik K. Moulik, Naveen Garg, Carol C. Wu , Kelvin Wong, Stephen T. Wong, Tian Cheng He , and Hien V. Nguyen

## Abstract

Computer-aided diagnosis (CAD) systems
must constantly cope with the perpetual changes in data
distributioncausedby different sensingtechnologies,imaging protocols, and patient populations. Adapting these systems to new domains often requires significant amounts of
labeled data for re-training. This process is labor-intensive
and time-consuming. We propose a memory-augmented
capsule network for the rapid adaptation of CAD models
to new domains. It consists of a capsule network that
is meant to extract feature embeddings from some highdimensional input, and a memory-augmented task network
meant to exploit its stored knowledge from the target
domains. Our network is able to efficiently adapt to unseen
domains using only a few annotated samples. We evaluate our method using a large-scale public lung nodule
dataset (LUNA), coupled with our own collected lung nodules and incidental lung nodules datasets. When trained on
the LUNA dataset, our network requires only 30 additional
samples from our collected lung nodule and incidental lung
nodule datasets to achieve clinically relevant performance
(0.925 and 0.891 area under receiving operating characteristic curves (AUROC), respectively). This result is equivalent
to using two orders of magnitude less labeled training data
while achieving the same performance. We further evaluate our method by introducing heavy noise, artifacts, and
adversarial attacks. Under these severe conditions, our network’s AUROC remains above 0.7 while the performance of
state-of-the-art approaches reduce to chance level.

## Useful links

[\[IEEE Xplore\]][1][\[BibTeX\]][2]


[1]:https://ieeexplore.ieee.org/abstract/document/9319883
[2]: /assets/bibtex/MEMCAP.txt
