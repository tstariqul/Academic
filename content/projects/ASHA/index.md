---
title: Brain Tissue Segmentation Using NeuroNet With Different Pre-processing Techniques
authors:
- F. I. Tushar, B. Alyafi, M. K. Hasan and L. Dahal
date: "2019-10-07"
doi: "10.1109/ICIEV.2019.8858515"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2019 Joint 8th International Conference on Informatics, Electronics & Vision (ICIEV) and 2019 3rd International Conference on Imaging, Vision & Pattern Recognition (icIVPR)*
publication_short: 2019 Joint 8th International Conference on Informatics, Electronics & Vision (ICIEV) and 2019 3rd International Conference on Imaging, Vision & Pattern Recognition (icIVPR), Spokane, WA, USA, 2019, pp. 223-227

abstract: Automatic segmentation of brain Magnetic Resonance Imaging (MRI) images is one of the vital steps for quantitative analysis of brain for further inspection. In this paper, NeuroNet has been adopted to segment the brain tissues (white matter (WM), grey matter (GM) and cerebrospinal fluid (CSF)) which uses Residual Network (ResNet) in encoder and Fully Convolution Network (FCN) in the decoder. To achieve the best performance, various hyper-parameters have been tuned, while, network parameters (kernel and bias) were initialized using the NeuroNet pre-trained model. Different pre-processing pipelines have also been introduced to get a robust trained model. The model has been trained and tested on IBSR18 data-set. To validate the research outcome, performance was measured quantitatively using Dice Similarity Coefficient (DSC) and is reported on average as 0.84 for CSF, 0.94 for GM, and 0.94 for WM. The outcome of the research indicates that for the IBSR18 data-set, pre-processing and proper tuning of hyper-parameters for NeuroNet model have improvement in DSC for the brain tissue segmentation.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Deep-learning
- Brain Tissue Segmentation
featured: true

links:
- name: Pre-print
  url: https://arxiv.org/abs/1904.00068
- name: Slides
  url: https://drive.google.com/open?id=1Kwhmt9qy2LgpjhbEdLaT2h1215JJHrYQ
url_pdf: https://ieeexplore.ieee.org/abstract/document/8858515
url_code: https://github.com/fitushar/Brain-Tissue-Segmentation-Using-Deep-Learning-Pipeline-NeuroNet



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Used architecture'
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
