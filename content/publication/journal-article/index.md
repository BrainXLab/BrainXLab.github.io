---
title: "A GPU-based computational framework that bridges neuron simulation and artificial intelligence"
authors:
- Yichen Zhang
- Gan He
- Lei Ma
- Xiaofei Liu
- J. J. Johannes Hjorth
- Alexander Kozlov
- Yutao He
- Shenjian Zhang
- Jeanette Hellgren Kotaleski
- Yonghong Tian
- Sten Grillner
- Kai Du
- Tiejun Huang
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-09-18T00:00:00Z"
doi: "10.1038/s41467-023-41553-7"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Nature Communications*, 14, Article number: 5798 (2023)"
publication_short: "Nat. Commun."


abstract: Biophysically detailed multi-compartment models are powerful tools to explore computational principles of the brain and also serve as a theoretical framework to generate algorithms for artificial intelligence (AI) systems. However, the expensive computational cost severely limits the applications in both the neuroscience and AI fields. The major bottleneck during simulating detailed compartment models is the ability of a simulator to solve large systems of linear equations. Here, we present a novel Dendritic Hierarchical Scheduling (DHS) method to markedly accelerate such a process. We theoretically prove that the DHS implementation is computationally optimal and accurate. This GPU-based method performs with 2-3 orders of magnitude higher speed than that of the classic serial Hines method in the conventional CPU platform. We build a DeepDendrite framework, which integrates the DHS method and the GPU computing engine of the NEURON simulator and demonstrate applications of DeepDendrite in neuroscience tasks. We investigate how spatial patterns of spine inputs affect neuronal excitability in a detailed human pyramidal neuron model with 25,000 spines. Furthermore, we provide a brief discussion on the potential of DeepDendrite for AI, specifically highlighting its ability to enable the efficient training of biophysically detailed models in typical image classification tasks.

# Summary. An optional shortened abstract.
summary:  A GPU-based framework enabling fast and accurate simulation of biophysical neuron models, with potential for both neuroscience and AI.

tags:
- Neural Simulation
- Artificial Intelligence
- GPU Computing
- DeepDendrite
- NEURON
- Dendritic Processing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.nature.com/articles/s41467-023-41553-7.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

image:
  filename: featured.webp  # 指向你当前文件夹下的图片
  caption: ""
  focal_point: center
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
slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
