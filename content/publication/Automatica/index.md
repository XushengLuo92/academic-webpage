---
title: "An optimal graph-search method for secure state estimation" 
authors:
- admin
- Miroslav Pajic
- Michael M. Zavlanos
date: "2021-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Automatica* 123 (2021): 109323"
publication_short: ""

abstract: The growing complexity of modern Cyber-Physical Systems (CPS) and the frequent communication between their components make them vulnerable to malicious attacks. As a result, secure state estimation is a critical requirement for the control of these systems. Many existing secure state estimation methods suffer from combinatorial complexity which grows with the number of states and sensors in the system. This complexity can be mitigated using optimization-based methods that relax the original state estimation problem, although at the cost of optimality as these methods often identify attack-free sensors as attacked. In this paper, we propose a new optimal graph-search algorithm to correctly identify malicious attacks and to securely estimate the states even in large-scale CPS modeled as linear time-invariant systems. The graph consists of layers, each one containing two nodes capturing a truth assignment of any given sensor, and directed edges connecting adjacent layers only. Then, our algorithm searches the layers of this graph incrementally, favoring directions at higher layers with more attack-free assignments, while actively managing a repository of nodes to be expanded at later iterations. The proposed search bias and the ability to revisit nodes in the repository and self-correct, allow our graph-search algorithm to reach the optimal assignment faster and tackle larger problems. We show that our algorithm is complete and optimal provided that process and measurement noises do not dominate the attack signal. Moreover, we provide numerical simulations that demonstrate the ability of our algorithm to correctly identify attacked sensors and securely reconstruct the state. Our simulations show that our method outperforms existing algorithms both in terms of optimality and execution time.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Journal article
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/1903.10620.pdf
#url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
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
#slides: example
---
<!--{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).-->
