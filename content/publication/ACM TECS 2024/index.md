---
title: 'AMP: Total Variation Reduction for Lossless Compression via Approximate Median-based Preconditioning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Fenfang Li
  - Huizhang Luo
  - Junqi Wang
  - Yida Li
  - Zhuo Tang
  - Kenli Li
  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  

date: '2024-09-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM Transactions on Embedded Computing Systems, Volume 23, Issue 6, No. 86, Pages 1 - 22*
publication_short: In *ACM TECS 2024*

abstract: With the increasing scale of cloud computing applications of next-generation embedded systems, a major challenge that domain scientists are facing is how to efficiently store and analyze the vast volume of output data. Compression can reduce the amount of data that needs to be transferred and stored. However, most of the large datasets are in floating-point format, which exhibits high entropy. As a result, existing lossless compressors cannot provide enough performance for such applications. To address this problem, we propose a total variation reduction method for improving the compression ratio of lossless compressors (namely, FPC+ and FPZIP+), which employs a median-based hyperplane to precondition the data. In particular, we first try to exploit the space-filling curve (SFC), a well-known technique to preserve data locality for a multi-dimensional dataset. We show and explain why a raw SFC, such as Hilbert and Z-order curves, cannot improve the compression ratio. Then, we explore the opportunity and theoretical feasibility of the proposed total variation reduction-based algorithm. The experiment results show the effectiveness of the proposed method. The compression ratios are improved up to 48.2% (20.6% on average) for FPZIP and 42.4% (18.4% on average) for FPC. Moreover, through observing the time composition of the proposed method, it is found that the median finding holds a high percentage of the execution time. Hence, we further introduce an approximate median finding algorithm, providing a linear-time overhead reduction scheme. The experiment results clearly demonstrate that this algorithm reduces execution time by an average of 56.7% and 40.7% compared to FPC+ and FPZIP+, respectively.

# Summary. An optional shortened abstract.
summary: In *ACM Transactions on Embedded Computing Systems, Volume 23, Issue 6, No. 86, Pages 1 - 22(ACM TECS 2024)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3605359#core-cited-by'
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
