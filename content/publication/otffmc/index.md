---
title: "Improved Projection Learning for Lower Dimensional Feature Maps"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jared Tanner



date: "2023-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*
publication_short: In *ICASSP 2023*

abstract: The requirement to repeatedly move large feature maps off-and on-chip during inference with convolutional neural networks (CNNs) imposes high costs in energy and time. In this work we explore an improved method for compressing all feature maps of pre-trained CNNs to below a specified limit. This is done by means of learned projections trained via end-to-end finetuning, which can then be folded and fused into the pre-trained network. We also introduce a new ‘ceiling compression' framework in which to evaluate such techniques in view of the future goal of performing inference fully on-chip.

# Summary. An optional shortened abstract.
<!-- summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.
 -->

tags: [efficient deep learning, feature map compression]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Paper
  url: https://ieeexplore.ieee.org/abstract/document/10095532
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
