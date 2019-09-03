---
title: "On the performance of network parallel training in artificial neural networks"
authors:
- Ludvig Ericson
- Rendani Mbuvha
date: "2016-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv preprint arXiv:1701.05130*
publication_short: In *arXiv*

abstract: Artificial Neural Networks (ANNs) have received increasing attention in recent years with applications that span a wide range of disciplines including vital domains such as medicine, network security and autonomous transportation. However, neural network architectures are becoming increasingly complex and with an increasing need to obtain real-time results from such models, it has become pivotal to use parallelization as a mechanism for speeding up network training and deployment. In this work we propose an implementation of Network Parallel Training through Cannon's Algorithm for matrix multiplication. We show that increasing the number of processes speeds up training until the point where process communication costs become prohibitive; this point varies by network complexity. We also show through empirical efficiency calculations that the speedup obtained is superlinear.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Neural Networks
- Parallel Computation
- Cannon's Algorithm
- Matrix Multiplication
featured: true

links:
#- name: Custom Link
#url: https://arxiv.org/pdf/1701.05130.pdf
url_pdf: https://arxiv.org/pdf/1701.05130.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

#{{% alert note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /alert %}}

#{{% alert note %}}
#Click the *Slides* button above to demo Academic's Markdown slides feature.
#{{% /alert %}}

#Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

