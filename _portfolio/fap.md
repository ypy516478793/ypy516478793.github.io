---
header:
  overlay_image: /assets/images/shotGather.jpeg
  caption: "**Shot gathers**, *Figure credit: atlasmarinegs*"
permalink: /portfolio/fap/
date: 2021-01-19
toc: true
toc_label: "Contents"
---

# A robust first-arrival picking workflow using convolutional and recurrent neural networks

*Geophysics 2020* \\
**Pengyu Yuan**, Shirui Wang, Wenyi Hu, Xuqing Wu, Jiefu Chen, Hien Van Nguyen

## Abstract

A deep-learning-based workflow is proposed in this paper to
solve the first-arrival picking problem for near-surface velocity
model building. Traditional methods, such as the short-term
average/long-term average method, perform poorly when the
signal-to-noise ratio is low or near-surface geologic structures
are complex. This challenging task is formulated as a segmentation problem accompanied by a novel postprocessing approach to identify pickings along the segmentation boundary.
The workflow includes three parts: a deep U-net for segmentation, a recurrent neural network (RNN) for picking, and a weight
adaptation approach to be generalized for new data sets. In
particular, we have evaluated the importance of selecting a proper
loss function for training the network. Instead of taking an end-to-
end approach to solve the picking problem, we emphasize the
performance gain obtained by using an RNN to optimize the
picking. Finally, we adopt a simple transfer learning scheme and
test its robustness via a weight adaptation approach to maintain
the picking performance on new data sets. Our tests on synthetic
data sets reveal the advantage of our workflow compared with
existing deep-learning methods that focus only on segmentation
performance. Our tests on field data sets illustrate that a good
postprocessing picking step is essential for correcting the segmentation errors and that the overall workflow is efficient in minimizing human interventions for the first-arrival picking task.

## Useful links

[\[SEG Library\]][1][\[BibTeX\]][2]

<div style="margin-bottom:1cm" align="center"><font size="6">  </font></div>

# First arrival picking using U-net with Lovasz loss and nearest point picking method

*SEG 2019* \\
**Pengyu Yuan**, Wenyi Hu, Xuqing Wu, Jiefu Chen, Hien Van Nguyen

## Abstract

We proposed a robust segmentation and picking workflow to
solve the first arrival picking problem for seismic signal processing. Unlike traditional classification algorithm, image segmentation method can utilize the location information by outputting a prediction map which has the same size of the input image. A parameter-free nearest point picking algorithm
is proposed to further improve the accuracy of the first arrival
picking. The algorithm is test on synthetic clean data, synthetic noisy data, synthetic picking-disconnected data and field
data. It performs well on all of them and the picking deviation
reaches as low as 4.8ms per receiver. 

The first arrival picking problem is formulated as the contour
detection problem. Similar to Wu et al. (2019), we use U-net to
perform the segmentation as it is proven to be state-of-the-art
in many image segmentation tasks. Particularly, a Lovasz loss
instead of the traditional cross-entropy loss is used to train the
network for a better segmentation performance. Lovasz loss is
a surrogate loss for Jaccard index or the so-called intersectionover-union (IoU) score, which is often one of the most used
metrics for segmentation tasks. In the picking part, we use a
novel nearest point picking (NPP) method to take the advantage of the coherence of the first arrival picking among adjacent receivers. Our model is tested and validated on both
synthetic and field data with harmonic noises. The main contributions of this paper are as follows:
- Used Lovasz loss to directly optimize the IoU for segmentation task. Improvement over the cross-entropy
loss with regard to the segmentation accuracy is verified by the test result.
- Proposed a nearest point picking post processing
method to overcome any defects left by the segmentation output.
- Proposed a nearest point picking post processing
method to overcome any defects left by the segmentation output.

## Useful links

[\[arXiv\]][3][\[BibTeX\]][4]



[1]: https://library.seg.org/doi/abs/10.1190/geo2019-0437.1
[2]: /assets/bibtex/fap.txt
[3]: https://arxiv.org/pdf/2104.02805.pdf
[4]: /assets/bibtex/fap2.txt
