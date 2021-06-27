---
title: Classification of Chest CT Using Case-level Weak Supervision
authors:
- "Ruixiang Tang, Fakrul Islam Tushar, Songyue Han, Rui Hou, Geoffrey D. Rubin, Joseph Y. Lo"
date: "2019-03-13"
doi: "10.1117/12.2513576"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-04"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proc. SPIE 10950, Medical Imaging 2019: Computer-Aided Diagnosis, 1095017 (13 March 2019)"
publication_short: "Proc. SPIE 10950, Medical Imaging 2019: Computer-Aided Diagnosis, 1095017 (13 March 2019)"

abstract: "Our goal is to investigate using only case-level labels extracted automatically from radiology reports to construct a multi-disease classifier for CT scans with deep learning method. We chose four lung diseases as a start: atelectasis, pulmonary edema, nodule and pneumonia. From a dataset of approximately 5,000 chest CT cases from our institution, we used a rule-based model to analyze those radiologist reports, labeling disease by text mining to identify cases with those diseases. From those results, we randomly selected the following mix of cases: 275 normal, 170 atelectasis, 175 nodule, 195 pulmonary edema, and 208 pneumonia. As a key feature of this study, each chest CT scan was represented by only 10 axial slices (taken at regular intervals through the lungs), and furthermore all slices shared the same label based on the radiology report. So the label was weak, because often disease will not appear in all slices. We used ResNet-50[1] as our classification model, with 4-fold cross-validation. Each slice was analyzed separately to yield a slice-level performance. For each case, we chose the 5 slices with highest probability and used their mean probability as the final patient-level probability. Performance was evaluated using the receiver operating characteristic (ROC) area under the curve (AUC). For the 4 diseases separately, the slice-based AUCs were 0.71 for nodule, 0.79 for atelectasis, 0.96 for edema, and 0.90 for pneumonia. The patient-based AUC were 0.74 for nodule, 0.83 for atelectasis, 0.97 for edema, and 0.91 for pneumonia. We backprojected the activations of last convolution layer and the weights from prediction layer to synthesize a heat map [2] . This heat map could be an approximate disease detector, also could tell us feature patterns which ResNet-50 focus on"

# Summary. An optional shortened abstract.
summary: ''

tags:
- Deep-learning
- NLP
- Rule-Based Model
- Classification
featured: true

links:
- name: Slides
  url: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10950/1095017/Classification-of-chest-CT-using-case-level-weak-supervision/10.1117/12.2513576.full?sessionGUID=d883c9d9-02bc-9993-ced2-68bead49a285&sessionGUID=d883c9d9-02bc-9993-ced2-68bead49a285&webSyncID=0ce46e9e-6ec7-a49d-ab6a-0cbad059329a&SSO=1
url_pdf: https://drive.google.com/open?id=117cPie0MzPBXm8fvhRJCcrg5si1PXwtm
url_video: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10950/1095017/Classification-of-chest-CT-using-case-level-weak-supervision/10.1117/12.2513576.full?sessionGUID=d883c9d9-02bc-9993-ced2-68bead49a285&sessionGUID=d883c9d9-02bc-9993-ced2-68bead49a285&webSyncID=0ce46e9e-6ec7-a49d-ab6a-0cbad059329a&SSO=1
url_code: https://github.com/fitushar/Classification-of-chest-CT-using-caselevel-weak-supervision



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Proposed Diagnosis'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
