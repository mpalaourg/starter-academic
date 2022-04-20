---
title: Image Segmentation
summary: Υλοποίηση βασικών τεχνικών τμηματοποίησης εικόνων.
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
Ο στόχος είναι η αναπαράσταση εικόνων ως πλήρη συνδεδεμένο και μη κατευθυντικό γράφο, και ο διαχωρισμός τους σε πολλαπλά τμήματα που μοιράζονται ορισμένα κοινά χαρακτηριστικά, όπως το χρώμα ή η ένταση.

Υλοποιήθηκαν οι εξής τεχνικές:
<ul>
<li>Spectral Clustering (k συστάδες). [<a href="https://www.kaggle.com/vipulgandhi/spectral-clustering-detailed-explanation#-Algorithm:-">Αλγόριθμος</a>]</li>
<li>Normalized cuts (k συστάδες). [<a href="https://people.eecs.berkeley.edu/~malik/papers/SM-ncut.pdf#page=4">Αλγόριθμος</a> χρησιμοποιώντας τις k μικρότερες ιδιοτιμές στο Βήμα 3]</li>
<li>Recursive Normalized cuts (Απροσδιόριστος αρ. συστάδων). [<a href="https://people.eecs.berkeley.edu/~malik/papers/SM-ncut.pdf#page=6">Αλγόριθμος</a> χρησιμοποιώντας τη μετρική Ncut(A, B)]</li>
</ul>
</p> </div>
