---
title: "Joint Speaker Encoder and Neural Back-end Model for Fully End-to-End Automatic Speaker Verification with Multiple Enrollment Utterances"
authors:
- Chang Zeng
- Xiaoxiao Miao
- Xin Wang
- Erica Cooper
- Junichi Yamagishi
date: "2022-09-01T00:00:00Z"
doi: "10.48550/arXiv.2209.00485"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computer Speech & Language"
publication_short: "In *Computer Speech & Language*"

abstract: Conventional automatic speaker verification systems can usually be decomposed into a front-end model such as time delay neural network (TDNN) for extracting speaker embeddings and a back-end model such as statistics-based probabilistic linear discriminant analysis (PLDA) or neural network-based neural PLDA (NPLDA) for similarity scoring. However, the sequential optimization of the front-end and back-end models may lead to a local minimum, which theoretically prevents the whole system from achieving the best optimization. Although some methods have been proposed for jointly optimizing the two models, such as the generalized end-to-end (GE2E) model and NPLDA E2E model, all of these methods are designed for use with a single enrollment utterance. In this paper, we propose a new E2E joint method for speaker verification especially designed for the practical case of multiple enrollment utterances. In order to leverage the intra-relationship among multiple enrollment utterances, our model comes equipped with frame-level and utterance-level attention mechanisms. We also utilize several data augmentation techniques, including conventional noise augmentation using MUSAN and RIRs datasets and a unique speaker embedding-level mixup strategy for better optimization.

# Summary. An optional shortened abstract.
summary: neural network, automatic speaker verification, deep learning, attention, data augmentation.

tags:
- Speaker Recognition / Antispoofing
featured: false

links:
- name: CSL link
  url: https://arxiv.org/abs/2209.00485
url_pdf: https://arxiv.org/pdf/2209.00485.pdf
url_code: ''
url_dataset: 'http://openslr.org/82/'
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
