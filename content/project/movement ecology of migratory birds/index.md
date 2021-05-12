---
title: Movement ecology of migratory birds
summary: Conservation of population of migratory birds requires knowledge of their annual routines. To study bird migration I develop and apply a range of animal tracking techniques from stable isotopes and solar geolocation, to Argos Doppler and recently GPS tracking with ICARUS tags.
tags:
- Movement Ecology
date: "2021-05-10T00:00:00Z"

weight: 1

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ''
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

image:
  caption: ''
  focal_point: ''
  preview_only: yes

header:
   image: solar_geolocation.jpg
   caption: "twilights over Earth"
---

Conservation of populations of migratory birds requires knowledge of their annual routines. To study bird migration I develop and apply a range of animal tracking techniques from stable isotopes and solar geolocation, to Argos Doppler and recently GPS tracking with ICARUS tags. 

__1. Solar geolocation.__ Working at Cornell I focused on developing statistical methods and software for the analysis of data collected by solar geolocators. Solar geolocators record light intensity values over time and are the lightest (0.34 g) available trackers that can be deployed on birds of a broad range of body size. I have developed a hidden Markov model that allows estimation of the geographic position of an animal from the recorded light levels. The likelihood of the model matches the observed rate of change in light intensity versus the expected one (Rakhimberdiev _et al._ Mov. Ecol. 2015). Implemented in the CRAN R package FLightR, the model provides estimates of migration schedules, locations and migratory routes of the tracked birds (Rakhimberdiev et. al., Methods Ecol. Evol. 2017, see also [my blog post]( https://methodsblog.com/2018/06/12/solar-geolocation/) ). The accuracy and precision of the model was tested in a study tracking a black-tailed godwit wearing two tags – a GPS and a geolocator (Rakhimberdiev et al. J. Avian Biol. 2016).

Recently we published a review on solar geolocation analysis methods in the Journal of Animal Ecology (Lisovski et. al. 2020).

**NB**: For my limited capacity for answering all FLightR and other geolocation related questions over email, please, consider [ornithologyexchange](http://ornithologyexchange.org/forums/forum/259-geolocator-discussion-support/) and open issues for package problems at the [dedicated GitHub page](https://github.com/eldarrak/FLightR/issues).

__2. Isotope signatures in tissues.__ For the birds recaptured after the migration flights we have developed an approach inferring duration of stopover based on the different rate of change of isotopic signatures between tissues (in this case blood plasma and cells). This method can be applied to birds of any size and allows to figure out whether an animal made a stop on the way and for how long did it stay.

__3. Argos Doppler tracking.__ This technique is the most used for tracking of migratory birds whose body mass exceeds 100g. It works well for studies at a continental scale, e.g. to explore whether bar-tailed godwits made stops migrating from the Wadden Sea, Northern Europe, to the Taimyr Peninsula, Arctic Russia (Nat. Comms. 2018). A serious issue of Argos Doppler tracking is that the positions have strongly varying spatial errors. Although Argos system supplies the information on the errors and strongly recommends using this information in the analyses, this recommendation is rarely followed. In collaboration with Dr. Julia Karagicheva I developed an approach that allows to account for these uncertainties in habitat use studies (Karagicheva et al. _in prep._).

__4. GPS tracking.__ GPS tracking is becoming leading technology in animal movement studies, as GPS provides yet the highest  precision geographic positions, while miniaturization of GPS chips enables their use on a progressively broader spectrum of animals. The main limitation of GPS tracking is data transmission to the user as it commonly requires close contact with the tracked animal, e.g. in the [UvA-BiTS system](https://www.uva-bits.nl/), developed at the University of Amsterdam, it takes tens of minutes to transmit data from the tag to handheld  (Rakhimberdiev et. al. 2015). At the moment the global data transmission is just becoming available via the antenna installed in the International Space Station ([ICARUS initiative](https://www.icarus.mpg.de/en)). Over the last five years I was involved with beta testing of this system and am currently deploying ICARUS tags on Black-tailed godwits. Finally, in 2021, ICARUS works without any problems.

__5. Data storage infrastructures.__ There are several platforms for cloud storage and analysis of the movement data with the largest of them  – Movebank –accommodating principally all movement data types, from geolocator to ICARUS. I collaborate with Sarah Davidson on development of Movebank data standards (co-PI on solar geolocation data standard and software development at [NCEAS project establishing open source animal tracking analysis platform for archival geolocators]( https://www.nceas.ucsb.edu/workinggroups/establishing-open-source-animal-tracking-analysis-platform-archival-geolocators)), and with Martin Wikelski and Walter Jetz on development of data sharing licenses and cloud analysis services.
