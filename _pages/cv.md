---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* DPhil in Computer Science, University of Oxford, 2023-2028 (expected)
* MMathCompsci in Mathematics and Computer Science, University of Oxford, 2019-2023

Work experience
======

* Summer 2022: Mathematical Institute, University of Oxford, Summer Research Intern
  * Explored the use of the Neural Control Differential Equation model to address the problem of protein folding
  * Enhanced the capability of the Alphafold with rough path theory
  * Developed a deep-learning based signature-inverse model to reduce the complexity of standard signature inversion
  * Supervisors: [Professor Terry Lyons](https://www.maths.ox.ac.uk/people/terry.lyons) and [Dr. Cristopher Salvi](https://www.imperial.ac.uk/people/c.salvi)

* Summer 2021: [Alibaba Group](https://www.alibabagroup.com/en-US), Machine Learning Engineer Intern
  * Developed an object detection system for video subtitle-detection with Faster-RCNN model
  * Conducted semantic analysis on OCR-detected titles to assess the quality of video descriptions
  * Supervisor: Improved accuracy of object detection and classification by 10\% and were incorporated into production

* Summer 2020: [Alirus Biotech.](https://www.ailurus.bio/), Machine Learning Engineer Intern
  * Implemented image segmentation for Petri dish centering and Hough Transform for colony ROI detection
  * Developed a colony counting algorithm by combining CNNs with traditional computer vision techniques
  * Delivered a model for automatic colony counting with 20\% decreased in terms of regression metric
  
Skills
======
* Python   
  * PyTorch
  * Tensorflow
  * Triton
* MATLAB
* Haskell
* Scala
* LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
