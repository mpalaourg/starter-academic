---
title: JPEG
summary: Implementation of JPEG standard (ISO/IEC 109181:1994).
tags:
- image compression
- multimedia
- MATLAB
date: "2016-04-27T00:00:00Z"

image:
  caption: ""
  focal_point: Smart

url_code: "https://github.com/mpalaourg/Multimedia"
url_pdf: "media/jpeg.pdf"
url_slides: ""
url_video: ""
---

<div style="text-align: justify"> <p>
The goal is to implement the baseline sequential DCT based (Lossy) JPEG encoder and decoder as described by ISO-IEC-10918-1-1993 standard. The major steps in JPEG coding involve:
<ul>
<li>Pre-processing of the image.
  <ul>
  <li>RGB ↔ YCbCr conversion.</li>
  <li>Subsampling 4:4:4, 4:2:2 and 4:2:0.</li>
  </ul></li>
<li>Samples dissociation.
  <ul>
  <li>Block [8x8] DCT Transform: Spatial Domain Representation ↔ Frequency Domain Representation</li>
  </ul></li>
<li>Image compression.
  <ul>
  <li>Block [8x8] Quantization and De-Quantization.</li>
  <li>Run-length calculation.</li>
  <li>Huffman coding.</li>
  </ul></li>
</ul>

For a more detailed explanation of the steps -in Greek- check the associated pdf file.
</p> </div>
