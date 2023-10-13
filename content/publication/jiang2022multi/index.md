---
title: 'Multi-view Human Body Mesh Translator'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Xuecheng Nie
  - Zitian Wang
  - Luoqi Liu
  - Si Liu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# pre-print
publication_types: ["article"]
# journal
# publication_types: ["article-journal"]
# conference
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Existing methods for human mesh recovery mainly focus on single-view frameworks, but they often fail to produce accurate results due to the ill-posed setup. Considering the maturity of the multi-view motion capture system, in this paper, we propose to solve the prior ill-posed problem by leveraging multiple images from different views, thus significantly enhancing the quality of recovered meshes. In particular, we present a novel \textbf{M}ulti-view human body \textbf{M}esh \textbf{T}ranslator (MMT) model for estimating human body mesh with the help of vision transformer. Specifically, MMT takes multi-view images as input and translates them to targeted meshes in a single-forward manner. MMT fuses features of different views in both encoding and decoding phases, leading to representations embedded with global information. Additionally, to ensure the tokens are intensively focused on the human pose and shape, MMT conducts cross-view alignment at the feature level by projecting 3D keypoint positions to each view and enforcing their consistency in geometry constraints. Comprehensive experiments demonstrate that MMT outperforms existing single or multi-view models by a large margin for human mesh recovery task, notably, 28.8\% improvement in MPVE over the current state-of-the-art method on the challenging HUMBI dataset. Qualitative evaluation also verifies the effectiveness of MMT in reconstructing high-quality human mesh. Codes will be made available upon acceptance.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2210.01886'
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
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
