---
title: 'Attention Back-end for Automatic Speaker Verification with Multiple Enrollment Utterances'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chang Zeng
  - Xin Wang
  - Erica Cooper
  - Xiaoxiao Miao
  - Junichi Yamagishi

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-05-23'
doi: '10.1109/ICASSP43922.2022.9746688'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Acoustics, Speech and Signal Processing 2022*
publication_short: In *ICASSP 2022*

abstract: Probabilistic linear discriminant analysis (PLDA) or cosine similarity has been widely used in traditional speaker verification systems as a back-end technique to measure pairwise similarities. To make better use of multiple enrollment utterances, we propose a novel attention back-end model that is applied to the utterance-level features. Specifically, we use scaled-dot self-attention and feed-forward self-attention networks as architectures that learn the intra-relationships of enrollment utterances. To verify the proposed model, we conduct a series of experiments on the CNCeleb and VoxCeleb datasets by combining them with several state-of-the-art speaker encoders including TDNN and ResNet. Experimental results obtained using multiple enrollment utterances on CNCeleb show that the proposed attention back-end model leads to lower EER and minDCF scores than its PLDA and cosine similarity counterparts for each speaker encoder, and an experiment on VoxCeleb demonstrates that our model can be used even for a single enrollment case. 

# Summary. An optional shortened abstract.
summary: Probabilistic linear discriminant analysis (PLDA) or cosine similarity has been widely used in traditional speaker verification systems as a back-end technique to measure pairwise similarities. To make better use of multiple enrollment utterances, we propose a novel attention back-end model that is applied to the utterance-level features. Specifically, we use scaled-dot self-attention and feed-forward self-attention networks as architectures that learn the intra-relationships of enrollment utterances.

tags: Speaker Recognition / Antispoofing

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: ICASSP Link
  url: https://ieeexplore.ieee.org/document/9746688

url_pdf: 'https://arxiv.org/pdf/2104.01541.pdf'
url_code: 'https://github.com/nii-yamagishilab/Attention_Backend_for_ASV'
url_dataset: 'http://openslr.org/82/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=LdZM2yiWHaw'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
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

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
