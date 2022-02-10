---
title: "Separation between Deterministic and Randomized Query Complexity"
authors:
- admin
- Swagato Sanyal
- Jaikumar Radhakrishnan
date: "2015-09-01T00:00:00Z"
doi: "10.1137/17M1124115"
markup: mmark

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*SIAM Journal on Computing* (47:4)"
publication_short: ""

abstract:


# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://epubs.siam.org/doi/10.1137/17M1124115
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

Saks and Wigderson [FOCS 1986] conjectured that $R\_0(f)=\Omega(D(f)^{0.753\ldots})$ for all Boolean functions $f$. We show that for the pointer function $GPW\_{r \times s}$ defined by Goos, Pitassi, and Watson [FOCS 2015], the following hold:

* $R\_1(GPW\_{r \times s})=\tilde\Theta(r + s)$ and 

* $R\_1(\overline{GPW\_{r \times s}})=\tilde \Theta(r + \sqrt{r}s)$, 

where $R\_1$ denotes the randomized one-sided error query complexity. These results imply that (i) $R\_0(GPW_{s^2 \times s})=O(D(GPW_{s^2 \times s})^{2/3})$, thereby refuting the conjecture of Saks and Wigderson, and (ii)
$R\_1(GPW\_{s \times s})=\tilde O(R\_0(GPW\_{s \times s})^{2/3})$, thereby
providing a polynomial separation between the randomized zero-error and one
sided error query complexity measures.
