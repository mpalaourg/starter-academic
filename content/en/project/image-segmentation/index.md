---
title: Image Segmentation
summary: Ιmplementation of basic image segmentation techniques.
tags:
- multimedia
- MATLAB
date: "2016-04-27T00:00:00Z"

image:
  caption: ""
  focal_point: Smart

url_code: "https://github.com/mpalaourg/DIP_Image_Segmentation"
url_pdf: ""
url_slides: ""
url_video: ""
---

<div style="text-align: justify"> <p>
The goal is to represent the input image as a fully connected and non-directional graph, and partitioned them into multiple sets of segments that share some common characteristics, such as color or intensity.

The following techniques were implemented:
<ul>
<li>Spectral Clustering (k clusters). [<a href="https://www.kaggle.com/vipulgandhi/spectral-clustering-detailed-explanation#-Algorithm:-">Algorithm</a>]</li>
<li>Normalized cuts (k clusters). [<a href="https://people.eecs.berkeley.edu/~malik/papers/SM-ncut.pdf#page=4">Algorithm</a> using the k smallest eigenvalues in Step 3]</li>
<li>Recursive Normalized cuts (unspecified clusters). [<a href="https://people.eecs.berkeley.edu/~malik/papers/SM-ncut.pdf#page=6">Algorithm</a> using Ncut(A, B) metric]</li>
</ul>
</p> </div>
