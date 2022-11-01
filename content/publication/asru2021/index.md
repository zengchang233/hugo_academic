---
title: "DeepLip: A Benchmark for Deep Learning-Based Audio-Visual Lip Biometrics"
authors:
  - Meng Liu
  - Longbiao Wang
  - Kong Aik Lee
  - Hanyi Zhang
  - Chang Zeng
  - Jianwu Dang
date: "2021-12-13T00:00:00Z"
doi: "10.1109/ASRU51503.2021.9688240"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *2021 IEEE Automatic Speech Recognition and Understanding Workshop*"
publication_short: "In *ASRU*"

abstract: Audio-visual lip biometrics (AV-LB) has been an emerging biometrics technology that straddles auditory and visual speech processing. Previous works mainly focused on the front-end lip-based feature engineering combined with a shallow statistical back-end model. Over the past decade, convolutional neural network (CNN, or ConvNet) has been widely used and achieved good performance in computer vision and speech processing tasks. However, the lack of a sizeable public AV-LB database led to a stagnation in deep-learning exploration on AV-LB tasks. In addition to the dual audio-visual streams, one essential requirement on the video stream is the region of interest (ROI) around the lips has to be of sufficient resolution. To this end, we compile a moderate-size database using existing public databases. Using this database, we present a deep learning-based AV-LB benchmark, dubbed DeepLip 1 1 https://github.com/DanielMengLiu/DeepLip, realized with convolutional video and audio unimodal modules, and a multimodal fusion module. Our experiments show that DeepLip outperforms the traditional lip-biometrics system in context modeling and achieves over 50% relative improvements compared with its unimodal system, with an equal error rate of 0.75% and 1.11% on the test datasets, respectively.

# Summary. An optional shortened abstract.
summary: speaker recognition, audio-visual, lip biometrics, deep learning, visual speech.

tags:
- Speaker Recognition / Antispoofing
featured: false

links:
- name: ASRU Link
  url: https://ieeexplore.ieee.org/document/9688240
url_pdf: ''
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
