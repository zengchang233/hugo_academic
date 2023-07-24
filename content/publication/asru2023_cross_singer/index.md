---
title: "CrossSinger: A Cross-Lingual Multi-Singer High-Fidelity Singing Voice Synthesizer Trained on Monolingual Singers"
authors:
  - Xintong Wang
  - Chang Zeng
  - Jun Chen
  - Chunhui Wang
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
date: "2023-7-17T00:00:00Z"
doi: "10.48550/arXiv.2210.12740"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-24T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "In *ArXiv*"
publication_short: "In *ArXiv*"

abstract: It is challenging to build a multi-singer high-fidelity singing voice synthesis system with cross-lingual ability by only using monolingual singers in the training stage. In this paper, we propose CrossSinger, which is a cross-lingual singing voice synthesizer based on Xiaoicesing2. Specifically, we utilize International Phonetic Alphabet to unify the representation for all languages of the training data. Moreover, we leverage conditional layer normalization to incorporate the language information into the model for better pronunciation when singers meet unseen languages. Additionally, gradient reversal layer (GRL) is utilized to remove singer biases included in lyrics since all singers are monolingual, which indicates singer's identity is implicitly associated with the text. The experiment is conducted on a combination of three singing voice datasets containing Japanese Kiritan dataset, English NUS-48E dataset, and one internal Chinese dataset. The result shows CrossSinger can synthesize high-fidelity songs for various singers with cross-lingual ability, including code-switch cases.

# Summary. An optional shortened abstract.
summary: Generative adversarial network, Acoustic model, Cross-lingual, Multi-singer, Singing Voice Synthesis.

tags:
- Singing Voice Synthesis
featured: false

links:
- name: ArXiv Link
  url: https://arxiv.org/abs/2210.12740
url_pdf: https://arxiv.org/pdf/2210.12740.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: https://wavelandspeech.github.io/CrossSinger/
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
- svs

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
