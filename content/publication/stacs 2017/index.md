---
title: "Lower Bounds for Elimination via Weak Regularity"
authors:
- Arkadev Chattopadhyay
- Michal Koucký
- Bruno Loff
- admin

date: "2017-07-01T00:00:00Z"
doi: "10.4230/LIPIcs.STACS.2017.21"
markup: mmark

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *STACS 2017*
publication_short: In *STACS 2017*

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
- name: DOI
  #url: https://eccc.weizmann.ac.il/report/2017/170/
url_pdf: http://drops.dagstuhl.de/opus/volltexte/2017/7012/pdf/LIPIcs-STACS-2017-21.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://youtu.be/In48e7VIlcY

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

We consider the problem of elimination in communication complexity, that was first raised by Ambainis et al. and later studied by Beimel et al. for its connection to the famous direct sum question. In this problem, let $f : \{0, 1\}^{2n} \to \{0, 1\}$ be any boolean function. Alice and Bob get $k$ inputs $x_1, \cdots , x_k$ and $y_1, \cdots, y_k$ respectively, with $x_i, y_i \in \{0, 1\}^n$. They want to output a $k$-bit vector $v$, such that there exists one index $i$ for which $v_i \neq f(x_i, y_i)$. We prove a general result lower bounding the randomized communication complexity of the elimination problem for $f$ using its discrepancy. Consequently, we obtain strong lower bounds for the functions *InnerProduct* and  *Greater-Than*, that work for exponentially larger values of $k$ than the best previous bounds. To prove our result, we use a pseudo-random notion called regularity that was first used by Raz and Wigderson. We show that functions with small discrepancy are regular. We also observe that a weaker notion, that we call weak-regularity, already implies hardness of elimination. Finally, we give a different proof, borrowing ideas from Viola, to show that Greater-Than is weakly regular.

