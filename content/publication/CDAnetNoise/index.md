---
title: "Downscaling Using CDAnet Under Observational and Model Noises: The Rayleigh-Bénard Convection Paradigm"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Edriss S. Titi
- Omar Knio
- Ibrahim Hoteit




# author_notes:
# - "Equal contribution"
# - ""
# - ""
# - ""
# - ""


date: "2025-02-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Computational Geosciences
publication_short: in *Comp. Geo.*

abstract: Efficient downscaling of large ensembles of coarse-scale information is crucial in several applications, such as oceanic and atmospheric modeling. The determining form map is a theoretical lifting function from the low-resolution solution trajectories of a dissipative dynamical system to their corresponding high-resolution counterparts. Recently, a physics-informed deep neural network (“CDAnet”) was introduced, providing a surrogate of the determining form map for efficient downscaling. CDAnet was demonstrated to efficiently downscale noise-free coarse-scale data in a deterministic setting. Herein, the performance of well-trained CDAnet models is analyzed in a stochastic setting involving (i) observational noise, (ii) model noise, and (iii) a combination of observational and model noise. The analysis is performed employing the Rayleigh-Bénard convection paradigm, under three training conditions, namely, training with perfect, noisy, or downscaled data. Furthermore, the effects of noise, Rayleigh number, and spatial and temporal resolutions of the input coarse-scale information on the downscaled fields are examined. The results suggest that the expected l2-error of CDAnet behaves quadratically in terms of the standard deviations of the observational and model noise. The results also suggest that CDAnet responds to uncertainties similar to the theorized and numerically-validated CDA behavior with an additional error overhead due to CDAnet being a surrogate of the determining form map.




# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/article/10.1007/s10596-024-10337-3'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary material can be found [here](https://drive.google.com/file/d/17tGxceooVTT0JFkBsQjsh3h529U7yI1v/view?usp=sharing). -->
