---
title: "An adaptive multiple-try Metropolis algorithm"
authors: 
- simfont
- mbedard
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-06-01T20:16:27-05:00"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-01T20:16:27-05:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "TBD"
publication_short: "TBD"

abstract: "Markov chain Monte Carlo (MCMC) methods, specifically samplers based on random walks, often have difficulty handling target distributions with complex geometry such as multi-modality. We propose an adaptive multiple-try Metropolis algorithm designed to tackle such problems by combining the flexibility of multiple-proposal samplers with the user-friendliness and optimality of adaptive algorithms. We prove the ergodicity of the resulting Markov chain with respect to the target distribution using common techniques in the adaptive MCMC literature. In a Bayesian model for loss of heterozygosity in cancer cells, we find that our method outperforms traditional adaptive samplers, non-adaptive multiple-try Metropolis samplers, and various more sophisticated competing methods."

# Summary. An optional shortened abstract.
summary: ""

# tags:
# - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ./publication/amtm/aMTM.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

links:
- name: "R package"
  url: "https://github.com/fontaine618/aMTM"
- name: "Simulation code"
  url: "https://github.com/fontaine618/aMTM-simulations"

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
