---
title: "Accelerating Artificial Intelligence-based Whole Slide Image Analysis with an Optimized Preprocessing Pipeline"
authors:
- Fabian Hörst
- Sajad H Schaheer
- Giulia Baldini
- Fin H Bahnsen
- Jan Egger
- Jens Kleesiek
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-02-20T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-658-44037-4_91"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-02-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
# publication_short: ""

abstract: 'As the field of digital pathology continues to advance, the computeraided analysis of whole slide images (WSI) has become an essential component for cancer diagnosis, staging, biomarker prediction, and therapy evaluation. However, even with the latest hardware developments, the processing of entire slides still demands significant computational resources. Therefore, many WSI analysis pipelines rely on patch-wise processing by tessellating a WSI into smaller sections and aggregating the results to retrieve slide-level outputs.One commonality among all these algorithms is the necessity for WSI preprocessing to extract patches, with each algorithm having its own requirements such as sliding window extraction or extracting patches at multiple magnification levels. In this paper, we present a novel Python-based software framework that leverages NVIDIA’s cuCIM library and parallelization to accelerate the preprocessing of WSIs, named PathoPatch. Compared to existing frameworks, we achieve a substantial reduction in processing time while maintaining or even improving the preprocessing capabilities.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-658-44037-4_91'
url_code: ''
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
