---
title: Weakly supervised 3D classification of chest CT using aggregated multi-resolution deep segmentation features
authors:
- "*Anindo Saha, *Fakrul I. Tushar, Khrystyna Faryna, Vincent M. D'Anniballe, Rui Hou, Maciej A. Mazurowski, Geoffrey D. Rubin M.D., Joseph Y. Lo (* Author with equal contribution)"
date: "2020-03-02"
doi: "10.1117/12.2550857"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-02"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proc. SPIE 11314, Medical Imaging 2020: Computer-Aided Diagnosis, 1131408"
publication_short: "Proc. SPIE 11314, Medical Imaging 2020: Computer-Aided Diagnosis, 1131408"

abstract: Weakly supervised disease classification of CT imaging suffers from poor localization owing to case-level annotations, where even a positive scan can hold hundreds to thousands of negative slices along multiple planes. Furthermore, although deep learning segmentation and classification models extract distinctly unique combinations of anatomical features from the same target class(es), they are typically seen as two independent processes in a computer-aided diagnosis (CAD) pipeline, with little to no feature reuse. In this research, we propose a medical classifier that leverages the semantic structural concepts learned via multi-resolution segmentation feature maps, to guide weakly supervised 3D classification of chest CT volumes. Additionally, a comparative analysis is drawn across two different types of feature aggregation to explore the vast possibilities surrounding feature fusion. Using a dataset of 1593 scans labeled on a case-level basis via rule-based model, we train a dual-stage convolutional neural network (CNN) to perform organ segmentation and binary classification of four representative diseases (emphysema, pneumonia/atelectasis, mass and nodules) in lungs. The baseline model, with separate stages for segmentation and classification, results in AUC of 0.791. Using identical hyperparameters, the connected architecture using static and dynamic feature aggregation improves performance to AUC of 0.832 and 0.851, respectively. This study advances the field in two key ways. First, case-level report data is used to weakly supervise a 3D CT classifier of multiple, simultaneous diseases for an organ. Second, segmentation and classification models are connected with two different feature aggregation strategies to enhance the classification performance.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Deep-learning
- Segmentation
- Weakly-supervised classification
- DenseVnet
- Resnet3D
featured: true

links:
- name: Slides
  url: https://drive.google.com/open?id=1pc3FN_z2fQmhCdaXTbOJVTCc1xI4xTsu
url_pdf: https://www.researchgate.net/publication/339956486_Weakly_Supervised_3D_Classification_of_Chest_CT_using_Aggregated_Multi-Resolution_Deep_Segmentation_Features
url_code: https://github.com/fitushar/Brain-Tissue-Segmentation-Using-Deep-Learning-Pipeline-NeuroNet
url_video: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11314/1131408/Weakly-supervised-3D-classification-of-chest-CT-using-aggregated-multi/10.1117/12.2550857.short?SSO=1&tab=ArticleLink



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Proposed CAD'
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
