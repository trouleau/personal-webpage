---
title: "Quantifying the Effects of Contact Tracing, Testing, and Containment Measures in the Presence of Infection Hotspots"
authors:
- Lars Lorch
- Heiner Kremer
- admin
- Stratis Tsirtsis
- Aron Szanto
- Berned Schölkopf
- Manuel Gomez-Rodriguez
date: "2022-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Spatial Algorithms and Systems"
publication_short: ""

abstract: Multiple lines of evidence at the individual and population level strongly suggest that infection hotspots, or superspreading events, where a single individual infects many others, play a key role in the transmission dynamics of COVID-19. However, most of the existing epidemiological models either assume or result in a Poisson distribution of the number of infections caused by a single infectious individual, often called secondary infections. As a result, these models overlook the observed overdispersion in the number of secondary infections and are unable to accurately characterize infection hotspots. In this work, we aim to fill this gap by introducing a temporal point process framework that explicitly represents sites where infection hotspots may occur. Under our model, overdispersion on the number of secondary infections emerges naturally. Moreover, using an efficient sampling algorithm, we demonstrate how to apply Bayesian optimization with longitudinal case data to estimate the transmission rate of infectious individuals at sites they visit and in their households, as well as the mobility reduction due to social distancing. Simulations using fine-grained demographic data and site locations from several cities and regions demonstrate that our framework faithfully characterizes the observed longitudinal trend of COVID-19 cases. In addition, the simulations show that our model can be used to estimate the effect of testing, contact tracing, and containment at an unprecedented spatiotemporal resolution, and reveal that these measures do not decrease overdispersion in the number of secondary infections.

# Summary. An optional shortened abstract.
summary:

tags:
featured: false

links:
url_pdf: https://dl.acm.org/doi/10.1145/3530774
url_code: https://github.com/covid19-model

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:

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
slides: ""
---