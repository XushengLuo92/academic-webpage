---
title: "An abstraction-free method for multirobot temporal logic optimal control synthesis" 
authors:
- admin
- Yiannis Kantaros
- Michael M. Zavlanos
date: "2021-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Robotics*, 37(5):1487–1507"
publication_short: ""

abstract: The majority of existing Linear Temporal Logic (LTL) planning methods rely on the construction of a discrete product automaton, that combines a discrete abstraction of robot mobility and a Buchi automaton that captures the LTL specification. Representing this product automaton as a graph and using graph search techniques, optimal plans that satisfy the LTL task can be synthesized. However, constructing expressive discrete abstractions makes the synthesis problem computationally intractable. In this paper, we propose a new samplingbased LTL planning algorithm that does not require any discrete abstraction of robot mobility. Instead, it incrementally builds trees that explore the product state-space, until a maximum number of iterations is reached or a feasible plan is found. The use of trees makes data storage and graph search tractable, which significantly increases the scalability of our algorithm. To accelerate the construction of feasible plans, we introduce bias in the sampling process which is guided by transitions in the Buchi automaton that belong to the shortest path to the accepting states. We show that our planning algorithm, with and without bias, is probabilistically complete and asymptotically optimal. Finally, we present numerical experiments showing that our method outperforms relevant temporal logic planning methods.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Journal article
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/1909.00526
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

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
-->