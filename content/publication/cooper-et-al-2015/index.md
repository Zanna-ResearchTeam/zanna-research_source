---
title: 'Optimisation of an idealised ocean model: stochastic parametrisation of sud-grid eddies'
authors:
 - F. Cooper
 - admin


date: '2015-04-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.ocemod.2014.12.014'

# Schedule page publish date (NOT publication's date).
publishDate: '2015-04-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*Ocean Modelling., 88, 38-53*'
publication_short: ''

abstract: 'An optimisation scheme is developed to accurately represent the sub-grid scale forcing of a high dimensional chaotic ocean system. Using a simple parameterisation scheme, the velocity components of a 30 km resolution shallow water ocean model are optimised to have the same climatological mean and variance as that of a less viscous 7.5 km resolution model. The 5 day lag-covariance is also optimised, leading to a more accurate estimate of the high resolution response to forcing using the low resolution model. The system considered is an idealised barotropic double gyre that is chaotic at both resolutions. Using the optimisation scheme, we find and apply the constant in time, but spatially varying, forcing term that is equal to the time integrated forcing of the sub-grid scale eddies. A linear stochastic term, independent of the large-scale flow, with no spatial correlation but a spatially varying amplitude and time scale is used to represent the transient eddies. The climatological mean, variance and 5 day lag-covariance of the velocity from a single high resolution integration is used to provide an optimisation target. No other high resolution statistics are required. Additional programming effort, for example to build a tangent linear or adjoint model, is not required either. The focus of this paper is on the optimisation scheme and the accuracy of the optimised flow. However the forcing can provide insights in the design of deterministic and stochastic parameterisations. In the present study, we found that the stochastic parameterisation correcting the model variance is associated with the spatial pattern of eddy-decorrelation timescales rather than the spatial pattern of the amplitude of the variance. The method can be applied in future investigations into the physical processes that govern barotropic turbulence and it can perhaps be applied to help understand and correct biases in the mean and variance of a more realistic coarse or eddy-permitting ocean model. The method is complementary to current parameterisations and can be applied at the same time without modification.'

summary: 

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.1016/j.ocemod.2014.12.014"
url_pdf: /files/Cooper-Zanna-2015.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.1016/j.ocemod.2014.12.014'
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
