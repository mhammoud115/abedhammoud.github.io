---
title: "Semantic Segmentation of Mesoscale Eddies in the Arabian Sea: A Deep Learning Approach"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Peng Zhan
- Omar Hakla
- Omar Knio
- Ibrahim Hoteit




# author_notes:
# - "Equal contribution"
# - ""
# - ""
# - ""
# - ""


date: "2023-03-10"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-10"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: MDPI Remote Sensing
publication_short: in *MDPI RS*

abstract: Detecting mesoscale ocean eddies provides a better understanding of the oceanic processes that govern the transport of salt, heat, and carbon. Established eddy detection techniques rely on physical or geometric criteria, and they notoriously fail to predict eddies that are neither circular nor elliptical in shape. Recently, deep learning techniques have been applied for semantic segmentation of mesoscale eddies, relying on the outputs of traditional eddy detection algorithms to supervise the training of the neural network. However, this approach limits the network’s predictions because the available annotations are either circular or elliptical. Moreover, current approaches depend on the sea-surface height, temperature, or currents as inputs to the network, and these data may not provide all the information necessary to accurately segment eddies. In the present work, we have trained a neural network for the semantic segmentation of eddies using human-based—and expert-validated—annotations of eddies in the Arabian Sea. Training with human-annotated datasets enables the network predictions to include more complex geometries, which occur commonly in the real ocean. We then examine the impact of different combinations of input surface variables on the segmentation performance of the network. The results indicate that providing additional surface variables as inputs to the network improves the accuracy of the predictions by approximately 5%. We have further fine-tuned another pre-trained neural network to segment eddies and achieved a reduced overall training time and higher accuracy compared to the results from a network trained from scratch.





# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.mdpi.com/2072-4292/15/6/1525'
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
