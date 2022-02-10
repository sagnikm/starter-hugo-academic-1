---
title: "Tribes is Hard in Message-passing Model"
authors:
- Arkadev Chattopadhyay
- admin

date: "2015-07-01T00:00:00Z"
doi: "10.4230/LIPIcs.STACS.2015.224"
markup: mmark

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *STACS 2015*
publication_short: In *STACS 2015*

# abstract: 


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.

tags:
- Communication complexity
- Elimination
- Direct sum
- Discrepancy
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1602.06079
url_pdf: https://arxiv.org/pdf/1602.06079.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
url_slides: https://drive.google.com/file/d/1gCS_qQn31TXhIKfzLbbPLX60TirYcf94/view
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---

We consider the point-to-point message passing model of
  communication in which there are $k$ processors with individual
  private inputs, each $n$-bit long. Each processor is located at the
  node of an underlying undirected graph and has access to private
  random coins. An edge of the graph is a private channel of
  communication between its endpoints. The processors have to compute
  a given function of all their inputs by communicating along these
  channels. While this model has been widely used in distributed
  computing, strong lower bounds on the amount of communication needed
  to compute simple functions have just begun to appear.

  In this work, we prove a tight lower bound of $\Omega(kn)$ on the
  communication needed for computing the Tribes function, when the
  underlying graph is a star of $k+1$ nodes that has $k$ leaves with
  inputs and a center with no input. Lower bound on this topology
  easily implies comparable bounds for others.  Our lower bounds are
  obtained by building upon the recent information theoretic
  techniques of Braverman et.al [FOCS'13] and combining it
  with the earlier work of Jayram, Kumar and Sivakumar [STOC'03]. This approach yields
  information complexity bounds that is of independent interest.