---
header:
  overlay_image: /assets/images/seismicDeblend.png
  caption: "**Seismic deblending**, *Figure credit: tgs*"
permalink: /portfolio/deblend/
date: 2021-01-19
toc: true
toc_label: "Contents"
---

# Seismic deblending by self-supervised deep learning with a blind-trace network

*IMAGE 2021* \\
Shirui Wang, Wenyi Hu, **Pengyu Yuan**, Xuqing Wu, Qunshan Zhang, Prashanth Nadukandi, German Ocampo Botero, and Jiefu Chen

## Abstract

Simultaneous-source acquisition endows seismic imaging with dense and efficient surveying designs. This cost-efficient strategy leads to inevitable interference when multiple source responses are recorded within a short time interval. To enable traditional seismic processing workflows, we need an accurate deblending process to separate the blended signals. Deep learning has been widely used in various seismic processing tasks. However, the disparity of seismic datasets is a challenge to a deep neural network’s adaptiveness (also known as generalization). The scarcity of labeled data in the deblending task also intensifies the overfitting problem. We propose a self-supervised learning method for seismic data deblending and a flexible deblending algorithm for speed-accuracy tradeoff. Using a novel blind-trace network and blending loss function, self-supervised training is deployed directly on the target data without the need for a labeled training dataset. Numerical experiments on several datasets demonstrate the effectiveness and robustness of the proposed method.

## Useful links

[\[SEG Library\]][1][\[BibTeX\]][2]


[1]:https://library.seg.org/doi/epdfplus/10.1190/segam2021-3583662.1
[2]: /assets/bibtex/deblend.txt
