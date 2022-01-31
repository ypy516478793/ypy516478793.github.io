---
header:
  overlay_image: /assets/images/cell.png
  caption: "**Phase contrast images**, *Figure credit: Pengyu Yuan*"
permalink: /portfolio/phasetime/
date: 2021-01-19
toc: true
toc_label: "Contents"
---

# Phasetime: Deep Learning Approach to Detect Nuclei in Time Lapse Phase Images
*Journal of Clinical Medicine 2019* \\
**Pengyu Yuan**, Ali Rezvan, Xiaoyang Li, Navin Varadarajan, and Hien Van Nguyen

## Abstract

Time lapse microscopy is essential for quantifying the dynamics of cells, subcellular organelles and biomolecules. Biologists use different fluorescent tags to label and track the subcellular structures and biomolecules within cells. However, not all of them are compatible with time lapse imaging, and the labeling itself can perturb the cells in undesirable ways. We hypothesized that phase image has the requisite information to identify and track nuclei within cells. By utilizing both traditional blob detection to generate binary mask labels from the stained channel images and the deep learning Mask RCNN model to train a detection and segmentation model, we managed to segment nuclei based only on phase images. The detection average precision is 0.82 when the IoU threshold is to be set 0.5. And the mean IoU for masks generated from phase images and ground truth masks from experts is 0.735. Without any ground truth mask labels during the training time, this is good enough to prove our hypothesis. This result enables the ability to detect nuclei without the need for exogenous labeling.

## Useful links

[\[MDPI\]][1][\[BibTeX\]][2]


[1]: https://www.mdpi.com/2077-0383/8/8/1159
[2]: /assets/bibtex/phasetime.txt
