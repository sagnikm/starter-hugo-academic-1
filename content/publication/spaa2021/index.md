---
title: "Work-Optimal Parallel Minimum Cuts for Non-Sparse Graphs"
authors:
- Andrés López-Martínez
- admin
- Danupon Nanongkai
date: "2021-02-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-04-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *SPAA 2021*"
publication_short: "In *SPAA 2021*"

abstract: 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Graph algorithm
- Parallel algorithm
- Min-cut
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2102.06565
url_pdf: https://arxiv.org/pdf/2102.06565.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://youtu.be/kw7DIGry48A

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

We present the first work-optimal polylogarithmic-depth parallel algorithm for the minimum cut problem on non-sparse graphs. For $m\geq n^{1+\epsilon}$ for any constant $\epsilon>0$, our algorithm requires $O(m \log n)$ work and $O(\log^3 n)$ depth and succeeds with high probability. 
Its work matches the best $O(m \log n)$ runtime for sequential algorithms [MN STOC’20; GMW SOSA'21].  This improves the previous best work by Geissmann and Gianinazzi [SPAA'18] by $O(\log^3 n)$ factor, while matching the depth of their algorithm. To do this, we design a work-efficient approximation algorithm and parallelize the recent sequential algorithms [MN STOC'21; GMW SOSA'21] that exploit a connection between 2-respecting minimum cuts and 2-dimensional orthogonal range searching. 
