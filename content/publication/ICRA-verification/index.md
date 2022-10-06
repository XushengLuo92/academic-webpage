---
title: 'Formal Verification of Stochastic Systems with ReLU Neural Network Controller'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Shiqi Sun
- Yan Zhang
- admin
- Panagiotis Vlantis
- Miroslav Pajic
- Michael M. Zavlanos

# Author notes (optional)

date: '2022-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "In *IEEE 39th International Conference on Robotics and Automation (ICRA)*, Philadelphia, USA"

abstract: In this work, we address the problem of formal safety verification for stochastic cyber-physical systems (CPS) equipped with ReLU neural network (NN) controllers. Our goal is to find the set of initial states from where, with a predetermined confidence, the system will not reach an unsafe configuration within a specified time horizon. Specifically, we consider discrete-time LTI systems with Gaussian noise, which we abstract by a suitable graph. Then, we formulate a Satisfiability Modulo Convex (SMC) problem to estimate upper bounds on the transition probabilities between nodes in the graph. Using this abstraction, we propose a method to compute tight bounds on the safety probabilities of nodes in this graph, despite possible over-approximations of the transition probabilities between these nodes. Additionally, using the proposed SMC formula, we devise a heuristic method to refine the abstraction of the system in order to further improve the estimated safety bounds. Finally, we corroborate the efficacy of the proposed method with simulation results considering a robot navigation example and comparison against a state-of-the-art verification scheme

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 
- Conference paper

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2103.05142.pdf'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
<!--
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
-->