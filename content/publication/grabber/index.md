---
title: "Grabber: A Tool to Improve Convergence in Interactive Image Segmentation"
authors:
- admin
- Bruno Moura
- Alexandre Xavier Falcão
- Fábio A. M. Cappabianco
date: 2020-12-01
doi: "https://doi.org/10.1016/j.patrec.2020.10.012"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Pattern Recognition Letters"
# publication_short: ""

abstract: Interactive image segmentation has considerably evolved from techniques that do not learn the parameters of the model to methods that pre-train a model and adapt it from user inputs during the process. However, user control over segmentation still requires significant improvements to avoid that corrections in one part of the object cause errors in other parts. We address this problem by presenting Grabber --- a tool to improve convergence (user control) in interactive image segmentation. Grabber is thought to complete segmentation of some other initial method. From a given segmentation mask, Grabber quickly estimates anchor points in one orientation along the boundary of the mask and delineates an optimum contour constrained to pass through those points. The user can control the process by adding, removing, and moving anchor points. Grabber can also explore object properties from the initial coarse segmentation to improve boundary delineation. We integrate Grabber with two recent methods, a region-based approach and a pixel classification method based on deep neural networks. Extensive experiments with robot users on two datasets show in both cases that Grabber can significantly improve convergence, with faster delineation, higher effectiveness, and less user effort. The code of Grabber is available at https://github.com/LIDS-UNICAMP/grabber .

tags:
- Interactive Image Segmentation
featured: true

links:
# - name: ""
#   url: ""
# url_pdf: ''
url_code: 'https://github.com/LIDS-UNICAMP/grabber'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
