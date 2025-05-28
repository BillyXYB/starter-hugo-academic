---
title: Differentiable Rendering for Local Parameters
summary: Course Project for CMU Physical-based Rendering
tags:
  - Graphics
date: '2024-06-10T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Visulization for Local Parameters Updates
  focal_point: Smart

links:
  # - icon: twitter
    # icon_pack: fab
    # name: Follow
    # url: https://twitter.com/georgecushen

url_code: ''
url_pdf: files/pbr.pdf
url_slides: 'https://docs.google.com/presentation/d/18Mmx02HhhXEvPLoBgCLkMehGDr4CD8i8wTJQStP3XqU/edit?usp=sharing'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Physic-based rendering typically refers to the process that outputs an im-
age given the known properties in the scene, such as object location, surface
shape, material property lighting condition, etc. However, the assumption
that all information about the scene is known is not always valid, which
gives rise to the field of inverse rendering that infers the scene attributes
from image observations. Differentiable Rendering is one of the methods that
can achieve such an objective by utilizing gradients of the scene parameters
and optimizing them. In this project, a differentiable rendering framework
based on DIRT is implemented, with the capabilities of optimizing local
parameters such as BRDF and lighting properties. Support of more advanced
optimizers such as Adam is also included. Finally, gradient certification
via numerical differentiation (finite difference) is also included.
