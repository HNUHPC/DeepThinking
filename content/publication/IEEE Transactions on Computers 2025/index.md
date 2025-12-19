---
title: 'AEIS: A New Energy Efficiency Improvement Scheme for MLC STT-MRAM'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Dong Yin
  - Huizhang Luo
  - Yan Ding
  - Chubo Liu
  - Wenchao Zhao
  - Kenli Li
  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  

date: '2025-10-24T00:00:00Z'
doi: '10.1109/TC.2025.3625152'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Computers (Volume 75, Issue 1, January 2026)*
publication_short: In *IEEE TC 2026*

abstract: Spin Transfer Torque-Magnetic Random Access Memory (STT-MRAM), as a new non-volatile memory technology with lower leakage power and higher density, is widely considered to be a new generation of memory technology that may replace SRAM in the cache. STT-MRAM is divided into Single-Level Cell (SLC) STT-MRAM and Multi-Level Cell (MLC) STT-MRAM. Compared with SLC STT-MRAM, MLC STT-MRAM has further improved its storage density. However, MLC STT-MRAM has a high write energy consumption and write latency due to its unique two-step state transitions (TTs) issue. State-of-the-art approaches mitigate this issue by eliminating TTs with expansion coding methods. Unfortunately, they focus more on eliminating TTs and have limited improvement in reducing energy consumption. To this end, we propose a new scheme, AEIS, which further reduces energy consumption while eliminating TTs. Our work begins with exploring the general rules of [Math Processing Error]-based expansion coding methods that eliminate TTs. Based on the discovered rules, the minimum energy coding method is found. To further improve energy efficiency, we segment the cache lines according to the data pattern. We only apply the expansion coding to those flipping segments to reduce the expansion coding overhead. The evaluation results show that AEIS can eliminate TTs in MLC STT-MRAM, reduce energy consumption by 28.5%, and increase the lifetime by 24.8%, while the total number of bits used for the cache only increases by 5.7%.

# Summary. An optional shortened abstract.
summary: 

tags: ['Encoding', 'Energy consumption', 'Codes', 'Magnetic tunneling', 'Random access memory', 'Energy efficiency', 'Writing', 'Magnetic domains', 'Resistance', 'Nonvolatile memory', 'MLC STT-MRAM', 'energy consumption', 'two-step state transitions']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/11216148'
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
