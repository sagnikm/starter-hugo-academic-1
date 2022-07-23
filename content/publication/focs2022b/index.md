---
title: "Nearly optimal communication and query complexity of
bipartite matching"
authors:
- Joakim Blikstad
- Jan van den Brand
- Yuval Efron
- admin
- Danupon Nanongkai
date: "2022-07-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-07-04T00:00:00Z"

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
- Communication complexity
- Query Complexity
featured: true

links:
- name: arXiv
  url: ''
  url_pdf: ''
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

We settle the complexities of the maximum-cardinality bipartite matching problem (BMM)
up to poly-logarithmic factors in five models of computation: the two-party communication,
AND query, OR query, XOR query, and quantum edge query models. Our results answer open
problems that have been raised repeatedly since at least three decades ago [Hajnal, Maass, and
Turan STOC’88; Ivanyos, Klauck, Lee, Santha, and de Wolf FSTTCS’12; Dobzinski, Nisan,
and Oren STOC’14; Nisan SODA’21] and tighten the lower bounds shown by Beniamini and
Nisan [STOC’21] and Zhang [ICALP’04]. We also settle the communication complexity of the
generalizations of BMM, such as maximum-cost bipartite b-matching and transshipment; and the
query complexity of unique bipartite perfect matching (answering an open question by Beniamini
[2022]). Our algorithms and lower bounds follow from simple applications of known techniques
such as cutting planes methods and set disjointness
 	