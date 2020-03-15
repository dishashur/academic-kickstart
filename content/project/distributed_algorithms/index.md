---
title: Distributed graph algorithms
summary: Smoothed analysis of leader election problem in graphs in a distributed setting
#tags:
#- Deep Learning

date: "2019-02-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
#external_link: ""

image:
  caption: Objective function with two sample points
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

In problems similar to SLAM, guessing the location of the object become as indispensable as reconstructing the field around it. We believe that reconstruction of the field by estimating the locations of the sensors, instead of assuming them as is currently done, would give a much higher precision of reconstruction with much lesser samples. Fourier transforms, as a method of reconstruction, can be cast into an optimization problem that, if solved, can estimate the correct locations. The challenge arises due to the non-convex nature of the thus formed optimization problem. Meta-heuristic techniques such a particle swarm, although effective, are difficult to analyze.

On the other hand, a convex majorizing function to the original optimization function would make the job of analyzing easy and ideally, would give similar results. This is the current direction of the project; to verify the error margin for a given approximation of the objective function. 

Moreover, the technique of Finite Rate of Innovation in signals paints a completely different picture as it uses properties of DFT and z-transform to achieve reconstruction by retrieving the time instances of the samples. My current work involves extending this idea for reconstructing the spatial instance of the samples. Work is still going on in this regard.
