---
title: "CDAnet: A Physics-Informed Deep Neural Network for Downscaling Fluid Flows"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Edriss S. Titi
- Ibrahim Hoteit
- Omar Knio


# author_notes:
# - "Equal contribution"
# - ""
# - ""
# - ""
# - ""


date: "2023-03-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: AGU Journal of Advances in Modeling Earth Systems
publication_short: in *JAMES*

abstract: Generating high-resolution flow fields is of paramount importance for various applications in engineering and climate sciences. This is typically achieved by solving the governing dynamical equations on high-resolution meshes, suitably nudged toward available coarse-scale data. To alleviate the computational cost of such downscaling process, we develop a physics-informed deep neural network (PI-DNN) that mimics the mapping of coarse-scale information into their fine-scale counterparts of continuous data assimilation (CDA). Specifically, the PI-DNN is trained within the theoretical framework described by Foias et al. (2014) to generate a surrogate of the theorized determining form map from the coarse-resolution data to the fine-resolution solution. We demonstrate the PI-DNN methodology through application to 2D Rayleigh-Bénard convection, and assess its performance by contrasting its predictions against those obtained by dynamical downscaling using CDA. The analysis suggests that the surrogate is constrained by similar conditions, in terms of spatio-temporal resolution of the input, as the ones required by the theoretical determining form map. The numerical results also suggest that the surrogate's downscaled fields are of comparable accuracy to those obtained by dynamically downscaling using CDA. Consistent with the analysis of Farhat, Jolly, and Titi (2015), temperature observations are not needed for the PI-DNN to predict the fine-scale velocity, pressure and temperature fields.




# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2022MS003051'
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
