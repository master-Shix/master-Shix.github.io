---
title: ColonNeRF Neural Radiance Fields for High-Fidelity Long-Sequence Colonoscopy Reconstruction
summary: Colonoscopy reconstruction is pivotal for diagnosing colorectal cancer. However, accurate long-sequence colonoscopy reconstruction faces three major challenges: (1) dissimilarity among segments of the colon due to its meandering and convoluted shape; (2) co-existence of simple and intricately folded geometry structures; (3) sparse viewpoints due to constrained camera trajectories.

To tackle these challenges, we introduce a new reconstruction framework based on neural radiance field (NeRF), named ColonNeRF, which leverages neural rendering for novel view synthesis of long-sequence colonoscopy. Specifically, to reconstruct the entire colon in a piecewise manner, our ColonNeRF introduces a region division and integration module, effectively reducing shape dissimilarity and ensuring geometric consistency in each segment. To learn both the simple and complex geometry in a unified framework, our ColonNeRF incorporates a multi-level fusion module that progressively models the colon regions from easy to hard. Additionally, to overcome the challenges from sparse views, we devise a DensiNet module for densifying camera poses under the guidance of semantic consistency.

We conduct extensive experiments on both synthetic and real-world datasets to evaluate our ColonNeRF. Quantitatively, our ColonNeRF outperforms existing methods on two benchmarks over four evaluation metrics. Notably, our LPIPS-ALEX scores exhibit a substantial increase of about 67%-85% on the SimCol-to-3D dataset. Qualitatively, our reconstruction visualizations show much clearer textures and more accurate geometric details. These sufficiently demonstrate our superior performance over the state-of-the-art methods.

tags:
  - Deep Learning
#date: '2016-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: 'https://showlab.github.io/ColonNeRF/'

image:
  caption: The Overview of Model
  focal_point: Smart

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
#url_code: ''
url_pdf: '/https://arxiv.org/pdf/2312.02015.pdf'
#url_slides: ''
#url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
