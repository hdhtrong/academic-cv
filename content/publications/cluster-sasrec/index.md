---
title: 'Self-Attentive Sequential Recommendation with User Preference Clustering'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Thi Thanh Sang Nguyen

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-06-12T00:00:00Z'
# Schedule page publish date (NOT publication's date).
publishDate: '2026-06-12T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "The 17th FLINS Conference & the 21st ISKE Conference: Machine Learning and Knowledge Engineering for Decision Making"
  short_name: "FLINS-ISKE 2026"

peer_reviewed: true
open_access: true
license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# awards:
#   - name: ""
#     level: selected

# Funders and grants. Required by many funders for compliance reporting.
funding:
  - funder: "Vietnam National University -VNU"
    grant: "C-2024"

abstract: Sequential recommendation has become an effective approach for modeling user behavior in recommender systems such as e-commerce and social networking platforms. Among existing approaches, self-attentive models have significantly improved the ability to capture sequential dependencies in user interactions. However, most self-attentive sequential recommendation models mainly rely on interaction sequences and often overlook higher-level preference patterns shared among users. In this study, we propose a user preference clustering approach to enhance self-attentive sequential recommendation. Specifically, user embeddings are first derived from historical user–item interactions to represent latent preference patterns. Users are then grouped into clusters using a Gaussian Mixture Model (GMM), where each cluster represents a group of users with similar behavioral preferences. The obtained cluster information is incorporated as an additional feature into the input of self-attentive sequential recommendation models. Based on this idea, we develop a framework called ClusterSASRec, which integrates user preference clustering with existing SASRec-based models to provide cluster-aware sequential recommendations. Experimental results on two public datasets show that the proposed method demonstrates consistent improvements over the corresponding baseline models.

# Summary. An optional shortened abstract.
summary: Accepted at FLINS-ISKE 2026. The conference will be held in July 2026. In this study, we develop a framework called ClusterSASRec, which integrates user preference clustering with existing SASRec-based models to provide cluster-aware sequential recommendations

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
    url: ""

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

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
