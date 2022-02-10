---
title: "Towards Better Separation between Deterministic and Randomized Query Complexity"
authors:
- admin
- Swagato Sanyal

date: "2015-07-01T00:00:00Z"
doi: "10.4230/LIPIcs.FSTTCS.2015.206"
markup: mmark

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *FSTTCS 2015*
publication_short: In *FSTTCS 2015*

# abstract: 


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.

tags:
- Query complexity
- Randomization
- Deterministic
featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/1506.06399
url_pdf: https://arxiv.org/pdf/1506.06399.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
url_slides: https://drive.google.com/file/d/1YrtQZgs7F9dlXvU8piXhxkSwk02o5TNg/view
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

We show that there exists a Boolean function $F$ which observes the following separations among deterministic query complexity $(D(F))$, randomized zero error query complexity $(R_0(F))$ and randomized one-sided error query complexity $(R_1(F))$: $R_1(F) = \widetilde{O}(\sqrt{D(F)})$ and $R_0(F)=\widetilde{O}(D(F))^{3/4}$. This refutes the conjecture made by Saks and Wigderson that for any Boolean function $f$, $R_0(f)=\Omega({D(f)})^{0.753..}$. This also shows widest separation between $R_1(f)$ and $D(f)$ for any Boolean function. The function $F$ was defined by Göös, Pitassi and Watson who studied it for showing a separation between deterministic decision tree complexity and unambiguous non-deterministic decision tree complexity. Independently of us, Ambainis et al proved that different variants of the function $F$ certify optimal (quadratic) separation between $D(f)$ and $R_0(f)$, and polynomial separation between $R_0(f)$ and $R_1(f)$. Viewed as separation results, our results are subsumed by those of Ambainis et al. However, while the functions considerd in the work of Ambainis et al are different variants of $F$, we work with the original function $F$ itself.