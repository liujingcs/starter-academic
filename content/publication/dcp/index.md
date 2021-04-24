---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Discrimination-aware Channel Pruning for Deep Neural Networks"
authors: [**Zhuangwei Zhuang**, **Mingkui Tan**, **Bohan Zhuang**, **Jing Liu**, Yong Guo, Qingyao Wu, Junzhou Huang, Jinhui Zhu]
date: 2018-12-03T15:25:37+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2018-12

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Advances in Neural Information Processing Systems 2018"
publication_short: "NeurIPS 2018"

abstract: "Channel pruning is one of the predominant approaches for deep model compression. Existing pruning methods either train from scratch with sparsity constraints on channels, or minimize the reconstruction error between the pre-trained feature maps and the compressed ones. Both strategies suffer from some limitations: the former kind is computationally expensive and difficult to converge, whilst the latter kind optimizes the reconstruction error but ignores the discriminative power of channels. To overcome these drawbacks, we investigate a simple-yet-effective method, called discrimination-aware channel pruning, to choose those channels that really contribute to discriminative power. To this end, we introduce additional losses into the network to increase the discriminative power of intermediate layers and then select the most discriminative channels for each layer by considering the additional loss and the reconstruction error. Last, we propose a greedy algorithm to conduct channel selection and parameter optimization in an iterative way. Extensive experiments demonstrate the effectiveness of our method. For example, on ILSVRC-12, our pruned ResNet-50 with 30% reduction of channels even outperforms the original model by 0.39% in top-1 accuracy."

# Summary. An optional shortened abstract.
summary: "NeurIPS 2018"

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://papers.nips.cc/paper/2018/file/55a7cf9c71f1c9c495413f934dd1a158-Paper.pdf
url_code: https://github.com/SCUT-AILab/DCP
url_dataset:
url_poster: https://drive.google.com/file/d/1uy27B5pfnK-_K70vydWpwv1fxmhITNMx/view?usp=sharing
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=wCsSZ54n2i0&t=4s

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
