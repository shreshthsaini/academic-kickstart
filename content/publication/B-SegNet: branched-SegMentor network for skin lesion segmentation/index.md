---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "B-SegNet: branched-SegMentor network for skin lesion segmentation"
authors: [Shreshth Saini*, Young Seok Jeon, Mengling 'Mornin' Feng]
date: 2021-02-2021
doi: "10.1145/3450439.3451873"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-2021

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Association for Computing Machinery - Conference on Health, Inference, and Learning"
publication_short: "ACM-CHIL 2021"

abstract: "Melanoma is the most common form of cancer in the world. Early diagnosis of the disease and an accurate estimation of its size and shape are crucial in preventing its spread to other body parts. Manual segmentation of these lesions by a radiologist however is time consuming and error-prone. It is clinically desirable to have an automatic tool to detect malignant skin lesions from dermoscopic skin images. We propose a novel end-to-end convolution neural network(CNN) for a precise and robust skin lesion localization and segmentation. The proposed network has 3 sub-encoders branching out from the main encoder. The 3 sub-encoders are inspired from Coordinate Convolution, Hourglass and Octave Convolutional blocks: each sub-encoder summarizes different patterns and yet collectively aims to achieve a precise segmentation. We trained our segmentation model just on the ISIC 2018 dataset. To demonstrate the generalizability of our model, we evaluated our model on the ISIC 2018 and unseen datasets including ISIC 2017 and PH2. Our approach showed an average 5% improvement in performance over different datasets, while having less than half of the number of parameters when compared to other state-of-the-arts segmentation models."

# Summary. An optional shortened abstract.
summary: ""

tags: [CNN, Deep learning, Biomedical Image Analysis, Healthcare, Dice Similarity Coefficient]
categories: [Deep Learning, Healthcare Informatics]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source: https://dl.acm.org/doi/abs/10.1145/3450439.3451873
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
slides: ""
---
