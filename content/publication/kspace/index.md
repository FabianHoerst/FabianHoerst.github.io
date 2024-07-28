---
title: "Tumor likelihood estimation on MRI prostate data by utilizing k-Space information"
authors:
- Moritz Rempe
- Fabian Hörst
- Constantin Seibold
- Boris Hadaschik
- Marco Schlimbach
- Jan Egger
- Kevin Kröninger
- Felix Breuer
- Martin Blaimer
- Jens Kleesiek
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-06-04T00:00:00Z"
doi: "https://arxiv.org/abs/2407.06165"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["pre-print"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
# publication_short: ""

abstract: We present a novel preprocessing and prediction pipeline for the classification of magnetic resonance imaging (MRI) that takes advantage of the information rich complex valued k-Space. Using a publicly available MRI raw dataset with 312 subject and a total of 9508 slices, we show the advantage of utilizing the k-Space for better prostate cancer likelihood estimation in comparison to just using the magnitudinal information in the image domain, with an AUROC of 86.1%±1.8%. Additionally, by using high undersampling rates and a simple principal component analysis (PCA) for coil compression, we reduce the time needed for reconstruction by avoiding the time intensive GRAPPA reconstruction algorithm. By using digital undersampling for our experiments, we show that scanning and reconstruction time could be reduced. Even with an undersampling factor of 16, our approach achieves meaningful results, with an AUROC of 71.4%±2.9%, using the PCA coil combination and taking into account the k-Space information. With this study, we were able to show the feasibility of preserving phase and k-Space information, with consistent results. Besides preserving valuable information for further diagnostics, this approach can work without the time intensive ADC and reconstruction calculations, greatly reducing the post processing, as well as potential scanning time, increasing patient comfort and allowing a close to real-time prediction.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/abs/2407.06165'
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
