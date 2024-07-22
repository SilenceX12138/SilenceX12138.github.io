---
title: 'ProtoGate: Prototype-based Neural Networks with Global-to-local Feature Selection for Tabular Biomedical Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Andrei Margeloiu
  - Nikola Simidjievski
  - Mateja Jamnik

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# date: '2013-07-01T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-03T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In Forty-first International Conference on Machine Learning
publication_short: ICML2024

abstract: Tabular biomedical data poses challenges in machine learning because it is often high-dimensional and typically low-sample-size (HDLSS). Previous research has attempted to address these challenges via local feature selection, but existing approaches often fail to achieve optimal performance due to their limitation in identifying globally important features and their susceptibility to the co-adaptation problem. In this paper, we propose ProtoGate, a prototype-based neural model for feature selection on HDLSS data. ProtoGate first selects instance-wise features via adaptively balancing global and local feature selection. Furthermore, ProtoGate employs a non-parametric prototype-based prediction mechanism to tackle the co-adaptation problem, ensuring the feature selection results and predictions are consistent with underlying data clusters. We conduct comprehensive experiments to evaluate the performance and interpretability of ProtoGate on synthetic and real-world datasets. The results show that ProtoGate generally outperforms state-of-the-art methods in prediction accuracy by a clear margin while providing high-fidelity feature selection and explainable predictions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://icml.cc/virtual/2024/poster/35215'
url_code: 'https://github.com/SilenceX12138/ProtoGate'
url_dataset: ''
url_poster: 'https://icml.cc/media/PosterPDFs/ICML%202024/35215.png?t=1719613791.1975074'
url_project: 'https://github.com/SilenceX12138/ProtoGate'
url_slides: 'https://icml.cc/media/icml-2024/Slides/35215.pdf'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=21BedzrsvSg'

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
