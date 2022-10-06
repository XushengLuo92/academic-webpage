---
title: 'Socially-aware robot planning via bandit human feedback'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yan Zhang
- Michael M. Zavlanos

# Author notes (optional)

date: '2020-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: "In *2020 ACM/IEEE 11th International Conference on Cyber-Physical Systems (ICCPS)*, pp. 216-225. IEEE"

abstract: In this paper, we consider the problem of de- signing collision-free, dynamically feasible, and socially-aware trajectories for robots operating in environments populated by humans. We define trajectories to be social-aware if they do not interfere with humans in any way that causes discomfort. In this paper, discomfort is defined broadly and, depending on specific individuals, it can result from the robot being too close to a human or from interfering with human sight or tasks. Moreover, we assume that human feedback is a bandit feedback indicating a complaint or no complaint on the part of the robot trajectory that interferes with the humans, and it does not reveal any contextual information about the locations of the humans or the reason for a complaint. Finally, we assume that humans can move in the obstacle-free space and, as a result, human utility can change. We formulate this planning problem as an online optimization problem that minimizes the social value of the time-varying robot trajectory, defined by the total number of incurred human complaints. As the human utility is unknown, we employ zeroth order, or derivative-free, optimization methods to solve this problem, which we combine with off-the-shelf motion planners to satisfy the dynamic feasibility and collision-free specifications of the resulting trajectories. To the best of our knowledge, this is a new framework for socially-aware robot planning that is not restricted to avoiding collisions with humans but, instead, focuses on increasing the social value of the robot trajectories using only bandit human feedback.

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

url_pdf: 'https://arxiv.org/pdf/2003.00658.pdf'

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