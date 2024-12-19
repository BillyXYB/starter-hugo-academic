---
title: Distillation-free Text-to-3D via Guided Multi-view Diffusion
summary: Resarch Project at CMU
tags:
  - Computer Vision
date: '2024-06-10T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Joint Sample with 2D and Multi-view Diffusion
  focal_point: Smart

links:
  # - icon: twitter
    # icon_pack: fab
    # name: Follow
    # url: https://twitter.com/georgecushen

url_code: ''
url_pdf: files/lr3d.pdf
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

We propose a method that can generate multi-view images of objects from text prompts with high fidelity. There has been considerable progress in the field of 3D generation thanks to large synthetic 3D datasets such as Objaverse and the advancement of diffusion models. However, the generated multi-view images or 3D assets often suffer from simplistic textures, possibly because the textures of the objects in synthetic datasets are not as sophisticated as in-
the-wild objects. This limits the practical usage of such models. On the other hand, text-to-2D methods are capable of generating images with high fidelity, partly due to the significantly larger and richer dataset they are trained on. We want to show that we can generate multi-view images with sophisticated textures by actively leveraging such a text-to-2D diffusion model in conjunction with a text-to-multi-view model while performing DDIM sampling.
