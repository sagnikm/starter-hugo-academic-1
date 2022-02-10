---
title: "Weighted Min-Cut: Sequential, Cut-Query and Streaming Algorithms"
authors:
- admin
- Danupon Nanongkai
date: "2020-01-01T00:00:00Z"
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
publication: In *STOC 2020*
publication_short: In *STOC 2020*

abstract: 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Query algorithm
- Streaming
- Sequential model
- Graph algorithm
- Min-cut
featured: true

links:
- name: arXiv
  url: http://arxiv.org/abs/1911.01651
url_pdf: https://arxiv.org/pdf/1911.01651.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: https://drive.google.com/file/d/1Lh7OjPfRK772WO9BIlxKv38dX1y1hXs9/view
url_source: ''
url_video: https://www.youtube.com/watch?v=WulDnhZTeDY&feature=youtu.be

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

Consider the following *2-respecting min-cut* problem. Given a weighted graph $G$ and its spanning tree $T$, find the minimum cut among the cuts that contain at most two edges in $T$. This problem is an important subroutine in Karger's celebrated randomized near-linear-time min-cut algorithm [STOC'96]. We present a new approach for this problem which can be easily implemented in many settings, leading to the following randomized min-cut algorithms for weighted graphs. 

* An $O\left(m\frac{\log^2 n}{\log\log n} + n\log^6 n\right)$-time sequential algorithm: This improves Karger's long-standing $O(m \log^3 n)$ and $O\left(m\frac{(\log^2 n)\log (n^2/m)}{\log\log n} + n\log^6 n\right)$ bounds when the input graph is not extremely sparse or dense. Improvements over Karger's bounds were previously known only under a rather strong assumption that the input graph is {\em simple} (unweighted without parallel edges) [Henzinger, Rao, Wang, SODA'17; Ghaffari, Nowicki, Thorup, SODA'20]. For unweighted graphs  (possibly with parallel edges) and using bit operations, our bound can be further improved to $O\left(m\frac{\log^{1.5} n}{\log\log n} + n\log^6 n\right)$. 
	
* An algorithm that requires $\tilde O(n)$ *cut queries* to compute the min-cut of a weighted graph: This answers an open problem by Rubinstein, Schramm, and Weinberg [ITCS'18], who obtained a similar bound for simple graphs. Our bound is tight up to polylogarithmic factors. 
	
* A *streaming* algorithm that requires $\tilde O(n)$ space and $O(\log n)$ passes to compute the min-cut: The only previous non-trivial exact min-cut algorithm in this setting is the 2-pass $\tilde O(n)$-space algorithm on simple graphs [Rubenstein et al. ITCS 2018] observed by Assadi, Chen, and Khanna [STOC'19]). 

In contrast to Karger's 2-respecting min-cut algorithm which deploys sophisticated dynamic programming techniques, our approach exploits some cute structural properties so that it only needs to compute the values of $\tilde O(n)$ cuts corresponding to removing $\tilde O(n)$ pairs of tree edges, an operation that can be done quickly in many settings.  
