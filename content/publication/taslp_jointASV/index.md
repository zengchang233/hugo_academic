---
title: "Joint Speaker Encoder and Neural Back-end Model for Fully End-to-End Automatic Speaker Verification with Multiple Enrollment Utterances"
authors:
- Chang Zeng
- Xiaoxiao Miao
- Xin Wang
- Erica Cooper
- Junichi Yamagishi
date: "2024-01-19T00:00:00Z"
doi: "10.1016/j.csl.2024.101619"

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
  url: https://www.sciencedirect.com/science/article/pii/S0885230824000020?via%3Dihub
url_pdf: https://pdf.sciencedirectassets.com/272453/AIP/1-s2.0-S0885230824000020/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEDkaCXVzLWVhc3QtMSJGMEQCIAycW%2Fvu1jRmgpZzXMhX5XCpehuG2Qvbt1j0gqDxmPd8AiAvq3hMvZ4M%2Fkk8%2BZJ9RdwaO9jP5Hyl444ij0mWRqWEPCq8BQji%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAUaDDA1OTAwMzU0Njg2NSIMhU%2BNUMezU9uoQf2LKpAFoaXsPwHe125vu7YhJFGkFFjSMz82cJFNgjx%2FAuMtnOF9lKRYnic4RT%2BJz5ZoEbLYesSzFDJMEPZAf9iHE7ByKjrte%2F%2BKho6sbrkF2lG8t5llINIRJd1Ms7uk92XQgQZsEUtMWrY6wgc66LnZuKRosduRg93%2FN49Q01eM59DK4dun8tBU7HNv9TR25xjO36072Lr%2BkqW%2BYqDC6cf%2BIejSsaTRPb%2BtDq9Yw%2F7FX%2FNQn4XCO9SfuoQMOR7%2BMDGu7qHsP4v6gkc6KhjLEgNumQ3r2%2FlfTVgpcBVo7YCUCLdPcbFfkYaOso34GFx150HmJ7y2yr1RgCOTq4LUN2h2aosUYkliFZJj4aOL9W6XL%2ByQ%2Fc3OYBIibA6rao0qA6%2FQhWNhyTQFOpXECX9BNi2pKoiKHmjQefvmMMDFMNixBgS7%2BZlDvPpgrjPQrElC%2FgHj4yNrFXqMOCAK%2B5btVNTHuM5XdgnILu%2BP23aFJDnwiMXlaG0yfTRtb96VnzPcxR%2FPFxb1wQX4bYVnEgoyrsV4KK0QxzD0fMTFuCBnJnONyC7w2PDQXJ%2FOlbU1wMXKiKdzMklWjPnEoHDJ%2FiA0kDf%2BMNBqGDIgs%2Fp8JqiiJ1FOuSmh105CSmjD%2B%2BUwKxNsH81mbAxGG2r0eSp6MNNfd5S6jErUKG361RwVWsoDicJacvDTFw0w0ikc%2BsIn5VroUv19v8uWWaGIPnr0B%2BdH2%2BhbVayxaznr3TnkcIWGA2%2B7oC7rkkw62uqlJcImnhFMjkgSz4XOrMEcRalXoRZMq2ZckwDF2UWqJZ96J4McdmbPE%2FxtD%2FUazTLOZSVtWBA0aWMylkmEol8ye%2BqxAvA7tAXH7QNsO1HHRGmFOGAG3gRQEo%2F1XDEw65GnrQY6sgHM5d0tvncJCg3uJPh63yE1GMpYZXSgseKDZikskNCXl25uOeS0kto%2BBYJNwg8A%2BiBYRquW%2Fx3%2Ba1SCnWhN1h%2FHvtAD72uNo6V0br6my2lXRJflraKfV70tSfEZBsVtsCer3uERQtMnYxg3vh4JFQ%2B5ugBmhsYf%2Bje04oLxJcxzcg8SkyjsJNY6T1yuD%2FNERhX%2BOflUkxkRXsXv5TNzD3dJh42fCtqH8w2N6QhGItPsVZFu&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240119T013635Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYQVZ5KNAP%2F20240119%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=4e9a1530cfac843890092007593421bec3414d0fa757743e7184f84012ed8324&hash=6edeb0c1fcf24a7fa54951a4346d6a17bbd63211dc52e9682df6638e32a75d1e&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0885230824000020&tid=spdf-9764f0ec-0b52-47b1-b710-369774c6fcaf&sid=11dfb75d3204814cce0816e1d326e8184a9bgxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=08135d555103535605&rr=847b58f9efaf80bf&cc=jp
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
