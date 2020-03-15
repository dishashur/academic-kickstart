---
title: Inverse microwave imaging
summary: Adaptive resolution based tumor imaging
#tags:
#- Deep Learning
date: "2017-06-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
 caption: Reconstruction with a contrast of 1
 focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
#url_pdf: ""
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Microwave imaging has been a promising concept, since its inception, for the detection of subsurface objects such as breast tumors due to a relative difference in the permittivity (technically, contrast) of the cancerous cells. Due to the underlying equations of Electromagnetic scattering, to reconstruct the contrast profile from the scattered field turns out to be, what we call, an ill-posed problem and computationally heavy. Although, at lower values of contrast, approximations permit the elimination of ill-posedness and prior knowledge help with handling the non-convex nature of the problem, the computational complexity keep rising with the resolution of the profile.

My work was an attempt to address the latter problem. I developed an adaptive resolution based iterative algorithm where at each iteration, previously reconstructed contrast profile is used to effectively reduce the resolution into categorised resolution; the reconstruction is then carried out on the categorised resolution. This algorithm does not only reduce the computational time but also increases the precision of the reconstructed profile. 
