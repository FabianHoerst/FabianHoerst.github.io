---
title: "Valuing vicinity: Memory attention framework for context-based semantic segmentation in histopathology"
authors:
- Oliver Ester
- admin
- Constantin Seibold
- Julius Keyl
- Saskia Ting
- Nikolaos Vasileiadis
- Jessica Schmitz
- Philipp Ivanyi
- Viktor Grünwald
- Jan Hinrich Bräsen
- Jan Egger
- Jens Kleesiek

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-07-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.compmedimag.2023.102238"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
# publication_short: ""

abstract: The segmentation of histopathological whole slide images into tumourous and non-tumourous types of tissue is a challenging task that requires the consideration of both local and global spatial contexts to classify tumourous regions precisely. The identification of subtypes of tumour tissue complicates the issue as the sharpness of separation decreases and the pathologist’s reasoning is even more guided by spatial context. However, the identification of detailed tissue types is crucial for providing personalized cancer therapies. Due to the high resolution of whole slide images, existing semantic segmentation methods, restricted to isolated image sections, are incapable of processing context information beyond. To take a step towards better context comprehension, we propose a patch neighbour attention mechanism to query the neighbouring tissue context from a patch embedding memory bank and infuse context embeddings into bottleneck hidden feature maps. Our memory attention framework (MAF) mimics a pathologist’s annotation procedure — zooming out and considering surrounding tissue context. The framework can be integrated into any encoder–decoder segmentation method. We evaluate the MAF on two public breast cancer and liver cancer data sets and an internal kidney cancer data set using famous segmentation models (U-Net, DeeplabV3) and demonstrate the superiority over other context-integrating algorithms — achieving a substantial improvement of up to 17% on Dice score. The code is publicly available at https://github.com/tio-ikim/valuing-vicinity.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0895611123000563'
url_code: 'https://github.com/tio-ikim/valuing-vicinity'
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
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
