---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning Choice Functions via Pareto-Embeddings"
event: KI2020 43rd German Conference on Artificial Intelligence
event_url: "https://ki2020.uni-bamberg.de/"
location: Bamberg, Germany
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: We consider the problem of learning to choose from a given set of objects, where each object is represented by a feature vector. Traditional approaches in choice modelling are mainly based on learning a latent, real-valued utility function, thereby inducing a linear order on choice alternatives. While this approach is suitable for discrete (top-1) choices, it is not straightforward how to use it for subset choices. Instead of mapping choice alternatives to the real number line, we propose to embed them into a higher-dimensional utility space, in which we identify choice sets with Pareto-optimal points. To this end, we propose a learning algorithm that minimizes a differentiable loss function suitable for this task. We demonstrate the feasibility of learning a Pareto-embedding on a suite of benchmark datasets.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-09-22T17:00:00+02:00
date_end: 2020-09-22T18:30:00+02:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-09-13T13:45:56+02:00

authors: ["Karlson Pfannschmidt", "Eyke Hüllermeier"]
tags: []

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf: "https://arxiv.org/pdf/2007.06927"
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---