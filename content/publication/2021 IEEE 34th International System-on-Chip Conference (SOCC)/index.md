---
title: 'Total Variation Reduction for Lossless Compression of HPC Applications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Junqi Wang
  - Yida Li
  - Qing Liu
  - Huizhang Luo
  - Kenli Li

  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''

  

date: '2021-09-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-09-14T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE 34th International System-on-Chip Conference (SOCC)*
publication_short: In *SOCC 2021*

abstract: With the growing size of high-performance computing (HPC) applications, a major challenge that domain scientists are facing is how to efficiently store and analyze the vast volume of output data. Compression can reduce the amount of data that needs to be transferred and stored. However, most of the large datasets are of floating-point format, which exhibit high entropy. As a result, existing lossless compressors usually achieve a modest reduction ratio of less than 2X. To address this problem, we propose a total variation reduction method to improve the compression ratio of lossless compressors. In particular, we first try to exploit space-filling curve (SFC), a well-known technique to preserve data locality for a multi-dimensional HPC dataset. We show and explain why a raw SFC, such as Hilbert curve and Z-order curve, cannot improve the compression ratio. Then, we explore the opportunity and theoretical feasibility of the proposed total variation reduction based algorithm. The experiment results show the effectiveness of the proposed method. The compression ratios are improved by 20.6% for FPZIP, and 18.4% for FPC, on average.

# Summary. An optional shortened abstract.
summary: In *2021 IEEE 34th International System-on-Chip Conference (SOCC)(SOCC 2021)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9739467'
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
