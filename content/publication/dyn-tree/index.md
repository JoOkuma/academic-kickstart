---
title: "Graph-Based Image Segmentation Using Dynamic Trees"
authors:
- admin
- Samuel Botter Martins
- Cesar Castelo-Fernandez
- Alexandre Xavier Falcão
date: "2019-03-03T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-030-13469-3_55"

# Schedule page publish date (NOT publication's date).
# publishDate: "2019-03-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Iberoamerican Congress on Pattern Recognition
publication_short: In CIARP 2018 

abstract: Image segmentation methods have been actively investigated, being the graph-based approaches among the most popular for object delineation from seed nodes. In this context, one can design segmentation methods by distinct choices of the image graph and connectivity function—i.e., a function that measures how strongly connected are seed and node through a given path. The framework is known as Image Foresting Transform (IFT) and it can define by seed competition each object as one optimum-path forest rooted in its internal seeds. In this work, we extend the general IFT algorithm to extract object information as the trees evolve from the seed set and use that information to estimate arc weights, positively affecting the connectivity function, during segmentation. The new framework is named Dynamic IFT (DynIFT) and it can make object delineation more effective by exploiting color, texture, and shape information from those dynamic trees. In comparison with other graph-based approaches from the state-of-the-art, the experimental results on natural images show that DynIFT-based object delineation methods can be significantly more accurate.

tags:
- Interactive Image Segmentation 
featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://link.springer.com/chapter/10.1007/978-3-030-13469-3_55
url_code: 'https://github.com/pyift/pyift'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "" 
---
