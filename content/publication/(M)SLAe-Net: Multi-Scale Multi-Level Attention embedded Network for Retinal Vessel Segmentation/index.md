---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "(M)SLAe-Net: Multi-Scale Multi-Level Attention embedded Network for Retinal Vessel Segmentation"
authors: [Shreshth Saini*, Geetika Agrawal]
date: 2021-08-14T21:21:53+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-08-1

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "9th IEEE INTERNATIONAL CONFERENCE ON HEALTHCARE INFORMATICS"
publication_short: "IEEE-ICHI 2021"

abstract: "Segmentation plays a crucial role in diagnosis. Studying the retinal vasculatures from fundus images help identify early signs of many crucial illnesses such as diabetic retinopathy. Due to the varying shape, size, and patterns of retinal vessels, along with artefacts and noises in fundus images, no one-stage method can accurately segment retinal vessels. In this work, we propose a multi-scale, multi-level attention embedded CNN architecture ((M)SLAe-Net) to address the issue of multi-stage processing for robust and precise segmentation of retinal vessels. We do this by extracting features at multiple scales and multiple levels of the network, enabling our model to holistically extracts the local and global features. Multi-scale features are extracted using our novel dynamic dilated pyramid pooling (D-DPP) module. We also aggregate the features from all the network levels. These effectively resolved the issues of varying shapes and artefacts and hence the need for multiple stages. To assist in better pixel-level classification, we use the Squeeze and Attention(SA) module, a smartly adapted version of the Squeeze and Excitation(SE) module for segmentation tasks in our network to facilitate pixel-group attention. Our unique network design and novel D-DPP module with efficient task-specific loss function for thin vessels enabled our model for better cross data performance. Exhaustive experimental results on DRIVE, STARE, HRF, and CHASE-DB1 show the superiority of our method."

# Summary. An optional shortened abstract.
summary: ""

tags: [CNN, Deep learning, Biomedical Image Analysis, Healthcare]
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
url_source: https://doi.org/10.1109/ICHI52183.2021.00042
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
