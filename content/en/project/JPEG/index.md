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
url_pdf: "el/media/files/jpeg.pdf"
url_slides: ""
url_video: ""
---

The goal is to implement the baseline sequential DCT based (Lossy) JPEG encoder and decoder as described by the ISO-IEC-10918-1-1993 standard. The major steps in JPEG coding involve:
- Pre-processing of the image
  - RGB ↔ YCbCr conversion
  - Subsampling 4:4:4, 4:2:2 and 4:2:0
- Samples dissociation
  - Block \[8x8\] DCT Transform: Spatial Domain Representation ↔ Frequency Domain Representation
- Image compression
  - Block \[8x8\] Quantization and De-Quantization
  - Run-length calculation
  - Huffman coding

For a more detailed explanation of the steps -in Greek- check the associated PDF file.
