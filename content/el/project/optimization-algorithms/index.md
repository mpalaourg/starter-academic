---
title: Optimization Algorithms
summary: Υλοποίηση διαφόρων αλγορίθμων βελτιστοποίησης
tags:
- function minimum
- function estimation
- machine learning
- MATLAB
date: "2016-04-27T00:00:00Z"

image:
  caption: ""
  focal_point: Smart

url_code: "https://github.com/mpalaourg/Optimization_Techniques"
url_pdf: ""
url_slides: ""
url_video: ""
---

Ο στόχος είναι η υλοποίηση διαφόρων αλγορίθμων βελτιστοποίησης, υπό διαφορετικές συνθήκες. Πιο συγκεκριμένα:
- Εύρεση ελαχίστου σε -αυστηρά- κυρτές συναρτήσεις \[1-Δ\]
  - Μέθοδος Διχοτόμου \[[Αλγόριθμος](https://mathworld.wolfram.com/Bisection.html)\]
  - Μέθοδος Χρυσού τομέα \[[Αλγόριθμος](http://web.tecnico.ulisboa.pt/mcasquilho/compute/com/,Fibonacci/pdfHXu_ch1.pdf#page=8)\]
  - Μέθοδος Fibonacci \[[Αλγόριθμος](http://web.tecnico.ulisboa.pt/mcasquilho/compute/com/,Fibonacci/pdfHXu_ch1.pdf#page=13)\]
  - Μέθοδος Διχοτόμου (με χρήση παραγώγων) \[[Αλγόριθμος](http://www.princeton.edu/~aaa/Public/Teaching/ORF363_COS323/F16/ORF363_COS323_F16_Lec7.pdf#page=2)\]
- Εύρεση ελαχίστου συνάρτησης για την οποία δεν υπάρχει αναλυτικός τύπος \[2-Δ\]
  - Μέθοδος Μέγιστης Καθόδου \[[Αλγόριθμος](http://www.cs.cmu.edu/~pradeepr/convexopt/Lecture_Slides/Gradient-Descent.pdf)\]
  - Μέθοδος Newton \[[Αλγόριθμος](http://www.cs.cmu.edu/~pradeepr/convexopt/Lecture_Slides/Newton_methods.pdf#page=11)\]
  - Μέθοδος Levenberg - Marquardt \[[Αλγόριθμος](http://ananth.in/docs/lmtut.pdf)\]
  - Μέθοδος συζυγών κλίσεων (Polak–Ribière) \[[Αλγόριθμος](http://www.cs.cmu.edu/~pradeepr/convexopt/Lecture_Slides/conjugate_direction_methods.pdf#page=38)\]
  - Μέθοσος quasi Newton (Τύπος Davidon–Fletcher–Powell) \[[Αλγόριθμος](https://www.stat.cmu.edu/~ryantibs/convexopt-F13/lectures/11-QuasiNewton-AnnotatedOnClass.pdf#page=21)\]
- Εύρεση ελαχίστου συνάρτησης παρουσία περιορισμών \[2-Δ\]
  - Μέθοδος Μέγιστης Καθόδου, με και χωρίς περιορισμούς \[[Αλγόριθμος](https://www.cs.ccu.edu.tw/~wtchu/courses/2015s_OPT/Lectures/Chapter%2023%20Algorithms%20for%20Constrained%20Optimization.pdf#page=2)\]
- Γενετικός Αλγόριθμος: Προσέγγιση άγνωστης συνεχούς συνάρτησης \[2-Δ\]
