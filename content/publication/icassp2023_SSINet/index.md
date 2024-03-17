---
title: "SSI-Net: A Multi-Stage Speech Signal Improvement System for ICASSP 2023 SSI Challenge"
authors:
  - Weixin Zhu
  - Zilin Wang
  - Jiuxin Lin
  - Chang Zeng
  - Tao Yu
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: "2023-04-10"
doi: "10.1109/ICASSP49357.2023.10094845"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-10"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE International Conference on Acoustics, Speech and Signal Processing 2023*
publication_short: In *ICASSP 2023*

abstract: The ICASSP 2023 Speech Signal Improvement (SSI) Challenge concentrates on improving the speech signal quality of real-time communication (RTC) systems. In this paper, we introduce the speech signal improvement network (SSI-Net) submitted to the ICASSP 2023 SSI Challenge, which satisfies the real-time condition. The proposed SSI-Net has a multi-stage architecture. We present the time-domain restoration generative adversarial network (TRGAN) in the first restoration stage for speech restoration. Regarding the second enhancement stage, we employ a lightweight multi-scale temporal frequency convolutional network with axial self-attention (MTFAA-Net) called MTFAA-Lite to enhance the fullband speech. In the subjective test on the SSI Challenge blind test set, our proposed SSI-Net yields a P.835 overall mean opinion score (MOS) of 3.190 and a P.804 overall MOS of 3.178, which eventually takes the 3rd place in tracks 1&2.

# Summary. An optional shortened abstract.
summary: We introduce SSI-Net, our submission to the ICASSP 2023 Speech Signal Improvement (SSI) Challenge, designed for real-time communication systems. SSI-Net features a multi-stage architecture, beginning with a time-domain restoration generative adversarial network (TRGAN) for initial speech restoration. In the second stage, we use a lightweight multi-scale temporal frequency convolutional network with axial self-attention (MTFAA-Lite) for fullband speech enhancement. In subjective tests on the SSI Challenge blind test set, SSI-Net achieved a P.835 mean opinion score (MOS) of 3.190 and a P.804 MOS of 3.178, ranking 3rd in tracks 1&2.

tags:
- Speech Enhancement
featured: false

links:
- name: ICASSP Link
  url: https://ieeexplore.ieee.org/document/10094845
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
- genai

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
