---
title: "A Physics-Informed Deep Neural Network for Backward in Time Prediction: Application to Rayleigh-Bénard Convection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Humam Al-Wassel
- Bernard Ghanem
- Omar Knio
- Ibrahim Hoteit




# author_notes:
# - "Equal contribution"
# - ""
# - ""
# - ""
# - ""


date: "2023-01-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: American Meteorological Society, Artificial Intelligence for the Earth Systems
publication_short: in *AMS AIES*

abstract: Backward-in-time predictions are needed to better understand the underlying dynamics of physical fluid flows and improve future forecasts. However, integrating fluid flows backward in time is challenging because of numerical instabilities caused by the diffusive nature of the fluid systems and nonlinearities of the governing equations. Although this problem has been long addressed using a nonpositive diffusion coefficient when integrating backward, it is notoriously inaccurate. In this study, a physics-informed deep neural network (PI-DNN) is presented to predict past states of a dissipative dynamical system from snapshots of the subsequent evolution of the system state. The performance of the PI-DNN is investigated using several systematic numerical experiments and the accuracy of the backward-in-time predictions is evaluated in terms of different error metrics. The proposed PI-DNN can predict the previous state of the Rayleigh–Bénard convection with an 8-time-step average normalized l2 error of less than 2% for a turbulent flow at a Rayleigh number of 105.




# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://journals.ametsoc.org/view/journals/aies/2/1/AIES-D-22-0076.1.xml'
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
