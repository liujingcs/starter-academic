---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Deep Transferring Quantization"
authors: [Zheng Xie*, Zhiquan Wen*, Jing Liu*, Zhiqiang Liu, Xixian Wu, Mingkui Tan]
date: 2020-07-18T15:59:02+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Computer Vision"
publication_short: "ECCV"

abstract: "Network quantization is an effective method for network compression. Existing methods train a low-precision network by fine-tuning from a pre-trained model. However, training a low-precision network often requires large-scale labeled data to achieve superior performance. In many real-world scenarios, only limited labeled data are available due to expensive labeling costs or privacy protection. With limited training data, fine-tuning methods may suffer from the overfitting issue and substantial accuracy loss. To alleviate these issues, we introduce transfer learning into network quantization to obtain an accurate low-precision model. Specifically, we propose a method named deep transferring quantization (DTQ) to effectively exploit the knowledge in a pre-trained fullprecision model. To this end, we propose a learnable attentive transfer module to identify the informative channels for alignment. In addition, we introduce the Kullback–Leibler (KL) divergence to further help train a low-precision model. Extensive experiments on both image classification and face recognition demonstrate the effectiveness of DTQ."

# Summary. An optional shortened abstract.
summary: "ECCV 2020"

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

url_pdf: https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123530613.pdf
url_code: https://github.com/xiezheng-cs/DTQ
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
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
