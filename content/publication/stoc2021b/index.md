---
title: "Breaking the Quadratic Barrier for Matroid Intersection"
authors:
- Joakim Blikstad
- Jan van den Brand
- admin
- Danupon Nanongkai
date: "2021-01-01T00:00:00Z"
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
- Matroid intersection
- Reachability
featured: true

links:
- name: arXiv
  url: http://arxiv.org/abs/1911.01651
url_pdf: https://arxiv.org/pdf/1911.01651.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: https://youtu.be/b-_F5DuRLl4

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

The matroid intersection problem is a fundamental problem that has been extensively studied for half a century. In the classic version of this problem, we are given two matroids ${\cal M}_1 = (V, {\cal I}_1)$ and ${\cal M}_2 = (V, {\cal I}_2)$ on a comment ground set $V$ of $n$ elements, and then we have to find the largest common independent set $S \in {\cal I}_1 \cap {\cal I}_2$ by making  *independence oracle queries*  of the form ''Is $S \in {\cal I}_1$?'' or ''Is $S \in {\cal I}_2$?'' for $S \subseteq V$. The goal is to minimize the number of queries. 

Beating the existing $\tilde O(n^2)$ bound, known as the *quadratic barrier*, is an open problem that captures the limits of techniques from two lines of work. The first one is the classic Cunningham's algorithm [SICOMP 1986], whose $\tilde O(n^2)$-query implementations were shown by CLS+ [FOCS 2019] and Nguyen [2019]. More generally, these algorithms take $\tilde O(nr)$ queries where $r$ denotes the rank which can be as big as $n$.  The other one is the general cutting plane method of Lee, Sidford, and Wong [FOCS 2015]. The only progress towards breaking the quadratic barrier requires either {\em approximation} algorithms or a more powerful *rank oracle query* [CLS+ FOCS 2019]. No exact algorithm with $o(n^2)$ independence queries was known.

In this work, we break the quadratic barrier with a randomized algorithm guaranteeing $\tilde O(n^{9/5})$ independence queries with high probability, and a deterministic algorithm guaranteeing $\tilde O(n^{11/6})$ independence queries. Our key insight is simple and fast algorithms to solve a graph reachability problem that arose in the standard augmenting path framework [Edmonds 1968]. Combining this with previous exact and approximation algorithms leads to our results. 
