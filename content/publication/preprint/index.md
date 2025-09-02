---
title: "Solving the Job Shop Scheduling Problem with Graph Neural Networks: A Customizable Reinforcement Learning Environment"
authors:
- admin
- Carlos Quesada González

date: "2025-06-10T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["Bachelor's thesis"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "The job shop scheduling problem is an NP-hard combinatorial optimization problem relevant to manufacturing and timetabling. Traditional approaches use priority dispatching rules based on simple heuristics. Recent work has attempted to replace these with deep learning models, particularly graph neural networks (GNNs), that learn to assign priorities from data. However, training such models requires customizing numerous factors: graph representation, node features, action space, and reward functions. The lack of modular libraries for experimentation makes this research time-consuming. This work introduces JobShopLib, a modular library that allows customizing these factors and creating new components with its reinforcement learning environment. We trained several dispatchers through imitation learning to demonstrate the environment's utility. One model outperformed various graph-based dispatchers using only individual operation features, highlighting the importance of feature customization. Our GNN model achieved near state-of-the-art results on large-scale problems. These results suggest significant room for improvement in developing such models. JobShopLib provides the necessary tools for future experimentation."

# Summary. An optional shortened abstract.
summary: Created JobShopLib, an open-source library that enables researchers to create, visualise, and solve the JSSP using customisable RL environments.

tags:
- Graph Neural Networks
- Reinforcement Learning

featured: true

# hugoblox:
#   ids:
#     arxiv: 2506.13781

links:
- type: preprint
  provider: arxiv
  id: 2506.13781
- type: code
  url: https://github.com/Pabloo22/gnn_scheduler
- type: slides
  url: https://docs.google.com/presentation/d/1XrR6k7o8fzt2QBVIoQDgQRMPp4axG7I5Y2KsoU988_c/edit?usp=sharing
# - type: dataset
#   url: "#"
# - type: poster
#   url: "#"
# - type: source
#   url: "#"
# - type: video
#   url: https://youtube.com
# - type: custom
#   label: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "High level overview of JobShopLib's RL environment design."
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

With my bachelor’s thesis, I have explored the field of deep reinforcement learning and graph neural networks. Inspired by AlphaZero’s success in combinatorial games like Go and chess, I was interested in using RL to solve combinatorial optimisation problems. I found the job shop scheduling problem (JSSP) the perfect one. It had received significantly less attention than others, facilitating more impactful and original contributions. For instance, in tackling the JSSP, I realised a lack of tools for efficient experimentation. This led me to create [JobShopLib](https://github.com/Pabloo22/job_shop_lib), an open-source library that enables researchers to create, visualise, and solve the JSSP using customisable RL environments. Although this work extended beyond the typical scope of a bachelor’s thesis, I was committed to pursuing a challenging and original project, even if it meant a longer completion time.

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
