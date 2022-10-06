---
title: 'Human-in-the-loop robot planning with non-contextual bandit feedback'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Yijie Zhou
- Yan Zhang
- admin
- Michael M. Zavlanos

# Author notes (optional)

date: '2021-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "In *2021 60th IEEE Conference on Decision and Control (CDC)*, pp. 2848-2853. IEEE"

abstract: In this paper, we consider robot navigation prob- lems in environments populated by humans. The goal is to determine collision-free and dynamically feasible trajectories that also maximize human satisfaction, by ensuring that robots are available to assist humans with their work as needed and avoid actions that cause discomfort. In practice, human satisfaction is subjective and hard to describe mathematically. As a result, the planning problem we consider in this paper may lack important contextual information. To address this challenge, we propose a semi-supervised Bayesian Optimization (BO) method to design globally optimal robot trajectories using bandit human feedback, in the form of complaints or satisfaction ratings, that expresses how desirable a trajectory is. Since trajectory planning is typically a high-dimensional optimization problem in the space of waypoints that need to be decided, BO may require prohibitively many queries for human feedback to return a good solution. To this end, we use an autoencoder to reduce the high-dimensional space into a low dimensional latent space, which we update using human feedback. Moreover, we improve the exploration efficiency of BO by biasing the search for new trajectories towards dynam- ically feasible and collision-free trajectories obtained using off- the-shelf motion planners. We demonstrate the efficiency of our proposed trajectory planning method in a scenario with humans that have diversified and unknown demands.

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

url_pdf: 'https://arxiv.org/pdf/2011.01793.pdf'

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