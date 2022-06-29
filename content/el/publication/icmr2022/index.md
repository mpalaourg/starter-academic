---
title: "Summarizing Videos using Concentrated Attention and Considering the Uniqueness and Diversity of the Video Frames"

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

date: "2022-06-27T00:00:00Z"
doi: "10.1145/3512527.3531404"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Στο *ACM Int. Conference on Multimedia Retrieval 2022*
publication_short: Στο *ICMR2022*

abstract: Σε αυτήν την εργασία, περιγράφουμε μια καινούργια μέθοδο για τη δημιουργία περιλήψεων βίντεο χωρίς επίβλεψη. Για να ξεπεραστούν οι περιορισμοί των υφιστάμενων προσεγγίσεων δημιουργίας περιλήψεων χωρίς επίβλεψη, σχετικά με την ασταθή εκπαίδευση των Generator-Discriminator αρχιτεκτονικών, τη χρήση RNNs για τη μοντελοποίηση εξαρτήσεων μεγάλης εμβέλειας των καρέ και την ικανότητα παραλληλοποίησης της εκπαίδευσης αρχιτεκτονικών που βασίζονται σε RNNs, η μέθοδος μας βασίζεται αποκλειστικά στη χρήση ενός μηχανισμού αυτοπροσοχής για την εκτίμηση της σπουδαιότητας των καρέ του βίντεο. Αντί να μοντελοποιούμε απλώς τις εξαρτήσεις των καρέ με βάση την καθολική προσοχή, η μέθοδός μας ενσωματώνει έναν μηχανισμό συγκεντρωμένης προσοχής που είναι σε θέση να εστιάζει σε μη επικαλυπτόμενα μπλοκ στην κύρια διαγώνιο του πίνακα προσοχής και να εμπλουτίζει την υπάρχουσα πληροφορία εξάγοντας και αξιοποιώντας γνώση σχετικά με τη μοναδικότητα και την ποικιλομορφία των σχετικών καρέ του βίντεο. Με αυτόν τον τρόπο, η μέθοδός μας κάνει καλύτερες εκτιμήσεις σχετικά με τη σημαντικότητα διαφορετικών τμημάτων του βίντεο και μειώνει δραστικά τον αριθμό των παραμέτρων του δικτύου. Πειραματικές αξιολογήσεις που χρησιμοποιούν δύο σύνολα δεδομένων (SumMe και TVSum) δείχνουν την ανταγωνιστικότητα της προτεινόμενης μεθόδου έναντι άλλων state-of-the-art προσεγγίσεων δημιουργίας περιλήψεων χωρίς επίβλεψη και καταδεικνύουν την ικανότητά της να παράγει περιλήψεις βίντεο που είναι πολύ κοντά στις ανθρώπινες προτιμήσεις. Μια μελέτη αφαίρεσης που επικεντρώνεται στα προτεινόμενα δομικά στοιχεία, ειδικότερα τη χρήση της συγκεντρωμένης προσοχής σε συνδυασμό με εκτιμήσεις σχετικά με τη μοναδικότητα και την ποικιλομορφία των πλαισίων, δείχνει τη σχετική συνεισφορά τους στη συνολική απόδοση.

# Summary. An optional shortened abstract.
summary: Μη εποπτευόμενη μέθοδος αυτόματης περίληψης βίντεο, βασισμένη στην αυτοπροσοχή.

tags: ["video summarization", "self-attention", "concentrated attention", "unsupervised learning", "transductive inference"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# Custom links (uncomment lines below)
links:
# - name: Custom Link
#   url: http://example.org
  - name: Papers With Code
    url: https://tinyurl.com/icmr2022-ca-sum

url_pdf: 'en/media/files/icmr2022_preprint.pdf'
url_code: 'https://github.com/e-apostolidis/CA-SUM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'en/media/slides/icmr2022_slides.pptx'
url_source: ''
url_video: 'https://dl.acm.org/doi/10.1145/3512527.3531404#sec-supp'

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
