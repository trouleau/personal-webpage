+++
title = "Stochastic Optimal Control of Epidemic Processes in Networks"
date = 2018-11-28T00:00:00
draft = false

# Authors.
authors = [
    "L Lorch", 
    "A De", 
    "S Bhatt", 
    "<em>W Trouleau</em>", 
    "U Upadhyay", 
    "M Gomez-Rodriguez"
]

# Publication type.
publication_types = ["1"]

# Publication name and optional abbreviated version.
# publication_short = "ML4H Workshop at NeurIPS"
publication = "Machine Learning for Health (ML4H) Workshop at NeurIPS"

# Abstract and optional shortened version.
abstract = """
Most of the early work on epidemic processes focused primarily on developing models for general population dynamics rather than the state of any given individual in the population. More recently, there has been research on modeling individual dynamics of epidemics in networks, which has been fueled by the success of network science in explaining other real world processes. However, most of these models ultimately resort to mean-field theory, which precludes them from characterizing the exact state of each individual. As a consequence, they are unable to benefit from the increasing availability of fine-grained data about disease outbreaks.

In this context, an orthogonal line of research aims to design control strategies to mitigate the spread of epidemics in networks using various optimization techniques. However, these approaches share one or more of the following shortcomings, which reduce its applicability in practice: (i) they leverage simple deterministic models of population dynamics and are thus unable to accurately assess the effect of individual treatments; (ii) they propose off-line strategies, often based on graph theoretic quantities, which do not account for the infection and recovery events of a specific epidemic over time, and as a consequence, achieve suboptimal performance; and (iii) they assume that individuals can go on and off of treatment multiple times instantaneously or vary recovery rates arbitrarily, which is not realistic in a real-world setting.

In this work, we approach the development of models and control strategies of epidemic processes from the perspective of marked temporal point processes (MTPPs) and stochastic optimal control of stochastic differential equations (SDEs) with jumps. In contrast to previous work, this novel perspective is particularly well-suited to make use of fine-grained data on disease outbreaks and lets us overcome the shortcomings of current control strategies. More specifically, we focus on susceptible-infected-susceptible (SIS) epidemic processes and represent the times when each individual becomes infected, recovered, or treated using MTPPs. We then exploit an alternative representation using SDEs with jumps, which have recently been introduced in the machine learning literature, to cast the design of control strategies of epidemic processes as a stochastic optimal control problem. The solution to this problem provides us with treatment intensities to determine who to treat and when to do so to minimize the amount of infected individuals over time. Preliminary experiments with synthetic data show that our control strategy consistently outperforms several alternatives. Looking into the future, we believe our methodology provides a promising step towards the development of practical data-driven control strategies of epidemic processes."""

# Is this a selected publication? (true/false)
selected = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Epidemic modeling", "Disease modeling", "SIS", "Optimal Control"]

# Links (optional).
url_full_text = "https://arxiv.org/abs/1810.13043"
url_code = "https://github.com/Networks-Learning/disease-control"

+++
