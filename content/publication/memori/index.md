---
title: "Histology-Based Prediction of Therapy Response to Neoadjuvant Chemotherapy for Esophageal and Esophagogastric Junction Adenocarcinomas Using Deep Learning"
authors:
- admin
- Saskia Ting
- Sven-Thorsten Liffers
- Kelsey L. Pomykala
- Katja Steiger
- Markus Albertsmeier
- Martin K. Angele
- Sylvie Lorenzen
- Michael Quante
- Wilko Weichert
- Jan Egger
- Jens T. Siveke
- Jens Kleesiek
date: "2023-07-01T00:00:00Z"
doi: "https://doi.org/10.1200/CCI.23.00038"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
# publication_short: ""

abstract: Quantifying treatment response to gastroesophageal junction (GEJ) adenocarcinomas is crucial to provide an optimal therapeutic strategy. Routinely taken tissue samples provide an opportunity to enhance existing positron emission tomography-computed tomography (PET/CT)–based therapy response evaluation. Our objective was to investigate if deep learning (DL) algorithms are capable of predicting the therapy response of patients with GEJ adenocarcinoma to neoadjuvant chemotherapy on the basis of histologic tissue samples. This diagnostic study recruited 67 patients with I-III GEJ adenocarcinoma from the multicentric nonrandomized MEMORI trial including three German university hospitals TUM (University Hospital Rechts der Isar, Munich), LMU (Hospital of the Ludwig-Maximilians-University, Munich), and UME (University Hospital Essen, Essen). All patients underwent baseline PET/CT scans and esophageal biopsy before and 14-21 days after treatment initiation. Treatment response was defined as a ≥35% decrease in SUVmax from baseline. Several DL algorithms were developed to predict PET/CT-based responders and nonresponders to neoadjuvant chemotherapy using digitized histopathologic whole slide images (WSIs). The resulting models were trained on TUM (n = 25 pretherapy, n = 47 on-therapy) patients and evaluated on our internal validation cohort from LMU and UME (n = 17 pretherapy, n = 15 on-therapy). Compared with multiple architectures, the best pretherapy network achieves an area under the receiver operating characteristic curve (AUROC) of 0.81 (95% CI, 0.61 to 1.00), an area under the precision-recall curve (AUPRC) of 0.82 (95% CI, 0.61 to 1.00), a balanced accuracy of 0.78 (95% CI, 0.60 to 0.94), and a Matthews correlation coefficient (MCC) of 0.55 (95% CI, 0.18 to 0.88). The best on-therapy network achieves an AUROC of 0.84 (95% CI, 0.64 to 1.00), an AUPRC of 0.82 (95% CI, 0.56 to 1.00), a balanced accuracy of 0.80 (95% CI, 0.65 to 1.00), and a MCC of 0.71 (95% CI, 0.38 to 1.00). Our results show that DL algorithms can predict treatment response to neoadjuvant chemotherapy using WSI with high accuracy even before therapy initiation, suggesting the presence of predictive morphologic tissue biomarkers.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
# url: 'www.ascopubs.org/doi/full/10.1200/CCI.23.00038'
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

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
