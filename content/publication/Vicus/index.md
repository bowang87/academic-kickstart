+++
title = "Vicus: Exploiting local structures to improve network-based analysis of biological data."
date = 2017-10-12T00:00:00
draft = false
highlight = false
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Bo Wang", "Lin Huang", "Yuke Zhu", "Anshul Kundaje", "Serafim Batzoglou", "Anna Goldenberg"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "In *Plos Computational Biology*."
publication_short = "In *Plos Combio*"

# Abstract and optional shortened version.
abstract = "Biological networks entail important topological features and patterns critical to understanding interactions within complicated biological systems. Despite a great progress in understanding their structure, much more can be done to improve our inference and network analysis. Spectral methods play a key role in many network-based applications. Fundamental to spectral methods is the Laplacian, a matrix that captures the global structure of the network. Unfortunately, the Laplacian does not take into account intricacies of the network’s local structure and is sensitive to noise in the network. These two properties are fundamental to biological networks and cannot be ignored. We propose an alternative matrix Vicus. The Vicus matrix captures the local neighborhood structure of the network and thus is more effective at modeling biological interactions. We demonstrate the advantages of Vicus in the context of spectral methods by extensive empirical benchmarking on tasks such as single cell dimensionality reduction, protein module discovery and ranking genes for cancer subtyping. Our experiments show that using Vicus, spectral methods result in more accurate and robust performance in all of these tasks."

url_pdf = "https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005621"
url_code = "https://github.com/bowang87/Vicus"
abstract_short = "Vicus is a new type of Laplacian matrix for biological networks with specific focus on local structures."
# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_preprint = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

