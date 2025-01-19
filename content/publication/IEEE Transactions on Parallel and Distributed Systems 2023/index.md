---
title: 'COFFEE: Cross-Layer Optimization for Fast and Efficient Executions of Sinkhorn-Knopp Algorithm on HPC Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Chengyu Sun
  - Huizhang Luo
  - Hong Jiang
  - Jeff Zhang
  - Kenli L

  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''

  

date: '2023-05-19T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Parallel and Distributed Systems (Volume 34, Issue 7, July 2023)*
publication_short: In *IEEE TPDS 2023*

abstract: In this paper, we present COFFEE, cross-layer optimization for fast and efficient executions of the Sinkhorn-Knopp (SK) algorithm on HPC systems with clusters of compute nodes by exploring some architectural features of the system. By analyzing the performance of a typical implementation of the SK algorithm on such a system, a huge performance gap is observed between the row rescaling and column rescaling of the algorithm, where the latter requires much more time than the former. We also found that the costly MPI communication of the column rescaling seriously hinders the exploitation of parallelism. By observing and leveraging unique architectural characteristics across different system optimizations, such as column rescaling redesign, data blocking, micro-kernel design, enhanced intra-node and inter-node communication in MPI, etc., COFFEE is able to explore cross-layer optimization opportunities that enable fast and efficient execution of the SK algorithm. Our experimental results show that COFFEE provides up to 7.5X with an average of 2.0X performance improvement over the typical implementation on a single node, and up to 2.9X with an average of 1.6X performance improvement over the state-of-the-art MPI Allreduce algorithms on Tianhe-1 supercomputer.

# Summary. An optional shortened abstract.
summary: In *IEEE Transactions on Parallel and Distributed Systems (Volume 34, Issue 7, July 2023)(IEEE TPDS 2023)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10129913'
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
