---
title: "A Unified Approach to Sparse Tweedie Modeling of Multi-Source Insurance Claim Data"
authors: 
- simfont
- yyang
- wqian
- bfan
- ygu
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2020-02-01T20:16:27-05:00"
doi: "10.1080/00401706.2019.1647881"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-01T20:16:27-05:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Technometrics"
publication_short: "Technometrics"

abstract: "Actuarial practitioners now have access to multiple sources of insurance data corresponding to various situations: multiple business lines, umbrella coverage, multiple hazards, and so on. Despite the wide use and simple nature of single-target approaches, modeling these types of data may benefit from a simultaneous approach. We propose a unified algorithm to perform sparse learning of such fused insurance data under the Tweedie (compound Poisson) model. By integrating ideas from multi-task sparse learning and sparse Tweedie modeling, our algorithm produces flexible regularization that balances predictor sparsity and between-sources sparsity. When applied to simulated and real data, our approach clearly outperforms single-target modeling in both prediction and selection accuracy, notably when the sources do not have exactly the same set of predictors. An efficient implementation of the proposed algorithm is provided in our R package MStweedie."

# Summary. An optional shortened abstract.
summary: ""

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ./publication/mstweedie/TCH_mstweedie.pdf
url_code: https://github.com/fontaine618/MSTweedie
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
- name: "Supplementary material"
  url: "./publication/mstweedie/TCH_mstweedie_appendix.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
