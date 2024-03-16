---
title: "HAM-TTS: Hierarchical Acoustic Modeling for Token-Based Zero-Shot Text-to-Speech with Model and Data Scaling"
authors:
  - Chunhui Wang
  - Chang Zeng
  - Bowen Zhang
  - Ziyang Ma
  - Yefan Zhu
  - Zifeng Cai
  - Jian Zhao
  - Zhonglin Jiang
  - Yong Chen
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
date: "2024-03-12T00:00:00Z"
doi: "10.48550/arXiv.2403.05989"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "In *ArXiv*"
publication_short: "In *ArXiv*"

abstract: "Token-based text-to-speech (TTS) models have emerged as a promising avenue for generating natural and realistic speech, yet they grapple with low pronunciation accuracy, speaking style and timbre inconsistency, and a substantial need for diverse training data. In response, we introduce a novel hierarchical acoustic modeling approach complemented by a tailored data augmentation strategy and train it on the combination of real and synthetic data, scaling the data size up to 650k hours, leading to the zero-shot TTS model with 0.8B parameters. Specifically, our method incorporates a latent variable sequence containing supplementary acoustic information based on refined self-supervised learning (SSL) discrete units into the TTS model by a predictor. This significantly mitigates pronunciation errors and style mutations in synthesized speech. During training, we strategically replace and duplicate segments of the data to enhance timbre uniformity. Moreover, a pretrained few-shot voice conversion model is utilized to generate a plethora of voices with identical content yet varied timbres. This facilitates the explicit learning of utterance-level one-to-many mappings, enriching speech diversity and also ensuring consistency in timbre. Comparative experiments (Demo page: https://anonymous.4open.science/w/ham-tts/)demonstrate our model's superiority over VALL-E in pronunciation precision and maintaining speaking style, as well as timbre continuity."

# Summary. An optional shortened abstract.
summary: 

tags:
- Speech Synthesis
- LLM
- GenAI
featured: true

links:
- name: ArXiv
  url: https://arxiv.org/abs/2403.05989v1
url_pdf: https://arxiv.org/pdf/2403.05989v1.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: https://anonymous.4open.science/w/ham-tts/
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
- TTS
- GenAI
- LLM

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
