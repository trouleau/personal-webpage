---
title: "Learning Self-Exciting Temporal Point Processes Under Noisy Observations"
authors:
- admin
date: "2021-06-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "PhD thesis, EPFL"
publication_short: ""

abstract: Understanding the diffusion patterns of sequences of interdependent events is a central question for a variety of disciplines. Temporal point processes are a class of elegant and powerful models of such sequences; these processes have become popular across multiple fields of research due to the increasing availability of data that captures the occurrence of events over time. A notable example is the Hawkes process. It was originally introduced by Alan Hawkes in 1971 to model the diffusion of earthquakes and was subsequently applied across fields such as epidemiology, neuroscience, criminology, finance, genomic, and social-network analysis. A central question in these fields is the inverse problem of uncovering the diffusion patterns of the events from the observed data. The methods for solving this inverse problem assume that, in general, the data is noiseless. However, real-world observations are frequently tainted by noise in a number of ways. Most existing methods are not robust against noise and, in the presence of even a small amount of noise in the data, they might completely fail to recover the underlying dynamics. In this thesis, we remedy this shortcoming and address this problem for several types of observational noise. First, we study the effects of small event-streams that are known to make the learning task challenging by amplifying the risk of overfitting. Using recent advances in variational inference, we introduce a new algorithm that leads to better regularization schemes and provides a measure of uncertainty on the estimated parameters. Second, we consider events corrupted by unknown synchronized time delays. We show that the so-called synchronization noise introduces a bias in the existing estimation methods, which must be handled with care. We provide an algorithm to robustly learn the diffusion dynamics of the underlying process under this class of synchronized delays. Third, we introduce a wider class of random and unknown time shifts, referred to as random translations, of which synchronization noise is a special case. We derive the statistical properties of Hawkes processes subject to random translations. In particular, we prove that the cumulants of Hawkes processes are invariant to random translations and we show that cumulant-based algorithms can be used to learn their underlying causal structure even when unknown time shifts distort the observations. Finally, we consider another class of temporal point processes, the so-called Wold process that solves a computational limitation of the Bayesian treatment of Hawkes processes while retaining similar properties. We address the problem of learning the parameters of a Wold process by relaxing some of the restrictive assumptions made in the state of the art and by introducing a Bayesian approach for inferring its parameters. In summary, the results presented in this dissertation highlight the shortcomings of standard inference methods used to fit temporal point processes. Consequently, these results deepen our ability to extract reliable insights from networks of interdependent event streams.

# Summary. An optional shortened abstract.
summary:

tags: 
featured: false

links:
url_pdf: https://infoscience.epfl.ch/record/288643

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