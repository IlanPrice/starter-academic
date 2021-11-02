---
title: "Gaussian processes for unconstraining demand"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jaroslav Fowkes
- Daniel Hopman



date: "2019-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *European Journal of Operational Research*
publication_short: In *EJOR*

abstract: One of the key challenges in revenue management is unconstraining demand data. Existing state of the art single-class unconstraining methods make restrictive assumptions about the form of the underlying demand and can perform poorly when applied to data which breaks these assumptions. In this paper, we propose a novel unconstraining method that uses Gaussian process (GP) regression. We develop a novel GP model by constructing and implementing a new non-stationary covariance function for the GP which enables it to learn and extrapolate the underlying demand trend. We show that this method can cope with important features of realistic demand data, including nonlinear demand trends, variations in total demand, lengthy periods of constraining, non-exponential inter-arrival times, and discontinuities/changepoints in demand data. In all such circumstances, our results indicate that GPs outperform existing single-class unconstraining methods.

# Summary. An optional shortened abstract.
<!-- summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
 -->

tags: [Gaussian process regression, demand unconstraining]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

links:
- name: PDF
  url: https://www.sciencedirect.com/science/article/pii/S0377221718310063

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
  caption: 'Demand unconstraining'
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
