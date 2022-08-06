---
title: 'GCM-Filters: A Python Package for Diffusion-based Spatial Filtering of Gridded Data'

authors:
- N.Loose
- R. Abernathey
- I. Grooms
- J. Busecke
- A. Guillaumin
- E. Yankovsky
- G. Marques
- J. Steinberg
- A.S. Ross
- H. Khatri
- S. Bachman 
- admin 
- P. Martin


date: '2022-02-11T00:00:00Z'
doi: 'https://doi.org/10.21105/joss.03947'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-07-26T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*Journal of Open Source Software,7,70,3947*'
publication_short: ''

abstract: 'GCM-Filters is a python package that allows scientists to perform spatial filtering analysis in an easy, flexible and efficient way. The package implements the filtering method based on the discrete Laplacian operator that was introduced by Grooms et al.(2021). The filtering algorithm is analogous to smoothing via diffusion; hence the name diffusion-based filters. GCM-Filters can be used with either gridded observational data or gridded data that is produced by General Circulation Models (GCMs) of ocean, weather, and climate. Spatial filtering of observational or GCM data is a common analysis method in the Earth Sciences, for example to study oceanic and atmospheric motions at different spatial scales or to develop subgrid-scale parameterizations for ocean models. GCM-Filters provides filters that are highly configurable, with the goal to be useful for a wide range of scientific applications. The user has different options for selecting the filter scale and filter shape. The filter scale can be defined in several ways: a fixed length scale (eg, 100 km), a scale tied to a model grid scale (eg, 1◦), or a scale tied to a varying dynamical scale (eg, the Rossby radius of deformation). As an example, Figure 1 shows unfiltered and filtered relative vorticity, where the filter scale is set to a model grid scale of 4◦. GCM-Filters also allows for anisotropic, ie, direction-dependent, filtering. Finally, the filter shape–currently: either Gaussian or Taper–determines how sharply the filter separates scales above and below the target filter scale.'


summary: 

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.21105/joss.03947"
url_pdf: '/files/Loose-et-al-2022.pdf'
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.21105/joss.03947'
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
