---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Generative Low-bitwidth Data Free Quantization"
authors: [Shoukai Xu*, Haokun Li*, Bohan Zhuang*, Jing Liu, Jiezhang Cao, Chuangrun Liang, Mingkui Tan ]
date: 2020-07-18T15:58:56+08:00
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

abstract: "Neural network quantization is an effective way to compress deep models and improve the execution latency and energy efficiency, so that they can be deployed on mobile or embedded devices. Existing quantization methods require original data for calibration or fine-tuning to get better performance. However, in many real-world scenarios, the data may not be available due to confidential or private issues, making existing quantization methods not applicable. Moreover, due to the absence of original data, the recently developed generative adversarial networks (GANs) can not be applied to generate data. Although the full precision model may contain the entire data information, such information alone is hard to exploit for recovering the original data or generating new meaningful data. In this paper, we investigate a simple-yet-effective method called Generative Low-bitwidth Data Free Quantization to remove the data dependence burden. Specifically, we propose a Knowledge Matching Generator to produce meaningful fake data by exploiting classification boundary knowledge and distribution information in the pre-trained model. With the help of generated data, we are able to quantize a model by learning knowledge from the pre-trained model. Extensive experiments on three data sets demonstrate the effectiveness of our method. More critically, our method achieves much higher accuracy on 4-bit quantization than the existing data free quantization method."

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

url_pdf: https://arxiv.org/pdf/2003.03603.pdf
url_code: https://github.com/xushoukai/GDFQ
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
