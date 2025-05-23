---
title: "Two-step AI-aided Bayesian source identification of urban-scale pollution"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Elissar ElAawar
- admin
- Ibrahim Hoteit




# author_notes:
# - "Equal contribution"
# - ""
# - ""
# - ""
# - ""


date: "2024-04-15"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-15"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Atmospheric Environment
publication_short: in *Atmospheric Environment*

abstract: Poor air quality produces detrimental effects worldwide; hence, it is vital to thoroughly characterize air pollution sources and effectively address and mitigate such effects. Due to the complexity of the underlying physical processes, and uncertainties in the available observations, the air pollution source identification problem is typically cast within a Bayesian inversion framework. The latter incorporates prior knowledge and observations to characterize a release event through the posterior distribution of the source parameters. In this study, we rely on two-dimensional (2D) pollutant concentration distributions as observations, and adopt the Wasserstein (W2) distance to model the likelihood probability distribution for given emission parameters. Since the posterior distribution is estimated via random sampling that involves many forward model runs, the Bayesian framework can be computationally prohibitive for realistic urban air pollution problems that are driven by computationally demanding micro-scale flow simulations. Furthermore, computing the W2 distance is resource-intensive . In this context, we develop a computationally efficient Bayesian framework by following (i) a two-stage approach that reduces the cost of the Bayesian inversion, and (ii) an artificial intelligence (AI) approximation of the W2 distance. In the two-stage approach, a low-resolution dispersion model is run in the first stage to propose representative samples of emission parameters for final selection by the original high-resolution model in the second stage. In addition, we approximate the W2 distance using a deep neural network (DNN) to achieve an appreciable reduction in the computational cost with negligible loss in the inversion performance. We design numerical experiments to test the sensitivity of the inverse solution to the characteristics of the approximative model. The results indicate that pairing the two-stage approach with the DNN approximation of the W2 distance preserves the quality of the inverse solution, while achieving at least threefold reductions in the computational cost.


# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S1352231024000633'
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
