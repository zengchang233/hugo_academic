---
title: 'Data Augmentation Using McAdams-Coefficient-Based Speaker Anonymization for Fake Audio Detection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Kai Li, 
  - Sheng Li, 
  - Xugang Lu, 
  - Masato Akagi,
  -  Meng Liu, 
  - Lin Zhang, 
  - Chang Zeng, 
  - Longbiao Wang, 
  - Jianwu Dang, 
  - Masashi Unoki

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-09-18'
doi: '10.21437/Interspeech.2022-10088'

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

abstract: Fake audio detection (FAD) is a technique to distinguish synthetic speech from natural speech. In most FAD systems, removing irrelevant features from acoustic speech while keeping only robust discriminative features is essential. Intuitively, speaker information entangled in acoustic speech should be suppressed for the FAD task. Particularly in a deep neural network (DNN)-based FAD system, the learning system may learn speaker information from a training dataset and cannot generalize well on a testing dataset. In this paper, we propose to use the speaker anonymization (SA) technique to suppress speaker information from acoustic speech before inputting it into a DNN-based FAD system. We adopted the McAdams-coefficient-based SA (MC-SA) algorithm, and this is expected that the entangled speaker information will not be involved in the DNN-based FAD learning. Based on this idea, we implemented a light convolutional neural network bidirectional long short-term memory (LCNN-BLSTM)-based FAD system and conducted experiments on the Audio Deep Synthesis Detection Challenge (ADD2022) datasets. The results showed that removing the speaker information from acoustic speech improved the relative performance in the first track of ADD2022 by 17.66%.

# Summary. An optional shortened abstract.
summary: fake audio detection, data augmentation, McAdams coefficients, speaker anonymization.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.isca-speech.org/archive/pdfs/interspeech_2022/li22o_interspeech.pdf'
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

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
