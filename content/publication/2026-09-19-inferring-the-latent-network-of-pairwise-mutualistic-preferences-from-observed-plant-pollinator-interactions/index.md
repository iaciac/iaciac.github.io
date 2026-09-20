---
title: "Inferring the latent network of pairwise mutualistic preferences from observed plant–pollinator interactions
"
authors: ["L. Federici", "E. Matechou", admin]
date: "2026-09-19"
doi: "https://doi.org/10.64898/2026.09.17.751682"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-19"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*arXiv*"
publication_short: ""

abstract: "Plant–pollinator communities are typically represented as bipartite networks, whose edges are taken directly from field records of visits. These visits, however, are only a proxy for the object of ecological interest: the latent mutualistic preference between two species. While counts are shaped by preference, they also carry confounding factors such as species abundances, sampling effort, and site- or time-specific conditions. We introduce a hierarchical Bayesian framework that treats visit counts as a realisation of a Poisson process and, on the log scale, decomposes the corresponding pairwise rate into a baseline (community-wide activity together with sampling effort), individual species effects representing abundance, and pairwise mutualistic preferences. The model extends to data replicated across sites and time points, and to the inclusion of environmental or experimental covariates. Because the whole system is fitted jointly, we obtain posterior not only for the preferences but for every latent quantity, each carrying ecological signal of its own, with uncertainty propagated through every level of the model, down to any derived network metric. On synthetic data, we show that common practices, such as reading preferences off raw counts or aggregating replicated observations into a single network, confound abundance with preference. In contrast, our framework recovers the underlying preference structure. On empirical datasets, including a seasonal multi-site pollination study where urbanisation level enters as a covariate, the inferred preference network departs markedly from the observed visits, revealing structure hidden in the raw counts: how species vary across sites and time, and which parts of the community respond most to the covariate. When communities are compared along the urbanisation gradient, standard network metrics on the preference layer revise the conclusions drawn from visits alone. The framework offers a principled way to move from networks of observed visits to networks of underlying mutualistic preferences, carrying uncertainty from the data through to the ecological conclusions and accommodating the spatial, temporal, and covariate structure of modern plant–pollinator datasets. Because it acts on the foundational step of network construction, its implications are broad, placing network-based approaches on firmer ground."

# Summary. An optional shortened abstract.
summary: ""

tags: ["mutualistic networks", "plant–pollinator", "Bayesian modelling", "ecology"]
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://www.biorxiv.org/content/10.64898/2026.09.17.751682v1"
url_code: 
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
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: [example]
---
