---
title: 'cuFastTuckerPlus: A Stochastic Parallel Sparse FastTucker Decomposition Using GPU Tensor Cores'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Zixuan Li
  - Mingxing Duan
  - Huizhang Luo
  - Wangdong Yang
  - Kenli Li
  - Keqin Li
  
  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''


date: '2024-04-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *arXiv preprint arXiv:2404.10087*
publication_short: In *arXiv 2404.10087*

abstract: Sparse tensors are prevalent in real-world applications, often characterized by their large-scale, high-order, and high-dimensional nature. Directly handling raw tensors is impractical due to the significant memory and computational overhead involved. The current mainstream approach involves compressing or decomposing the original tensor. One popular tensor decomposition algorithm is the Tucker decomposition. However, existing state-of-the-art algorithms for large-scale Tucker decomposition typically relax the original optimization problem into multiple convex optimization problems to ensure polynomial convergence. Unfortunately, these algorithms tend to converge slowly. In contrast, tensor decomposition exhibits a simple optimization landscape, making local search algorithms capable of converging to a global (approximate) optimum much faster. In this paper, we propose the FastTuckerPlus algorithm, which decomposes the original optimization problem into two non-convex optimization problems and solves them alternately using the Stochastic Gradient Descent method. Furthermore, we introduce cuFastTuckerPlus, a fine-grained parallel algorithm designed for GPU platforms, leveraging the performance of tensor cores. This algorithm minimizes memory access overhead and computational costs, surpassing the state-of-the-art algorithms. Our experimental results demonstrate that our method achieves a speedup of 3X to 5X compared to state-of-the-art algorithms.

# Summary. An optional shortened abstract.
summary: In *arXiv preprint arXiv:2404.10087(arXiv 2404.10087)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2404.10087'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''



# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
