---
title: "Simulation Beats Richness: New Data-Structure Lower Bounds"
authors:
- Arkadev Chattopadhyay
- Michal Koucký
- Bruno Loff
- admin

date: "2018-07-01T00:00:00Z"
doi: "10.1145/3188745.3188874"
markup: mmark

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *STOC 2018*
publication_short: In *STOC 2018*

# abstract: 


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.

tags:
- Communication complexity
- Data structure lower bound
- Simulation theorem
featured: true

links:
- name: ECCC
  #url: https://eccc.weizmann.ac.il/report/2017/170/
url_pdf: https://eccc.weizmann.ac.il/report/2017/170/
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
url_slides: https://drive.google.com/file/d/1ASxW4ljarJhF-GgOunmreoyg4CCbT19_/view
#url_source: '#'
url_video: https://youtu.be/lv6uIjamlc8

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

We develop a technique for proving lower bounds in the setting of asymmetric communication, a model that was introduced in the famous works of Miltersen (STOC'94) and Miltersen, Nisan, Safra and Wigderson (STOC'95). At the core of our technique is a novel simulation theorem. Alice gets a $p \times n$ matrix $x$ over $\mathbb F_2$ and Bob gets a vector $y \in \mathbb F_2^n$.  Alice and Bob need to evaluate $f(x\cdot y)$ for a Boolean function $f$. Our simulation theorems show that a deterministic/randomized communication protocol exists for this problem, with cost $C\cdot n$ for Alice and $C$ for Bob, if and only if there exists a deterministic/randomized \emph{parity decision tree} of cost $\Theta(C)$ for evaluating $f$. As applications of this technique, we obtain the following results:

 * The first strong lower-bounds against randomized data-structure schemes for the Vector-Matrix-Vector product problem over $\mathbb F_2$. Moreover, our method yields strong lower bounds even when the data-structure scheme has tiny advantage over random guessing. 

 * The first lower bounds against randomized data-structures schemes for two natural Boolean variants of Orthogonal Vector Counting. 

 * We construct an asymmetric communication problem and obtain a deterministic lower-bound for it which is provably better than any lower-bound that may be obtained by the classical Richness Method of Miltersen et al. This seems to be the first known limitation of the Richness Method in the context of proving deterministic lower bounds.

