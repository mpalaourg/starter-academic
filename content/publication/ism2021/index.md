---
title: "Combining Global and Local Attention with Positional Encoding for Video Summarization"

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
publication: In *IEEE Int. Symposium on Multimedia (ISM) 2021*
publication_short: In *ISM2021*

abstract: This paper presents a new method for supervised video summarization. To overcome drawbacks of existing RNN-based summarization architectures, that relate to the modeling of long-range frames' dependencies and the ability to parallelize the training process, the developed model relies on the use of self-attention mechanisms to estimate the importance of video frames. Contrary to previous attention-based summarization approaches that model the frames' dependencies by observing the entire frame sequence, our method combines global and local multi-head attention mechanisms to discover different modelings of the frames' dependencies at different levels of granularity. Moreover, the utilized attention mechanisms integrate a component that encodes the temporal position of video frames - this is of major importance when producing a video summary. Experiments on two datasets (SumMe and TVSum) demonstrate the effectiveness of the proposed model compared to existing attention-based methods, and its competitiveness against other state-of-the-art supervised summarization approaches. An ablation study that focuses on our main proposed components, namely the use of global and local multi-head attention mechanisms in collaboration with an absolute positional encoding component, shows their relative contributions to the overall summarization performance.

# Summary. An optional shortened abstract.
summary: Α supervised self-attention-based method for automated video summarization.

tags: ["video summarization", "self-attention", "multi-head attention", "positional encoding", "supervised learning"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
- name: PwC
  url: 'https://tinyurl.com/pgl-sum'

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
