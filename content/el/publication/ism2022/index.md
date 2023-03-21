---
title: "Explaining video summarization based on the focus of attention"

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

date: "2022-12-06T00:00:00Z"
doi: "10.1109/ISM55400.2022.00029"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Στο *IEEE Int. Symposium on Multimedia (ISM) 2022*
publication_short: Στο *ISM2022*

abstract: Σε αυτό το άρθρο προτείνουμε μια μέθοδο για την επεξήγηση της περίληψης ενός βίντεο. Ξεκινάμε διατυπώνοντας το πρόβλημα ως τη δημιουργία μιας μάσκας επεξήγησης που υποδεικνύει τα μέρη του βίντεο που επηρέασαν περισσότερο τις εκτιμήσεις ενός δικτύου περίληψης βίντεο, σχετικά με τη σημασία των καρέ του. Στη συνέχεια, εξηγούμε πώς μπορεί να χρησιμοποιηθεί ο τυπικός αγωγός ανάλυσης δικτύων περίληψης βίντεο που βασίζονται στην αυτοπροσοχή για τον καθορισμό σημάτων επεξήγησης, και εξετάζουμε διάφορα σήματα που βασίζονται στην προσοχή που έχουν μελετηθεί ως επεξηγήσεις στον τομέα του NLP. Αξιολογούμε την απόδοση αυτών των σημάτων διερευνώντας τη σχέση εισόδου-εξόδου του δικτύου περίληψης βίντεο σύμφωνα με διαφορετικές συναρτήσεις αντικατάστασης, και χρησιμοποιώντας μετρικές που ποσοτικοποιούν την ικανότητα των επεξηγήσεων να εντοπίσουν τα μέρη ενός βίντεο με τη μεγαλύτερη και τη μικρότερη επιρροή. Εκτελούμε πειράματα χρησιμοποιώντας ένα δίκτυο που βασίζεται στην αυτοπροσοχή (CA-SUM) και δύο σύνολα δεδομένων (SumMe και TVSum). Οι αξιολογήσεις μας υποδεικνύουν την προχωρημένη απόδοση των επεξηγήσεων που σχηματίζονται χρησιμοποιώντας τα εγγενή βάρη προσοχής, και καταδεικνύουν την ικανότητα της μεθόδου μας να εξηγεί τα αποτελέσματα της περίληψης βίντεο χρησιμοποιώντας ενδείξεις σχετικά με την εστίαση του μηχανισμού προσοχής.

# Summary. An optional shortened abstract.
summary: Μέθοδος για την επεξήγηση της περίληψης ενός βίντεο.

tags: ["explainable ai", "video summarization", "self-attention", "concentrated attention", "ca-sum", "evaluation metrics"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
# - name: Custom Link
#   url: http://example.org
# - name: Papers With Code
#   url: 

url_pdf: 'en/media/files/ism2022_preprint.pdf'
url_code: 'https://github.com/e-apostolidis/XAI-SUM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
