---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ClevrTex: A Texture-Rich Benchmark for Unsupervised Multi-Object Segmentation"
authors: ["admin", "Iro Laina", "Christian Rupprecht"]
date: 2021-08-29T19:16:17+01:00
# doi: "10.1007/978-3-319-92537-0_7"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-01-02T17:15:49+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Neural Information Processing Systems Track on Datasets and Benchmarks 2021"
publication_short: "NeurIPS Datasets and Benchmarks 2021"

abstract: "There has been a recent surge in methods that aim to decompose and segment scenes into multiple objects in an unsupervised manner, i.e., unsupervised multi-object segmentation. Performing such a task is a long-standing goal of computer vision, offering to unlock object-level reasoning without requiring dense annotations to train segmentation models. Despite significant progress, current models are developed and trained on visually simple scenes depicting mono-colored objects on plain backgrounds. The natural world, however, is visually complex with confounding aspects such as diverse textures and complicated lighting effects. In this study, we present a new benchmark called ClevrTex, designed as the next challenge to compare, evaluate and analyze algorithms. ClevrTex features synthetic scenes with diverse shapes, textures and photo-mapped materials, created using physically based rendering techniques. ClevrTex has 50k examples depicting 3-10 objects arranged on a background, created using a catalog of 60 materials, and a further test set featuring 10k images created using 25 different materials. We benchmark a large set of recent unsupervised multi-object segmentation models on ClevrTex and find all state-of-the-art approaches fail to learn good representations in the textured setting, despite impressive performance on simpler data. We also create variants of the ClevrTex dataset, controlling for different aspects of scene complexity, and probe current approaches for individual shortcomings."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_video: https://slideslive.com/embed/presentation/38969525?embed_parent_url=https%3A%2F%2Fneurips.cc%2Fvirtual%2F2021%2Fdatasets-and-benchmarks%2F38449%23collapse-sl-29871&embed_container_origin=https%3A%2F%2Fneurips.cc&embed_container_id=presentation-embed-38969525
url_pdf: https://arxiv.org/abs/2111.10265
url_code: https://github.com/karazijal/clevrtex-generation
url_dataset: 
url_poster: "clevrtex_poster_fixed.png"
url_project: https://www.robots.ox.ac.uk/~vgg/data/clevrtex/
url_slides:
url_source:


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "BottomLeft"
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
