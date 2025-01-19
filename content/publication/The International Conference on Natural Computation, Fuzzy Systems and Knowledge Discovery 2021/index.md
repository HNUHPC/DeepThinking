---
title: 'Exploring Level-Wise Interpolation to Improve Lossy Compression Ratio for AMR Applications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Yida Li
  - Huizhang Luo
  - Chubo Liu
  - Kenli Li

  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''

  

date: '2021-07-24T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-07-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The International Conference on Natural Computation, Fuzzy Systems and Knowledge Discovery, Pages 259-266*
publication_short: In *ICNC-FSKD*

abstract: Adaptive Mesh Refinement (AMR) is widely adopted in High-Performance Computing (HPC) systems. However, none of existing AMR storage solutions has considered the high similarities among the adjacent AMR levels, which leads to a lower storage efficiency. In this paper, we propose level-wise data interpolation techniques to further reduce the storage of AMR applications. In particular, it generates finer level data based on coarser levels. Then, the differences (deltas) between the interpolated data and original data are stored to achieve a higher compression ratio for lossy compressors. We firstly use median absolute deviation and standard deviation to decide which interpolations are adopted. After that, we evaluate the effectiveness of level-wise interpolation with ZFP and SZ lossy compressors. The experimental results show that the compression ratio of deltas are improved up to 3*compared to directly compressing the finer level data.

# Summary. An optional shortened abstract.
summary: In *The International Conference on Natural Computation, Fuzzy Systems and Knowledge Discovery, Pages 259-266(ICNC-FSKD)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-89698-0_27'
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
