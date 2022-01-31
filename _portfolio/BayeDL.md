---
header:
  overlay_image: /assets/images/header.jpg
  caption: "*Photo credit: Roman Mager*"
permalink: /portfolio/BayeDL/
date: 2021-01-19
toc: true
toc_label: "Contents"
---

# Bayesian Deep Learning
## Introduction to Bayesian Modeling and Variational Inference
Recently, there has been an increasing interest in combining Bayesian methods with deep neural networks to enable estimating the confidence of the model’s prediction. While the conventional approach views a deep network as a deterministic function that produces only a single output for an input. In contrast, Bayesian deep learning computes a distribution of output for each input by taking into account the randomness inherent in the training data and the modeling parameters. This distribution allows estimating the confidence level of the output. New methods based on stochastic regularization techniques like dropout or scalable Monte Carlo interference have been shown to capture meaningful uncertainty while scaling well to high-dimensional data. The revisit of Bayesian techniques in light of deep learning has created many promising results.

### Outline
*(For detail of this presentation, check the [slides][1].)*
- Introduction
    - Why we need uncertainty?
    - Basic Bayesian rules 
- Non-Bayesian method
    - Linear Regression
- Bayesian meta-learning evaluation
    - Qualitative visualization
    - Quantitative evaluation
    - Active-learning evaluation
- Non-parametric Bayesian
    - Non-parametric method (GP)
    - Gaussian Process Regression

## DropConnect Is Effective in Modeling Uncertainty of Bayesian Deep Networks
Deep neural networks (DNNs) have achieved state-of-the-art performance in many important domains, including medical diagnosis, security, and autonomous driving. In domains where safety is highly critical, an erroneous decision can result in serious consequences. While a perfect prediction accuracy is not always achievable, recent work on Bayesian deep networks shows that it is possible to know when DNNs are more likely to make mistakes. Knowing what DNNs do not know is desirable to increase the safety of deep learning technology in sensitive applications; Bayesian neural networks attempt to address this challenge. Traditional approaches are computationally intractable and do not scale well to large, complex neural network architectures. In this paper, we develop a theoretical framework to approximate Bayesian inference for DNNs by imposing a Bernoulli distribution on the model weights. This method called Monte Carlo DropConnect (MC-DropConnect) gives us a tool to represent the model uncertainty with little change in the overall model structure or computational cost. We extensively validate the proposed algorithm on multiple network architectures and datasets for classification and semantic segmentation tasks. We also propose new metrics to quantify uncertainty estimates. This enables an objective comparison between MC-DropConnect and prior approaches. Our empirical results demonstrate that the proposed framework yields significant improvement in both prediction accuracy and uncertainty estimation quality compared to the state of the art.

### Outline
*(For detail of this presentation, check the [slides][2].)*
- What is dropConnect?
    - DropConnect as Bayesian Approximations
    - MC-Dropout vs. MC-Dropconnect 
- Uncertainty Evaluation Metrics
    - Negative Predictive Value (NPV)
    - True Positive Rate (TPR)
    - Uncertainty Accuracy (UA)
- Experiments and results
    - Classification
    - Segmentation

## Useful links
- Bayesian Deep Learning Tutorial \\
    [\[website\]][4]
- Introduction to Bayesian Modeling and Variational Inference \\
    [\[slides\]][1]
- DropConnect Is Effective in Modeling Uncertainty of Bayesian Deep Networks \\
    [\[slides\]][2][\[paper\]][3] 


[1]: /assets/presentations/Session1-MICCAI19.pdf
[2]: /assets/presentations/Session3-MICCAI19.pdf
[3]: https://www.nature.com/articles/s41598-021-84854-x.pdf
[4]: https://www.hvnguyen.com/bayesiandeeplearning
