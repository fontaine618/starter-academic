---
title: Missing Value Imputation of Network Node Attributes
event: JSM 2021
event_url: 

location: 
address:
  street: 
  city: 
  region: 
  postcode: 
  country: United States

summary: 
abstract: "User profiles in social networks are notoriously incomplete due to self-censoring or 
attrition in the answering process; predicting or imputing these missing values is 
often of paramount importance. While missing value imputation 
has been widely studied in the context of standard data matrices, the network with 
node attributes case remains fairly unexplored. In particular, using all available
information, observed node attributes and edges, should improve on using only the 
observed attributes, provided some association between attributes and edges. We 
propose a novel imputation method based on a joint latent space model that 
allows information between the network adjacency matrix and node attributes to be 
shared. Additionally, we propose an extension to non-ignorable missing values by
directly modeling the missingness process. Using variational inference, we obtain 
approximate posteriors for the latent variables enabling predictive distributions for 
the missing values and further allowing assessment of missingness patterns. 
Numerical experiments, on both simulated data and real-world networks, show that our proposed 
method improves on multiple imputation using only the node attributes."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-08-10T10:00:00"
date_end: ""
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2021-05-31T00:00:00"

authors: 
- simfont
- Ji Zhu
author_notes:
- "Presenting"
- ""

#tags: ["Bayesian inference", "Factor graphs", "Online algorithms", "Rating systems"]

# Is this a featured talk? (true/false)
featured: false

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:

# Enable math on this page?
math: true
---
