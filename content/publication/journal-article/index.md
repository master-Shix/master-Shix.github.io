---
title: "An example journal article"
authors:
- Yufei Shi
- Beijia Lu
- Jia-Wei Liu
- Ming Li
- Mike Zheng Shou

#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2023-12-03T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Medical Imaging"
publication_short: "TMI"

abstract: Colonoscopy reconstruction is pivotal for diagnosing colorectal cancer. However, accurate long-sequence colonoscopy reconstruction faces three major challenges (1) dissimilarity among segments of the colon due to its meandering and convoluted shape; (2) co-existence of simple and intricately folded geometry structures; (3) sparse viewpoints due to constrained camera trajectories. To tackle these challenges, we introduce a new reconstruction framework based on neural radiance field (NeRF), named ColonNeRF, which leverages neural rendering for novel view synthesis of long-sequence colonoscopy. Specifically, to reconstruct the entire colon in a piecewise manner, our ColonNeRF introduces a region division and integration module, effectively reducing shape dissimilarity and ensuring geometric consistency in each segment. To learn both the simple and complex geometry in a unified framework, our ColonNeRF incorporates a multi-level fusion module that progressively models the colon regions from easy to hard. Additionally, to overcome the challenges from sparse views, we devise a DensiNet module for densifying camera poses under the guidance of semantic consistency. We conduct extensive experiments on both synthetic and real-world datasets to evaluate our ColonNeRF. Quantitatively, our ColonNeRF outperforms existing methods on two benchmarks over four evaluation metrics. Notably, our LPIPS-ALEX scores exhibit a substantial increase of about 67%-85% on the SimCol-to-3D dataset. Qualitatively, our reconstruction visualizations show much clearer textures and more accurate geometric details. These sufficiently demonstrate our superior performance over the state-of-the-art methods.

# Summary. An optional shortened abstract.
summary: We propose a neural rendering framework for reconstructing the entire colon.

tags:
- 3D Reconstruction
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2312.02015
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
