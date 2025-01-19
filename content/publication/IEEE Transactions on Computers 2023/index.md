---
title: 'LAMP: Improving compression ratio for AMR applications via level associated mapping-based preconditioning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Yida Li
  - Huizhang Luo
  - Fenfang Li
  - Junqi Wang
  - Kenli Li

  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''

  

date: '2024-07-20T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-20T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Computers (Volume 72, Issue 12, December 2023)*
publication_short: In *IEEE TC 2023*

abstract: Data compression can efficiently reduce the memory and persistence storage cost, which is highly desirable in modern computing systems, such as enterprise, cloud, and High-Performance Computing (HPC) environments. However, the main challenges of existing data compressors are the insufficient compression ratio and low throughput. This paper focuses on improving the compression ratio of state-of-the-art lossy compression algorithms from the view of applications. Besides, we also use the characteristics of the applications to reduce the runtime overhead. To this end, we explore the idea with Adaptive Mesh Refinement (AMR), which is widely adopted as a computational technique to reduce the amount of computation and memory required in scientific simulations. We propose Level Associated Mapping-based Preconditioning (LAMP) to improve the storage efficiency of AMR applications. The main idea is twofold. First, we utilize the high similarities among the adjacent AMR levels to precondition the data prior to compression. Second, AMR has a unique characteristic of grid structures. We utilize grid structures to rebuild a level associated mapping table, which significantly reduces the runtime overhead of LAMP. Thanks to the optimization techniques of General Matrix Multiplication (GEMM), we further accelerate the process of rebuilding AMR hierarchy for LAMP. Besides, we also block multiple adjacent coordinates within a box and further improve cache locality. The experimental results show that the compression ratios of LAMP are improved up to 63.8% compared to directly compressing the data.

# Summary. An optional shortened abstract.
summary: In *IEEE Transactions on Computers (Volume 72, Issue 12, December 2023)(IEEE TC 2023)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10189350'
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
