---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Efficient time stepping for numerical integration using reinforcement learning"
authors: ["Michael Dellnitz", "Eyke Hüllermeier", "Marvin Lücke", "Sina Ober-Blöbaum", "Christian Offen", "Sebastian Peitz", "Karlson Pfannschmidt"]
date: 2021-04-09T10:00:00+02:00
# doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-04-08T07:24:54+00:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv.org"
publication_short: "arXiv"

abstract: "Many problems in science and engineering require the efficient numerical approximation of integrals, a particularly important application being the numerical solution of initial value problems for differential equations. For complex systems, an equidistant discretization is often inadvisable, as it either results in prohibitively large errors or computational effort. To this end, adaptive schemes have been developed that rely on error estimators based on Taylor series expansions. While these estimators a) rely on strong smoothness assumptions and b) may still result in erroneous steps for complex systems (and thus require step rejection mechanisms), we here propose a data-driven time stepping scheme based on machine learning, and more specifically on reinforcement learning (RL) and meta-learning. First, one or several (in the case of non-smooth or hybrid systems) base learners are trained using RL. Then, a meta-learner is trained which (depending on the system state) selects the base learner that appears to be optimal for the current situation. Several examples including both smooth and non-smooth problems demonstrate the superior performance of our approach over state-of-the-art numerical schemes."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Numerical integration", "Reinforcement learning", "Differential equations"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/pdf/2104.03562v1.pdf"
url_code: "https://github.com/lueckem/quadrature-ML"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
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
