---
title: 'Self-Attentive Sequential Recommendation Models Enriched with More Features'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Sang Thi Thanh Nguyen

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-07-15T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Proceedings of the 2024 8th International Conference on Deep Learning Technologies"
  short_name: "ICDLT"

peer_reviewed: true
open_access: true
license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
awards:
  - name: "Online Presentation"
    level: selected

# Funders and grants. Required by many funders for compliance reporting.
funding:
  - funder: "Vietnam National University -VNU"
    grant: "C-2024"

abstract: Recommender systems have become essential for alleviating information overload by providing personalized suggestions, with traditional collaborative filtering methods based on matrix factorization widely adopted but often struggling to capture dynamic user interests and complex item relationships. Recently, deep learning techniques utilizing the attention mechanism have shown promise in modeling sequential user behavior for recommendation tasks by leveraging self-attention to identify relevant historical interactions when predicting the next item of interest. However, these models primarily rely on raw interaction sequences, failing to exploit auxiliary information, such as user ratings and item categories that could further enhance recommendation accuracy. In this study, we propose a self-attentive sequential recommendation method that enriches input representations by incorporating user ratings to capture explicit preferences and item categories to capture semantic relationships between items, extending the self-attention architecture to attend to the combination of interaction sequences, ratings, and categories. Through extensive experiments on public datasets, we demonstrate that our proposed method exhibits relative strengths in capturing certain aspects of user-item relationships, leading to competitive performance compared to original models across different recommendation quality metrics.

# Summary. An optional shortened abstract.
summary: In this study, we propose a self-attentive sequential recommendation method that enriches input representations by incorporating user ratings to capture explicit preferences and item categories to capture semantic relationships between items, extending the self-attention architecture to attend to the combination of interaction sequences, ratings, and categories.

tags:
  - Sequential Recommendation Models

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3695719.3695727

# Custom links
links:
  - type: pdf
    url: ""
  - type: dataset
    url: https://jmcauley.ucsd.edu/data/amazon_v2/index.html
  - type: source
    url: https://github.com/hdhtrong/EnrichedTiSASRec-Pytorch

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
