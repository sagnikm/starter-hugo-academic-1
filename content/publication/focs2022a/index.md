---
title: "Cut query algorithms with star contraction"
authors:
- Simon Apers
- Yuval Efron
- Pawel Gawrychowski
- Troy Lee
- admin
- Danupon Nanongkai
date: "2022-07-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-14T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In *FOCS 2022*"
publication_short: "In *FOCS 2022*"

abstract: 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Graph algorithm
- Cut query
featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2201.05674
url_pdf: https://arxiv.org/pdf/2201.05674.pdf
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

We study the complexity of determining the edge connectivity of a simple graph with cut queries.
We show that (i) there is a bounded-error randomized  algorithm that computes edge connectivity with $O(n)$ cut queries, and (ii) there is a bounded-error quantum algorithm that computes edge connectivity with $\tilde O(\sqrt{n})$ cut queries. To prove these results we introduce a new technique, called *star contraction*, to randomly contract edges of a graph while preserving non-trivial minimum cuts.  In star contraction vertices randomly contract an edge incident on a small set of randomly chosen 'center' vertices.  In contrast to the related 2-out contraction technique of Ghaffari, Nowicki, and Thorup [SODA'20], star contraction only contracts vertex-disjoint star subgraphs, which allows it to be efficiently implemented via cut queries.

The $O(n)$ bound from item (i) was not known even for the simpler problem of connectivity, and it improves the $O(n \log^3 n)$ upper bound by Rubinstein, Schramm, and Weinberg [ITCS'18]. The bound is tight under the reasonable conjecture that the randomized communication complexity of connectivity is $\Omega(n \log n)$, an open question since the seminal work of Babai, Frankl, and Simon [FOCS'86]. The bound also excludes using edge connectivity on simple graphs to prove a superlinear randomized query lower bound for minimizing a symmetric submodular function. The quantum algorithm from item~(ii) gives a nearly-quadratic separation with the randomized complexity, and addresses an open question of Lee, Santha, and Zhang [SODA'21]. The algorithm can alternatively be viewed as computing the edge connectivity of a simple graph with $\tilde O(\sqrt{n})$ matrix-vector multiplication queries to its adjacency matrix.


Finally, we demonstrate the use of star contraction outside of the cut query setting by designing a one-pass semi-streaming algorithm for computing edge connectivity in the complete vertex arrival setting. This contrasts with the edge arrival setting where two passes are required.
