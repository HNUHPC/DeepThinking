---
title: 'zeroTT: A Two-Step State Transition Avoidance Scheme for MLC STT-RAM'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Dong Yin
  - Huizhang Luo
  - Jeff Zhang
  - Mingxing Duan
  - Wangdong Yang
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
  

date: '2024-06-23T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *DAC '24 Proceedings of the 61st ACM/IEEE Design Automation Conference, Article No. 210, Pages 1 - 6*
publication_short: In *DAC 2024*

abstract: Compared with conventional SRAM, Spin-Transfer Torque Random Access Memory(STT-RAM) is expected to play a crucial role in future memory technologies with the increasing demands for higher storage density and lower power consumption for modern embedded systems. Moreover, Multi-Level Cell (MLC) STT-RAM outperforms Single-Level Cell (SLC) STT-RAM since it has higher bit density. However, MLC STT-RAM suffers from write performance due to the two-step state transitions (TTs) in memory cells' soft domain. State-of-the-art approaches mitigate this issue by reducing TTs with efficient data coding. Unfortunately, none of the existing works can fully eliminate the TTs. In this work, zeroTT, an optimal (3, 4)-based expansion coding method that eliminates TTs for MLC STT-RAM. The design of ZeroTT considers space overhead and coding complexity, and our experimental results demonstrate that zeroTT can completely avoid TTs, leading to a more efficient MLC STT-RAM memory in terms of access latency, energy consumption, and device lifetime.

# Summary. An optional shortened abstract.
summary: In *DAC '24 Proceedings of the 61st ACM/IEEE Design Automation Conference, Article No. 210, Pages 1 - 6(DAC 2024)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3649329.3658240'
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
