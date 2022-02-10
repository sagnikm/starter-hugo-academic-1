---
title: "Lifting Theorems for Equality"
authors:
- Bruno Loff
- admin

date: "2019-03-01T00:00:00Z"
doi: "10.4230/LIPIcs.STACS.2019.50"
markup: mmark

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *STACS 2019*
publication_short: In *STACS 2019*

# abstract: 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.

tags:
- Communication complexity
- Simulation theorem
featured: false

links:
- name: ECCC
  url: https://eccc.weizmann.ac.il/report/2018/175/
url_pdf: http://drops.dagstuhl.de/opus/volltexte/2019/10289/pdf/LIPIcs-STACS-2019-50.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
url_slides: https://drive.google.com/file/d/11M7wRTfn140z3_F78fksIGl0NQ8x06Vf/view
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

We show a *deterministic simulation (or lifting) theorem* for composed problems $f \circ \mathsf{Eq}_n$ where the inner function (the gadget) is Equality on $n$ bits. When $f$ is a total function on $p$ bits, it is easy to show via a rank argument that the communication complexity of $f\circ \mathsf{Eq}_n$ is $\Omega(deg(f) \cdot n)$. However, there is a surprising counter-example of a partial function $f$ on $p$ bits, such that any completion $f'$ of $f$ has $\deg(f') = \Omega(p)$, and yet $f \circ \mathsf{Eq}_n$ has communication complexity $O(n)$. Nonetheless, we are able to show that the communication complexity of $f \circ \mathsf{Eq}_n$ is at least $D(f) \cdot n$ for a complexity measure $D(f)$ which is closely related to the AND-query complexity of $f$ and is lower-bounded by the logarithm of the leaf complexity of $f$. As a corollary, we also obtain lifting theorems for the set-disjointness gadget, and a lifting theorem in the context of parity decision-trees, for the NOR gadget. 

As an application, we prove a tight lower-bound for the deterministic communication complexity of the communication problem, where Alice and Bob are each given $p$-many $n$-bit strings, with the promise that either all of the strings are distinct, or all-but-one of the strings are distinct, and they wish to know which is the case. We show that the complexity of this problem is $\Theta(p \cdot n)$.
