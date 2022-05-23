---
title: "Increasing the accuracy and resolution of precipitation forecasts using deep generative models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Stephan Rasp



date: "2021-10-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: The 25th International Conference on Artificial Intelligence and Statistics
publication_short: AISTATS 2022

abstract: Accurately forecasting extreme rainfall is notoriously difficult, but is also ever more crucial for society as climate change increases the frequency of such extremes. Global numerical weather prediction models often fail to capture extremes, and are produced at too low a resolution to be actionable, while regional, high-resolution models are hugely expensive both in computation and labour. In this paper we explore the use of deep generative models to simultaneously correct and downscale (super-resolve) global ensemble forecasts over the Continental US. Specifically, using fine-grained radar observations as our ground truth, we train a conditional Generative Adversarial Network — coined CorrectorGAN — via a custom training procedure and augmented loss function, to produce ensembles of high-resolution, bias-corrected forecasts based on coarse, global precipitation forecasts in addition to other relevant meteorological fields. Our model significantly outperforms an interpolation baseline, and approaches the performance of an operational regional high-resolution model across an array of established probabilistic metrics. Crucially, CorrectorGAN, once trained, produces predictions in seconds on a single machine. These results raise exciting questions about the necessity of regional models, and whether data-driven downscaling and correction methods can be transferred to data-poor regions that so far have had no access to high-resolution forecasts.

# Summary. An optional shortened abstract.
<!-- summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
 -->

tags: [GANs, precipitation forecasting, forecast downscaling]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
#
# - name: Custom Link -->
# url: 'https://example.org'
links:
- name: PDF
  url: 'https://proceedings.mlr.press/v151/price22a/price22a.pdf'
- name: Code
  url: 'https://github.com/raspstephan/nwp-downscale'

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
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
<!-- projects:
- example -->

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
<!-- slides: example -->

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
