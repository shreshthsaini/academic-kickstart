---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Detector-SegMentor Network for Skin Lesion Localization and Segmentation"
subtitle: ""
abstract: "Melanoma is a life-threatening form of skin cancer when left undiagnosed at the early stages. Although there are more cases of non-melanoma cancer than melanoma cancer, melanoma cancer is more deadly. Early detection of melanoma is crucial for the timely diagnosis of melanoma cancer and prohibit its spread to distant body parts. Segmentation of skin lesion is a crucial step in the classification of melanoma cancer from the cancerous lesions in dermoscopic images. Manual segmentation of dermoscopic skin images is very time consuming and error-prone resulting in an urgent need for an intelligent and accurate algorithm. In this study, we propose a simple yet novel network-in-network convolution neural network(CNN) based approach for segmentation of the skin lesion. A Faster Region-based CNN (Faster RCNN) is used for preprocessing to predict bounding boxes of the lesions in the whole image which are subsequently cropped and fed into the segmentation network to obtain the lesion mask. The segmentation network is a combination of the UNet and Hourglass networks. We trained and evaluated our models on ISIC 2018 dataset and also crossvalidated on PH2 and ISBI 2017 datasets. Our proposed method surpassed the state-of-the-art with Dice Similarity Coefficient of 0.915 and Accuracy 0.959 on ISIC 2018 dataset and Dice Similarity Coefficient of 0.947 and Accuracy 0.971 on ISBI 2017 dataset"
authors: [Shreshth Saini*, Divij Gupta, Anil Kumar Tiwari]
tags: [CNN, Faster RCNN, Segmentation, Dermoscopic, Melanoma, Dice Similarity Coefficient]
categories: [Deep Learning, Medical Imaging Analysis]
publication_types: ["1"]
publication_short: "NCVPRIPG, 2019"

date: 2020-08-14T21:21:53+05:30
lastmod: 2020-08-14T21:21:53+05:30
featured: true
draft: false
url_source :  https://link.springer.com/chapter/10.1007/978-981-15-8697-2_55
url_custom : [{name = "details", url = "/publication/PixlSegNetDetector-SegMentor-Network-for-Skin-Lesion-Localization-and-Segmentation/"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
This work was presented at NCVPRIPG-19, which is a sister conference of ICVGIP. Top Indian conference on Computer Vision, Pattern Recognition, Image Processing, and Graphics.
