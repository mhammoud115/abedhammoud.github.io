---
title: "On the potential of Bayesian neural networks for estimating chlorophyll-a concentration from satellite data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Nikolaos Papagiannopoulos
- George Krokos
- Robert J W Brewin
- Dionysios E Raitsos
- Omar Knio
- Ibrahim Hoteit




# author_notes:
# - "Equal contribution"
# - ""
# - ""
# - ""
# - ""


date: "2025-05-23"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-05-23"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: MDPI Remote Sensing
publication_short: in *MDPI-RS*

abstract: This work introduces the use of Bayesian Neural Networks (BNNs) for inferring chlorophyll-a concentration ([CHL-a]) from remotely sensed data. BNNs are probabilistic models that associate a probability distribution to the neural network parameters and rely on Bayes' rule for training. The performance of the proposed probabilistic model is compared to that of standard ocean color algorithms, namely ocean color 4 (OC4) and ocean color index (OCI). An extensive in situ bio-optical dataset was used to train and validate the ocean color models. In contrast to established methods, the BNN allows for enhanced modeling flexibility, where different variables that affect phytoplankton phenology or describe the state of the ocean can be used as additional input for enhanced performance. Our results suggest that BNNs perform at least as well as established methods, and they could achieve 20-40% lower mean squared errors when additional input variables are included, such as the sea surface temperature and its climatological mean alongside the coordinates of the prediction. The BNNs offer means for uncertainty quantification by estimating the probability distribution of [CHL-a], building confidence in the [CHL-a] predictions through the variance of the predictions. Furthermore, the output probability distribution can be used for risk assessment and decision making through analyzing the quantiles and shape of the predicted distribution.



# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.mdpi.com/2072-4292/17/11/1826'
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
