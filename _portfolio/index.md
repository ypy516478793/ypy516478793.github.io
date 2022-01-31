---
classes: wide
header:
  overlay_image: /assets/images/AntelopeCanyon.jpeg
  caption: "**Antelope Canyon**, *Page AZ*"
permalink: /portfolio/index.html
date: 2021-01-19

feature_row:
  - image_path: assets/images/MEMCAP.png
    alt: "MEMCAP"
    title: "Adaptable Lung Nodule Classification"
    excerpt: "A memory-augmented capsule network for the rapid adaptation of CAD models to new domains."
    url: "/portfolio/MAMCAP/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: assets/images/agile.png
    alt: "AGILE"
    title: "AGILE: Few Shot Brain Cell Classification"
    excerpt: "A tAsk-auGmented actIve meta-LEarning (AGILE) brain cell type classifier."
    url: "/portfolio/AGILE/"
    btn_label: "Read More"
    btn_class: "btn--primary"    
  - image_path: assets/images/DECAPS.png
    alt: "DECAPS"
    title: "DECAPS: Detail-Oriented Capsule Networks"
    excerpt: "A tAsk-auGmented actIve meta-LEarning (AGILE) brain cell type classifier."
    url: "/portfolio/DECAPS/"
    btn_label: "Read More"
    btn_class: "btn--primary"    
  - image_path: /assets/images/breast.png
    alt: "Breast"
    title: "Multimodal Breast Lesion Classification"
    excerpt: "Breast lesion risk estimation using both mammograms and clinical reports."
    url: "/portfolio/breast/"
    btn_label: "Read More"
    btn_class: "btn--primary"	
  - image_path: /assets/images/phasetime.png
    alt: "Phasetime"
    title: "Phasetime: Nuclei Detection"
    excerpt: "A deep learning approach to detect nuclei in time lapse phase images."
    url: "/portfolio/phasetime/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/interpolation.png
    alt: "Interpolation"
    title: "Self-supervised Seismic Interpolation"
    excerpt: "A self-supervised learning approach for anti-aliasing seismic data interpolation."
    url: "/portfolio/interpolation/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/fap.png
    alt: "FAP"
    title: "First Arrival Picking"
    excerpt: "A robust first-arrival picking workflow using convolutional and recurrent neural networks."
    url: "/portfolio/fap/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/deblend.png
    alt: "Deblend"
    title: "Unsupervised Seismic Deblending"
    excerpt: "Seismic deblending by self-supervised deep learning with a blind-trace network."
    url: "/portfolio/deblend/"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
feature_row2:
  - image_path: assets/images/BayeML.png
    alt: "BayeML"
    title: "Bayesian meta-learning"
    excerpt: "Bayesian meta-learning basics and its application in medical field."
    url: "/portfolio/BayeML/"
    btn_label: "Read More"
    btn_class: "btn--primary"    
  - image_path: assets/images/BayeDL.png
    alt: "BayeDL"
    title: "Bayesian deep learning"
    excerpt: "Bayesian methods for machine learning and dropConnect for Bayesian Neural Network."
    url: "/portfolio/BayeDL/"
    btn_label: "Read More"
    btn_class: "btn--primary"  
---


# Portfolio

Here you'll find summaries of my major academic projects as well as the tutorial I presented in 
MICCAI conference, which are representative of my skills and interests. All projects utilize 
the deep learning model to solve specific image analysis problem, both in medical and geophysical
fields. Specifically, I focus on solving the less-label issue of deep learning by using
meta-learning or self-supervised learning strategies. The tutorials here provides the basic knowledge
about Bayesian learning and Bayesian meta-learning, as well as some popular approaches and our solutions
in terms of the medical applications.  

For all academic projects, you can find the related publication in [my resume][1]. There are also 
links to documents at the bottom of each project, which offer more depth. If you're curious
about technical details I've glossed over, feel free to [contact me][2].


<div style="margin-bottom:1cm" align="center"><font size="6">Selected Research Projects</font></div>

{% include feature_row %}

<div style="margin-bottom:1cm" align="center"><font size="6">Conference Tutorials</font></div>

{% include feature_row id="feature_row2" %}

<!------------------------------- FOOTER --------------------------------->

[1]: /assets/docs/resume.pdf

[2]: mailto:ypy516478793@pwills.com
