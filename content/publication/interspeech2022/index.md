---
title: 'Spoofing-Aware Attention based ASV Back-end with Multiple Enrollment Utterances and a Sampling Strategy for the SASV Challenge 2022'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chang Zeng
  - Lin Zhang
  - Meng Liu
  - Junichi Yamagishi

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-09-18'
doi: '10.21437/Interspeech.2022-10495'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-09-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Interspeech 2022*
publication_short: In *Interspeech 2022*

abstract: Current state-of-the-art automatic speaker verification (ASV) systems are vulnerable to presentation attacks, and several countermeasures (CMs), which distinguish bona fide trials from spoofing ones, have been explored to protect ASV. However, ASV systems and CMs are generally developed and optimized independently without considering their inter-relationship. In this paper, we propose a new spoofing-aware ASV back-end module that efficiently computes a combined ASV score based on speaker similarity and CM score. In addition to the learnable fusion function of the two scores, the proposed back-end module has two types of attention components, scaled-dot and feed-forward self-attention, so that intra-relationship information of multiple enrollment utterances can also be learned at the same time. Moreover, a new effective trials-sampling strategy is designed for simulating new spoofing-aware verification scenarios introduced in the Spoof-Aware Speaker Verification (SASV) challenge 2022. Combining the two types of scores using the proposed back-end optimized by using the sampling strategies, it is confirmed that the SASV-EER can be significantly reduced from 22.91\% to 1.19\% on the evaluation set of the ASVSpoof 2019 LA database. 

# Summary. An optional shortened abstract.
summary: Current state-of-the-art automatic speaker verification (ASV) systems are vulnerable to presentation attacks, and several countermeasures (CMs), which distinguish bona fide trials from spoofing ones, have been explored to protect ASV. However, ASV systems and CMs are generally developed and optimized independently without considering their inter-relationship. In this paper, we propose a new spoofing-aware ASV back-end module that efficiently computes a combined ASV score based on speaker similarity and CM score.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=gXxP1nn5X6E'

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

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
