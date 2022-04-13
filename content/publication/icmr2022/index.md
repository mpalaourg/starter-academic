---
title: "Summarizing Videos Using Concentrated Attention and Considering the Uniqueness and Diversity of the Video Frames"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Evlampios Apostolidis
- admin
- Vasileios Mezaris
- Ioannis Patras

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Int. Conference on Multimedia Retrieval 2022*
publication_short: In *ICMR2022*

abstract: In this work, we describe a new method for unsupervised video summarization. To overcome limitations of existing unsupervised video summarization approaches, that relate to the unstable training of Generator-Discriminator architectures, the use of RNNs for modeling long-range frames' dependencies and the ability to parallelize the training process of RNN-based network architectures, the developed method relies solely on the use of a self-attention mechanism to estimate the importance of video frames. Instead of simply modeling frames' dependencies based on global attention, our method integrates a concentrated attention mechanism that is able to focus on non-overlapping blocks in the main diagonal of the attention matrix, and to enrich the existing information by extracting and exploiting knowledge about the uniqueness and diversity of the associated frames of the video. In this way, our method makes better estimates about the significance of different parts of the video, and drastically reduces the number of learnable parameters. Experimental evaluations using two benchmarking datasets (SumMe and TVSum) show the competitiveness of the proposed method against other state-of-the-art unsupervised summarization approaches, and demonstrate its ability to produce video summaries that are very close to the human preferences. An ablation study that focuses on the introduced components, namely the use of concentrated attention in combination with attention-based estimates about the frames' uniqueness and diversity, shows their relative contributions to the overall summarization performance.

# Summary. An optional shortened abstract.
summary: An unsupervised self-attention-based method for automated video summarization.

tags: ["video summarization", "self-attention", "concentrated attention", "unsupervised learning", "transductive inference"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/e-apostolidis/CA-SUM'
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
