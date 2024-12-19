---
title: Utilizing 2D Diffusion Model for Text Commanded NeRF Editing
summary: HKUST Final Year Thesis
tags:
  - Computer Vision
date: '2023-06-10T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Example of NeRF Editing
  focal_point: Smart

links:
  # - icon: twitter
    # icon_pack: fab
    # name: Follow
    # url: https://twitter.com/georgecushen

url_code: ''
url_pdf: files/FYT_Final_Report_Yanbo_Xu.pdf
url_slides: 'https://docs.google.com/presentation/d/1VGU7NENw4Zs9-df7nJNt4LU0wSe7lo8cXjykKaIb2rY/edit?usp=sharing'
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The tasks of image manipulation have always been important. Recently, with the advancements in AI-based image manipulation in the field of computer vision, many methods for editing in the 2D images domain have been proposed and proven effective. It is natural to extend the manipulation to the 3D domain, whose success could bring improvement in the multimedia industry and even areas such as VR, Gaming, etc.
This critical task is feasible with the success of diffusion models (DMs) and text models, generating or editing an image with only textual input is possible. DMs could also be used to generate 3D models conditioned on text input, which shows the possibility of guiding 3D generation using 2D models.