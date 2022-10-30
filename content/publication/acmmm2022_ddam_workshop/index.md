---
title: "Deep Spectro-temporal Artifacts for Detecting Synthesized Speech"
authors:
  - Xiaohui Liu
  - Meng Liu
  - Lin Zhang
  - Linjuan Zhang
  - Chang Zeng
  - Kai Li
  - Nan Li
  - Kong Aik Lee
  - Longbiao Wang
  - Jianwu Dang
date: "2022-10-10T00:00:00Z"
doi: "10.1145/3552466.3556527"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-10-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "In *DDAM 2022: Proceedings of the 1st International Workshop on Deepfake Detection for Audio Multimedia*"
publication_short: "In *DDAM 2022 Workshop*"

abstract: The Audio Deep Synthesis Detection (ADD) Challenge has been held to detect generated human-like speech. With our submitted system, this paper provides an overall assessment of track 1 (Low-quality Fake Audio Detection) and track 2 (Partially Fake Audio Detection). In this paper, spectro-temporal artifacts were detected using raw temporal signals, spectral features, as well as deep embedding features. To address track 1, low-quality data augmentation, domain adaptation via finetuning, and various complementary feature information fusion were aggregated in our system. Furthermore, we analyzed the clustering characteristics of subsystems with different features by visualization method and explained the effectiveness of our proposed greedy fusion strategy. As for track 2, frame transition and smoothing were detected using self-supervised learning structure to capture the manipulation of PF attacks in the time domain. We ranked 4th and 5th in track 1 and track 2, respectively.

# Summary. An optional shortened abstract.
summary: Singing voice synthesis, feed-forward transformer, generative adversarial network.

tags:
- Speaker Recognition / Antispoofing
featured: false

links:
- name: ACMMM page
  url: https://dl.acm.org/doi/abs/10.1145/3552466.3556527
url_pdf: https://arxiv.org/pdf/2210.14666.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- speaker_verification

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
