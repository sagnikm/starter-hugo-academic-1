---
title: "Faster Connectivity in Low-Rank Hypergraphs via Expander Decomposition"
authors:
- Calvin Beideman
- Karthekeyan Chandrasekaran
- admin
- Danupon Nanongkai
date: "2022-02-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *IPCO 2022*"
publication_short: "In *IPCO 2022*"

abstract: 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Hypergraph algorithm
- Min-cut
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2011.08097
url_pdf: https://arxiv.org/pdf/2011.08097.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---

We design an algorithm for computing connectivity in hypergraphs which runs in time $\hat O_r(p + \min\{\lambda n^2, n^r/\lambda\})$, where $p$ is the size, $n$ is the number of vertices, $r$ is the rank (size of the largest hyperedge), and $\lambda$ is the connectivity of the hypergraph. The $\hat O_r(\cdot)$ hides terms that are subpolynomial in the main parameter and terms that depend only on $r$. Our algorithm is faster than existing algorithms when the connectivity $\lambda$ is $\Omega(n^{(r-2)/2})$.
The heart of our algorithm is a structural result regarding min-cuts in simple hypergraphs. We show a trade-off between the number of hyperedges taking part in all min-cuts and the size of the smaller side of the min-cut. This structural result can be viewed as a generalization of a well-known structural theorem for simple graphs [Kawarabayashi-Thorup, JACM 19].  We extend the framework of expander decomposition to simple hypergraphs in order to prove this structural result. We also make the proof of the structural result constructive to obtain our faster hypergraph connectivity algorithm.