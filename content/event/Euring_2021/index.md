---
title: Misidentification errors in reencounters result in biased estimates of survival from CJS models

event: EURING analytical meeting
event_url: http://www.phidot.org/euring/index.html

location: Laval University
address:
  #street: 450 Serra Mall
  city: Québec City
  region: PQ
  #postcode: '94305'
  country: Canada

summary: oral presentation at EURING analytical meeting
abstract: "1. Misidentification of marked individual animals due to tag misreads is unavoidable in most studies on wild populations. Models commonly used for the estimation of survival from observations of unique identifiers ignore this potential source of bias. With a simulation study we show that misidentification causes a systematic bias in estimates of survival obtained from the Cormack-Jolly-Seber (CJS) model - survival is positively biased, the bias increases with decreasing true survival and survival spuriously declines over time.

2. We developed an extended robust design capture mark-resight (RDM) model that includes an
estimation of correct identification to get unbiased survival estimates when resighting histories contain misidentification errors. The model assumes that resightings occur repeatedly within a season, which is in practice often the case when resightings from color-marked individuals are collected. We implemented the RDM model in a state-space formulation and also in an approximate, but computationally faster model (RDMa) in JAGS and evaluated their performances by using simulated and real capture-resight data on black-tailed godwits _Limosa l. limosa_.

3. For a range of degrees of misidentification errors the novel RDM model provides unbiased and
accurate estimates of survival, recapture/resighting and correct-identification probabilities. The RDMa model performed well for large datasets (0.25 individuals), with high resighting (0.3) and low misidentification (0.3) probabilities. For the field data on black-tailed godwits, the RDMa model estimated a probability of correct identification, Theta, of 0.92. The unbiased estimates of survival produced by RDMa model were lower than estimates by CJS - the adult survival was estimated at 0.94 vs 0.97 and juvenile at 0.29 vs 0.86.

4. Given that misidentification errors are likely to be common in particular in resighting data, we conclude that survival estimates from many studies obtained from such data from CJS models are likely to be incorrect. The bias becomes larger for higher probabilities of individual misidentification and inevitably increases as datasets become longer. Based on our results we recommend the use of the RDM model to provide unbiased parameter estimates."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-06-10"
#date_end: ""
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: [Eldar Rakhimberdiev]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: '[Laval University](https://www.ulaval.ca/)'
  focal_point: Center

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- Population Ecology of long distance migratory birds
---
