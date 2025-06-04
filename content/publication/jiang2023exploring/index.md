---
title: "Exploring Time Granularity on Temporal Graphs for Dynamic Link Prediction in Real-world Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yanyi Pu

# Author notes (optional)
author_notes:
  - "Equal contribution"
  - "Equal contribution"

# date: '2013-07-01T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# pre-print
# publication_types: ["article"]
# journal
# publication_types: ["article-journal"]
# conference
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In NeurIPS 2023 Workshop "Temporal Graph Learning Workshop (TGL)"
publication_short: NeurIPS 2023 Workshop

abstract: Dynamic Graph Neural Networks (DGNNs) have emerged as the predominant approach for processing dynamic graph-structured data. However, the influence of temporal information on model performance and robustness remains insufficiently explored, particularly regarding how models address prediction tasks with different time granularities. In this paper, we explore the impact of time granularity when training DGNNs on dynamic graphs through extensive experiments. We examine graphs derived from various domains and compare three different DGNNs to the baseline model across four varied time granularities. We mainly consider the interplay between time granularities, model architectures, and negative sampling strategies to obtain general conclusions. Our results reveal that a sophisticated memory mechanism and proper time granularity are crucial for a DGNN to deliver competitive and robust performance in the dynamic link prediction task. We also discuss drawbacks in considered models and datasets and propose promising directions for future research on the time granularity of temporal graphs.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: "https://arxiv.org/pdf/2311.12255"
url_code: "https://github.com/SilenceX12138/Time-Granularity-on-Temporal-Graphs"
url_dataset: "https://github.com/SilenceX12138/Time-Granularity-on-Temporal-Graphs"
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""
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
