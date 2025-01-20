---
title: 'ZFP-X: Efficient Embedded Coding for Accelerating Lossy Floating Point Compression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Bing Lu
  - Yida Li
  - Junqi Wang
  - Huizhang Luo
  - Kenli Li

  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''

  

date: '2023-05-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE International Parallel and Distributed Processing Symposium (IPDPS)*
publication_short: In *IPDPS 2023*

abstract: Today’s scientific simulations are confronting seriously limited I/O bandwidth, network bandwidth, and storage capacity because of immense volumes of data generated in high-performance computing systems. Data compression has emerged as one of the most effective approaches to resolve the issue of the exponential increase of scientific data. However, existing state-of-the-art compressors also are confronting the issue of low throughput, especially under the trend of growing disparities between the compute and I/O rates. Among them, embedded coding is widely applied, which contributes to the dominant running time for the corresponding compressors. In this work, we propose a new kind of embedded coding algorithm, and apply it as the backend embedded coding of ZFP, one of the most successful lossy compressors. Our embedded coding algorithm uses bit groups instead of bit planes to store the compressed data, avoiding the time overhead of generating bit planes and group tests of bit planes, which significantly reduces the running time of ZFP. Our embedded coding algorithm can also accelerate the decompression of ZFP, because the costly procedures of the reverse of group tests and reconstructing bit planes are also avoided. Moreover, we provide theoretical proof that the proposed coding algorithm has the same compression ratio as the baseline ZFP. Experiments with four representative real-world scientific simulation datasets show that the compression and decompression throughput of our solution is up to 2.5× (2.1× on average), and up to 2.1× (1.5× on average) as those of ZFP, respectively.

# Summary. An optional shortened abstract.
summary: In *2023 IEEE International Parallel and Distributed Processing Symposium (IPDPS)(IPDPS 2023)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10177402'
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
