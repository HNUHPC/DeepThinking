---
title: 'A Data-driven Approach to Harvesting Latent Reduced Models to Precondition Lossy Compression for Scientific Data'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Huizhang Luo
  - Junqi Wang
  - Zhenlu Qin
  - Dan Huang
  - Qing Liu
  - Mengchu Zhou

  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  

date: '2022-12-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-1T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Big Data (Volume 9, Issue 3, 01 June 2023)*
publication_short: In *IEEE TBD 2023*

abstract: In this paper, we propose and evaluate the idea that data need to be preconditioned prior to compression, such that they can better match the design philosophies of lossy compressors for HPC scientific data. In particular, we aim to identify a reduced model that can be utilized to transform the original data into a more compressible form. We begin with two PDE applications as a proof of concept, in which we demonstrate that a reduced model can indeed reside in the full model output, and can be utilized to improve compression ratios. A mathematical proof is also presented to show how the compression ratio is improved by the reduced model. We further explore more general dimension reduction techniques to extract the reduced model, including principal component analysis, singular value decomposition, and discrete wavelet transform. After preconditioning, the reduced model in conjunction with difference between the reduced model and full model is stored, which results in higher compression ratios. We evaluate the reduced models on ten scientific datasets, and the results show the effectiveness of our approaches. Given that there is no single method that consistently achieves the best performance, we further propose a selection strategy that guides users to select the best reduced model prior to data reduction.

# Summary. An optional shortened abstract.
summary: In *IEEE Transactions on Big Data (Volume 9, Issue 3, 01 June 2023)(IEEE TBD 2023)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9968123'
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
