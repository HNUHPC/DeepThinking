---
title: 'HSMU-SpGEMM: Achieving High Shared Memory Utilization for Parallel Sparse General Matrix-Matrix Multiplication on Modern GPUs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Wu, Min
  - Luo, Huizhang
  - Li, Fenfang
  - Zhang, Yiran
  - Tang, Zhuo
  - Li, Kenli
  - Zhang, Jeff
  - Liu, Chubo
  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  

date: '2025-03-01T00:00:00Z'
doi: '10.1109/HPCA61900.2025.00109'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2025 IEEE International Symposium on High Performance Computer Architecture (HPCA)*
publication_short: In *HPCA 2025*

abstract: Sparse general matrix-matrix multiplication (SpGEMM) is a core primitive for numerous scientific applications. Traditional hash-based approaches fail to strike a balance between reducing hash collisions and efficiently utilizing fast shared memory, which significantly undermines the performance of executing SpGEMM on GPUs. To address this issue, this paper introduces a novel accumulator design that achieves high shared memory utilization on modern GPUs. For the proposed high shared memory utilization algorithm, i.e., HSMU-SpGEMM1, we further optimize different symbolic stages. Our evaluations with four state-of-the-art hash-based SpGEMM libraries (Nsparse, spECK, OpSparse, and NVIDIA’s cuSPARSE) on three NVIDIA GPUs (Ampere, Ada Lovelace, Turing) demonstrate significant performance benefits from HSMU-SpGEMM.1HSMU-SpGEMM is available at https://github.com/wuminqaq/HSMUSpGEMM

# Summary. An optional shortened abstract.
summary: 

tags: ['Memory management', 'Graphics processing units', 'Libraries', 'Sparse matrices', 'SpGEMM', 'Sparse matrix', 'GPU', 'High shared memory utilization', 'Novel accumulator']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10946796'
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
