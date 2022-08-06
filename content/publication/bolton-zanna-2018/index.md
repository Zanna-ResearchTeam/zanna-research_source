---
title: 'Applications of Deep Learning to Ocean Data Inference and Subgrid Parameterization'
authors:
 - T. Bolton
 - admin

date: '2019-01-01T00:00:00Z'
doi: 'https://doi.org/10.1029/2018MS001472'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*JAMES, 11, 376–399*'
publication_short: ''

abstract: Oceanographic observations are limited by sampling rates, while ocean models are limited by finite resolution and high viscosity and diffusion coefficients. Therefore, both data from observations and ocean models lack information at small and fast scales. Methods are needed to either extract information, extrapolate, or upscale existing oceanographic data sets, to account for or represent unresolved physical processes. Here we use machine learning to leverage observations and model data by predicting unresolved turbulent processes and subsurface flow fields. As a proof of concept, we train convolutional neural networks on degraded data from a high-resolution quasi-geostrophic ocean model. We demonstrate that convolutional neural networks successfully replicate the spatiotemporal variability of the subgrid eddy momentum forcing, are capable of generalizing to a range of dynamical behaviors, and can be forced to respect global momentum conservation. The training data of our convolutional neural networks can be subsampled to 10–20% of the original size without a significant decrease in accuracy. We also show that the subsurface flow field can be predicted using only information at the surface (e.g., using only satellite altimetry data). Our results indicate that data-driven approaches can be exploited to predict both subgrid and large-scale processes, while respecting physical principles, even when data are limited to a particular region or external forcing. Our in-depth study presents evidence for the successful design of ocean eddy parameterizations for implementation in coarse-resolution climate models.
summary: 

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.1029/2018MS001472"
url_pdf: /files/Bolton-et-al-2019.pdf/
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.1029/2018MS001472'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ''
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
slides:
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/).
