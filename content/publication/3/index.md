---
title: Attention-guided classification of abnormalities in semi-structured computed tomography reports
authors:
- "Khrystyna Faryna, Fakrul I. Tushar, Khrystyna Faryna, Vincent M. D'Anniballe, Rui Hou, Geoffrey D. Rubin M.D., Joseph Y. Lo"
date: "2020-03-16"
doi: "10.1117/12.2551370"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-03"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proc. SPIE 11314, Medical Imaging 2020: Computer-Aided Diagnosis, 113141P"
publication_short: "Proc. SPIE 11314, Medical Imaging 2020: Computer-Aided Diagnosis, 113141P"

abstract: "Lack of annotated data is a major challenge to machine learning algorithms, particularly in the field of radiology. Algorithms that can efficiently extract labels in a fast and precise manner are in high demand. Weak supervision is a compromise solution, particularly, when dealing with imaging modalities like Computed Tomography (CT), where the number of slices can reach 1000 per case. Radiology reports store crucial information about clinicians’ findings and observations in CT slices. Automatic generation of labels from CT reports is not a trivial task due to the complexity of sentences and diversity of expression in free-text narration. In this study, we focus on abnormality classification in lungs, liver and kidneys. Firstly, a rule-based model is used to extract weak labels at the case level. Afterwards, attention guided recurrent neural network (RNN) is trained to perform binary classification of radiology reports in terms of whether the organ is normal or abnormal. Additionally, a multi-label RNN with attention mechanism is trained to perform binary classification by aggregating its output for four representative diseases (lungs: emphysema, mass-nodule, effusion and atelectasis-pneumonia; liver: dilatation, fatty infiltration-steatosis, calcification-stone-gallstone, lesion-mass; kidneys: atrophy, cyst, stone-calculi, lesion) into a single abnormal class. Performance has been evaluated using the receiver operating characteristic (ROC) area under the curve (AUC) on 274, 306 and 278 reports for lungs, liver and kidneys correspondingly, manually annotated by radiology experts. The change in performance was evaluated for different sizes of training dataset for lungs. The AUCs of multi-label pretrained models: lungs - 0.929, liver - 0.840, kidney - 0.844; multi-label models: lungs - 0.903, liver - 0.848, kidney - 0.906; binary pretrained models: lungs - 0.922, liver - 0.826, kidneys - 0.928."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Deep-learning
- NLP
- Rule-Based Model
featured: true

links:
- name: Slides
  url: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11314/113141P/Attention-guided-classification-of-abnormalities-in-semi-structured-computed-tomography/10.1117/12.2551370.short
url_pdf: https://drive.google.com/open?id=1CUlLUc630ZPDLWX7PAnlH3bZGufTZtR3
url_video: https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11314/113141P/Attention-guided-classification-of-abnormalities-in-semi-structured-computed-tomography/10.1117/12.2551370.short



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Proposed Rule-Based Model'
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
