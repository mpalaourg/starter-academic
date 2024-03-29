---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: "Data Scientist"
    company: "EY"
    company_url: "https://www.ey.com/en_gr"
    location: "Thessaloniki, Central Macedonia, Greece"
    date_start: "2023-09-04"
    date_end: ""
    description: ""

  - title: "Deep Learning Engineer & Researcher Assistant"
    company: "Intelligent Digital Transformation Laboratory (CERTH - ITI)"
    company_url: "http://idt.iti.gr/"
    location: "Thessaloniki, Central Macedonia, Greece"
    date_start: "2021-01-04"
    date_end: "2022-08-31"
    description: "Our main goal was to generate a concise synopsis that conveys the important parts of a full-length video automatically, either in a supervised or an unsupervised way. More precisely, using an Encoder-Decoder architecture we were trying to model the temporal dependency among video frames and learn how to estimate frames’ importance. At first, we were mostly using Recurrent Architectures, like vanilla RNNs and LSTMs, and Generative Adversarial Networks (GANs), where an LSTM-based VAE (Generator) tries to confuse the Discriminator about the originality of the produced summaries. Despite the success of these architectures, problems like limited parallelization and challenging training, led us in exploring Attention Mechanisms and Transformers models for our ongoing works. Finally, all our developments are open-source and based on PyTorch."
---
