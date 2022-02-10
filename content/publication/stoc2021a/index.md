---
title: "Distributed Weighted Min-Cut in Nearly-Optimal Time"
authors:
- Michal Dory
- Yuval Efron
- admin
- Danupon Nanongkai
date: "2021-01-20T00:00:00Z"
doi: ""
markup: mmark

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *STOC 2021*
publication_short: In *STOC 2021*

abstract: 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Graph algorithm
- CONGEST model
- Min-cut
featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2004.09129
url_pdf: https://arxiv.org/pdf/2004.09129.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://youtu.be/On9DX3TkEgo

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

Minimum-weight cut (min-cut) is a basic measure of a network's connectivity strength. While the min-cut can be computed efficiently in the sequential setting [Karger STOC'96], there was no efficient way for a distributed network to compute its own min-cut without limiting the input structure or dropping the output quality: In the standard CONGEST model, existing algorithms with nearly-optimal time (e.g. [Ghaffari, Kuhn, DISC'13; Nanongkai, Su, DISC'14]) can guarantee a solution that is $(1+\epsilon)$-approximation at best while the exact $\tilde O(n^{0.8} D^{0.2} + n^{0.9})$-time algorithm [Ghaffari, Nowicki, Thorup, SODA'20] works only on *simple* networks (no weights and no parallel edges). Throughout, $n$ and $D$ denote the network's number of vertices and hop-diameter, respectively. For the weighted case, the best bound was $\tilde O(n)$ [Daga, Henzinger, Nanongkai, Saranurak, STOC'19]. 
	
In this paper, we provide an {\em exact} $\tilde O(\sqrt n + D)$-time algorithm for computing min-cut on *weighted* networks. Our result improves even the previous algorithm that works only on simple networks. Its time complexity matches the known lower bound up to polylogarithmic factors. 
At the heart of our algorithm are a clever routing trick and two structural lemmas regarding the structure of a minimum cut of a graph. These two structural lemmas considerably strengthen and generalize the framework of Mukhopadhyay-Nanongkai [STOC'20] and can be of independent interest.