---
title: CellViT
summary: 
  CellViT sets the benchmark for nuclei instance segmentation, surpassing existing methods on the PanNuke dataset with remarkable performance improvements. This cutting-edge project integrates the power of Vision Transformer (ViT) encoders, enhancing segmentation accuracy, and leverages a U-Net architecture for efficient feature extraction. With fast inference capabilities on gigapixel Whole Slide Images (WSI), CellViT promises to revolutionize the field of cell analysis in computational pathology.
tags:
  - Deep Learning
  - Computational Pathology
  - Cell Analysis
  - Single Cell Analysis
  - Computer Vision
date: '2023-10-20T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: CellViT Visualization
  focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

CellViT is an advanced deep learning-based method designed for automated instance segmentation of cell nuclei within digitized tissue samples. This project achieves exceptional performance, surpassing existing methods with remarkable results on the challenging PanNuke dataset. The software is widely used in the community, with **>175 stars on GitHub and >30.000 website accesses**. CellViT is used by many research institutes, including Harvard University.

Some key features of CellViT include:

- **State-of-the-Art Performance**: CellViT outperforms existing methods for nuclei instance segmentation, achieving a mean panoptic quality of 0.51 and an F1-detection score of 0.83 on the PanNuke dataset.

- **Vision Transformer Encoder**: CellViT incorporates pre-trained Vision Transformer (ViT) encoders, renowned for their effectiveness in various computer vision tasks. This choice significantly enhances the segmentation performance of CellViT.

- **U-Net Architecture**: CellViT adopts a U-Net-shaped encoder-decoder network structure, which facilitates both high-level and low-level feature extraction. This architecture enables efficient and accurate nuclei instance segmentation.

- **Weighted Sampling Strategy**: CellViT introduces a novel weighted sampling strategy to enhance performance. This strategy improves the representation of challenging nuclei instances, resulting in more accurate segmentation.

- **Fast Inference on Gigapixel WSI**: CellViT provides rapid inference results by utilizing a large inference patch size of 1024x1024 pixels, as opposed to conventional 256-pixel-sized patches. This approach allows for efficient analysis of Gigapixel Whole Slide Images (WSI) and generates localizable deep features. Additionally, a fast inference pipeline is provided with a connection to current Viewing Software like QuPath.

This powerful tool is an essential asset in the field of computational pathology, offering state-of-the-art capabilities for precise cell segmentation and classification. If you intend to use CellViT, please remember to cite the original publication for your research.

**Citation**

```latex
@article{Hrst2024,
  title = {CellViT: Vision Transformers for precise cell segmentation and classification},
  volume = {94},
  ISSN = {1361-8415},
  url = {http://dx.doi.org/10.1016/j.media.2024.103143},
  DOI = {10.1016/j.media.2024.103143},
  journal = {Medical Image Analysis},
  publisher = {Elsevier BV},
  author = {H\"{o}rst,  Fabian and Rempe,  Moritz and Heine,  Lukas and Seibold,  Constantin and Keyl,  Julius and Baldini,  Giulia and Ugurel,  Selma and Siveke,  Jens and Gr\"{u}nwald,  Barbara and Egger,  Jan and Kleesiek,  Jens},
  year = {2024},
  month = may,
  pages = {103143}
}