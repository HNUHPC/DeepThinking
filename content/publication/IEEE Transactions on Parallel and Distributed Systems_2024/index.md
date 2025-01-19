---
title: 'FastLoad: Speeding Up Data Loading of Both Sparse Matrix and Vector for SpMV on GPUs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jinyu Hu
  - Huizhang Luo
  - Hong Jiang
  - Guoqing Xiao
  - Kenli Li

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''

date: '2024-10-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-09T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Parallel and Distributed Systems (Volume 35, Issue 12, December 2024)*
publication_short: In *IEEE TPDS 2024*

abstract: Sparse Matrix-Vector Multiplication (SpMV) on GPUs has gained significant attention because of SpMV's importance in modern applications and the increasing computing power of GPUs in the last decade. Previous studies have emphasized the importance of data loading for the overall performance of SpMV and demonstrated the efficacy of coalesced memory access in enhancing data loading efficiency. However, existing approaches fall far short of reaching the full potential of data loading on modern GPUs. In this paper, we propose an efficient algorithm called FastLoad, that speeds up the loading of both sparse matrices and input vectors of SpMV on modern GPUs. Leveraging coalesced memory access, FastLoad achieves high loading efficiency and load balance by sorting both the columns of the sparse matrix and elements of the input vector based on the number of non-zero elements while organizing non-zero elements in blocks to avoid thread divergence. FastLoad takes the Compressed Sparse Column (CSC) format as an implementation case to prove the concept and gain insights. We conduct a comprehensive comparison of FastLoad with the CSC-based SpMV, cuSPARSE, CSR5, and TileSpMV, using the full SuiteSparse Matrix Collection as workload. The experimental results on RTX 3090 Ti demonstrate that our method outperforms the others in most matrices, with geometric speedup means over CSC-based, cuSPARSE, CSR5, and TileSpMV being 2.12×, 2.98×, 2.88×, and 1.22×, respectively.

# Summary. An optional shortened abstract.
summary: In *IEEE Transactions on Parallel and Distributed Systems (Volume 35, Issue 12, December 2024)(IEEE TPDS 2024)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ranger.uta.edu/~jiang/publication/Journals/2024/IEEE-TPDS(FastLoad-Jinyu%20Hu).pdf'
url_code: 'https://github.com/MinttHu/FastLoad'
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
