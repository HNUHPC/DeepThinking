---
title: 'zMesh: Exploring Application Characteristics to Improve Lossy Compression Ratio for Adaptive Mesh Refinement'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Huizhang Luo
  - Junqi Wang
  - Qing Liu
  - Jieyang Chen
  - Scott Klasky
  - Norbert Podhorszki

  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  

date: '2021-05-17T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-05-17T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE International Parallel and Distributed Processing Symposium (IPDPS)*
publication_short: In *IPDPS 2021*

abstract: Scientific simulations on high-performance computing systems produce vast amounts of data that need to be stored and analyzed efficiently. Lossy compression significantly reduces the data volume by trading accuracy for performance. Despite the recent success of lossy compression, such as ZFP and SZ, the compression performance is still far from being able to keep up with the exponential growth of data. This paper aims to further take advantage of application characteristics, an area that is often under-explored, to improve the compression ratios of adaptive mesh refinement (AMR) - a widely used numerical solver that allows for an improved resolution in limited regions. We propose a level reordering technique zMesh to reduce the storage footprint of AMR applications. In particular, we group the data points that are mapped to the same or adjacent geometric coordinates such that the dataset is smoother and more compressible. Unlike the prior work where the compression performance is affected by the overhead of metadata, this work re-generates restore recipe using a chained tree structure, thus involving no extra storage overhead for compressed data, which substantially improves the compression ratios. The results demonstrate that zMesh can improve the smoothness of data by 67.9% and 71.3% for Z-ordering and Hilbert, respectively. Overall, zMesh improves the compression ratios by up to 16.5% and 133.7% for ZFP and SZ, respectively. Despite that zMesh involves additional compute overhead for tree and restore recipe construction, we show that the cost can be amortized as the number of quantities to be compressed increases.

# Summary. An optional shortened abstract.
summary: In *2021 IEEE International Parallel and Distributed Processing Symposium (IPDPS)(IPDPS 2021)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://par.nsf.gov/servlets/purl/10252632'
url_code: 'https://github.com/HNUHPC/AMR'
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
