---
title: "Combining Global and Local Attention with Positional Encoding for Video Summarization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ευλάμπιος Αποστολίδης
- admin
- Βασίλειος Μεζάρης
- Ιωάννης Πάτρας

# Author notes (optional)
author_notes:
- "Ίση συνεισφορά"
- "Ίση συνεισφορά"

date: "2021-12-01T00:00:00Z"
doi: "10.1109/ISM52913.2021.00045"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Στο *IEEE Int. Symposium on Multimedia (ISM) 2021*
publication_short: Στο *ISM2021*

abstract: Αυτή η εργασία παρουσιάζει μια νέα μέθοδο για την εποπτευόμενη δημιουργία περιλήψεων βίντεο. Για να ξεπεραστούν τα μειονεκτήματα υφιστάμενων αρχιτεκτονικών δημιουργίας περιλήψεων που βασίζονται σε RNNs, σχετικά με τη μοντελοποίηση των εξαρτήσεων μεγάλης εμβέλειας των καρέ και την ικανότητα παραλληλοποίησης της εκπαίδευσης, το αναπτυγμένο μοντέλο βασίζεται στη χρήση μηχανισμών αυτοπροσοχής για την εκτίμηση της σημασίας των καρέ του βίντεο. Σε αντίθεση με προηγούμενες προσεγγίσεις δημιουργίας περιλήψεων που βασίζονται στην αυτοπροσοχή για να μοντελοποιούν τις εξαρτήσεις των καρέ παρατηρώντας ολόκληρη την αλληλουχία καρέ, η μέθοδός μας συνδυάζει καθολικούς και τοπικούς μηχανισμούς αυτοπροσοχής πολλαπλών κεφαλών για να ανακαλύψει διαφορετικές μοντελοποιήσεις των εξαρτήσεων των καρέ σε διαφορετικά επίπεδα λεπτομέρειας. Επιπλέον, οι χρησιμοποιούμενοι μηχανισμοί αυτοπροσοχής ενσωματώνουν ένα δομικό στοιχείο που κωδικοποιεί τη χρονική θέση των καρέ - μείζονος σημασίας κατά την παραγωγή μιας σύνοψης. Πειράματα σε δύο σύνολα δεδομένων (SumMe και TVSum) καταδεικνύουν την αποτελεσματικότητα του προτεινόμενου μοντέλου σε σύγκριση με τις υπάρχουσες μεθόδους αυτοπροσοχής και την ανταγωνιστικότητά του έναντι άλλων state-of-the-art εποπτευόμενων προσεγγίσεων δημιουργίας περιλήψεων. Μια μελέτη αφαίρεσης που εστιάζει στα κύρια προτεινόμενα δομικά στοιχεία, ειδικότερα τη χρήση καθολικών και τοπικών μηχανισμών αυτοπροσοχής πολλαπλών κεφαλών σε συνεργασία με ένα τμήμα κωδικοποίησης της απόλυτης θέσης, δείχνει τη σχετική συνεισφορά τους στη συνολική απόδοση.

# Summary. An optional shortened abstract.
summary: Εποπτευόμενη μέθοδος αυτόματης περίληψης βίντεο, βασισμένη στην αυτοπροσοχή.

tags: ["video summarization", "self-attention", "multi-head attention", "positional encoding", "supervised learning"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: Custom Link
#   url: http://example.org
  - name: Papers With Code
    url: https://tinyurl.com/pgl-sum

url_pdf: 'media/files/ism2021_preprint.pdf'
url_code: 'https://github.com/e-apostolidis/PGL-SUM'
url_dataset: ''
url_poster: ''
url_project: 'http://multimedia2.iti.gr/videosummarization/service/start.html'
url_slides: 'media/slides/ism2021_slides.pptx'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=LbjPLJzeNII'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
