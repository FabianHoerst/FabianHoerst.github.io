---
title: PathoPatcher
summary: 
  PathoPatcher is a Python project designed for accelerating Whole Slide Image Preprocessing, employing AI-based preprocessing techniques with features like annotation handling, color normalization, and configurable parameters - Accelerating Artificial Intelligence Based Whole Slide Image Analysis with an Optimized Preprocessing Pipeline 
tags:
  - Deep Learning
  - Computational Pathology
  - Preprocessing
  - Computer Vision
date: '2024-07-20T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: PathoPatcher Pipeline
  focal_point: Smart

links:
  - icon: python
    icon_pack: fab
    name: Pip
    url: 'pypi.org/project/pathopatch/'
  - icon: github
    icon_pack: fab
    name: GitHub
    url: 'https://github.com/TIO-IKIM/PathoPatcher'

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

As the field of digital pathology continues to advance, the computer-aided analysis of whole slide images (WSI) has become an essential component for cancer diagnosis, staging, biomarker prediction, and therapy evaluation. Despite the latest hardware developments, processing entire slides still demands significant computational resources. Consequently, many WSI analysis pipelines rely on patch-wise processing by tessellating a WSI into smaller sections and aggregating the results to retrieve slide-level outputs.

A commonality among all these algorithms is the necessity for WSI preprocessing to extract patches, with each algorithm having its own requirements, such as sliding window extraction or extracting patches at multiple magnification levels. Addressing these needs, we present PathoPatcher, a novel Python-based software framework designed to accelerate the preprocessing of WSIs.

PathoPatcher leverages NVIDIA’s cuCIM library and parallelization to deliver enhanced preprocessing capabilities. Compared to existing frameworks, PathoPatcher achieves a substantial reduction in processing time while maintaining or even improving the preprocessing quality. With features like annotation handling, color normalization, and configurable parameters, PathoPatcher is set to revolutionize AI-based WSI analysis.

### Key Features of PathoPatcher:
- **Efficient Preprocessing:** Utilizing NVIDIA’s cuCIM library and parallelization for faster processing.
- **Annotation Handling:** Streamlined integration with annotated data.
- **Color Normalization:** Ensuring consistent color profiles across slides.
- **Configurable Parameters:** Flexible settings to cater to diverse algorithm requirements.

Explore the power of PathoPatcher and accelerate your WSI preprocessing pipeline. The code is available under [PathoPatcher GitHub Repository](https://github.com/TIO-IKIM/PathoPatcher).

Join us in advancing digital pathology with PathoPatcher, the optimized preprocessing solution for whole slide image analysis.

**Citation**

```latex
@InProceedings{10.1007/978-3-658-44037-4_91,
    author="H{\"o}rst, Fabian
            and Schaheer, Sajad H.
            and Baldini, Giulia
            and Bahnsen, Fin H.
            and Egger, Jan
            and Kleesiek, Jens",
    editor="Maier, Andreas
            and Deserno, Thomas M.
            and Handels, Heinz
            and Maier-Hein, Klaus
            and Palm, Christoph
            and Tolxdorff, Thomas",
    title="Accelerating Artificial Intelligence-based Whole Slide Image Analysis with an Optimized Preprocessing Pipeline",
    booktitle="Bildverarbeitung f{\"u}r die Medizin 2024",
    year="2024",
    publisher="Springer Fachmedien Wiesbaden",
    address="Wiesbaden",
    pages="356--361",,
    isbn="978-3-658-44037-4"
}