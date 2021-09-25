+++
title = "PixISegNet: Pixel Level Iris Segmentation Network using Convolutional Encoder-Decoder with Stacked Hourglass Bottleneck"
date = 2019-06-06
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [Ranjeet Ranjan Jha, Gaurav Jaswal, Shreshth Saini, Divij Gupta, Aditya Nigam]
#
# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]
#
# Publication name and optional abbreviated version.
publication = "The Institution of Engineering and Technology - Biometrics"
publication_short = "IET-Biometrics, 2019"
#
# Abstract and optional shortened version.
abstract = "Biometric segmentation to obtain the region of interest under non-cooperative conditions is a fundamental and essential problem in biometric research. In the past few decades, researchers have widely studied this problem. For instance, non-ideal iris images cause poor segmentation in case of non-regular reflections, blurred boundaries, eyelids occlusion, and off-angle rotations. In this paper, we present a new iris ROI segmentation algorithm using a deep convolutional neural network to achieve the state-of-the-art segmentation performance on well-known iris image datasets. Our model surpasses the performance of state- of-the-art Iris-DenseNet framework by applying several strategies, including multi-scale/ multi-orientation training, model training from scratch, and proper hyper-parameterization of crucial parameters. The proposed PixISegNet consists of an autoencoder which primarily uses long and short skip connections and a stacked hourglass network between encoder and decoder. There is a continuous scale up-down in stacked hourglass networks, which helps in extracting features at multiple scales and robustly segments the iris even in an occluded environment. Furthermore, cross entropy loss and content loss optimizes the proposed model. The content loss considers the high-level features, thus operating at a different scale of abstraction, which compliments the cross-entropy loss, which considers pixel-to-pixel classification loss. Additionally, we have checked the robustness of the proposed network by rotating images to certain degrees with a change in the aspect ratio along with blurring and change in contrast. Experimental results on the various iris characteristics demonstrate the superiority of the proposed method over state-of-the-art iris segmentation methods considered in this paper. In order to demonstrate the network generalization, we deploy a very stringent T OT A (i.e train once test all) strategy. Our proposed method achieves E1 scores of 0.00672, 0.00916 and 0.00117 on UBIRIS-V2, IIT-D and CASIA V3.0 Interval datasets respectively. Moreover, such a deep convolutional neural network for segmentation when included in an end-to-end iris recognition system with a siamese based matching network will augment the performance of the siamese network. It facilitates the siamese matching network by selectively removing all of the unwanted (non-iris) pixels, to learn the salient iris features and provide a better recognition performance."

# abstract_short = "Robust Iris Segmentation network"
#
# Is this a featured publication? (true/false)
 featured = false
 tags = ["CNN", "Segmentation", "Biometric", "Iris", "Non-ideal", "Dice Similarity Coefficient"]
 categories = ["Deep Learning", "Biometrics"]


## Projects (optional).
##   Associate this publication with one or more of your projects.
##   Simply enter your project's folder or file name without extension.
##   E.g. `projects = ["deep-learning"]` references 
##   `content/project/deep-learning/index.md`.
##   Otherwise, set `projects = []`.
##projects = []
#
## Slides (optional).
##   Associate this page with Markdown slides.
##   Simply enter your slide deck's filename without extension.
##   E.g. `slides = "example-slides"` references 
##   `content/slides/example-slides.md`.
##   Otherwise, set `slides = ""`.
##slides = ""
#
## Tags (optional).
##   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
##tags = []
#
# Links (optional).
#url_pdf =
#url_preprint = ""
#url_code = ""
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = ""
#url_source = https://ietresearch.onlinelibrary.wiley.com/doi/10.1049/iet-bmt.2019.0025
#
# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "details", url = "/publication/PixlSegNet/"}]
#
## Digital Object Identifier (DOI)
#doi = ""
#
## Featured image
## To use, add an image named `featured.jpg/png` to your page's folder. 
#[image]
#  # Caption (optional)
#  caption = ""
#
#  # Focal point (optional)
#  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
#  focal_point = ""
+++

