---
title: 'STREAM: Spatiotemporal Similarity-based Efficient Approximate Median with Tunable Granularity'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Fenfang Li
  - Huizhang Luo
  - Weichen Liu
  - Anthony Theodore Chronopoulos
  - Kenli Li
  - Chubo Liu
  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  

date: '2025-06-22T00:00:00Z'
doi: '10.1109/DAC63849.2025.11133038'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2025 62nd ACM/IEEE Design Automation Conference (DAC)*
publication_short: In *DAC 2025*

abstract: The median (MED) is a crucial statistic for measuring the central tendency. However, exact MED computation remains costly, with even state-of-the-art (SOTA) algorithms failing to meet (near) real-time processing demands. While approximate MED algorithm has arisen as a promising candidate, existing approaches ignore the potential opportunity of spatiotemporal similarity within the application and fail to provide applicationspecific trade-offs between execution time and accuracy. Our goal is to design an enhanced approximate MED algorithm STREAM, which is capable of exploiting the spatiotemporal similarity to achieve bucket reuse and establish a tunable-grained bucket mechanism to meet the accuracy of application-specific requirements. Experimental results show that while maintaining nearly identical accuracy, STREAM outperforms the SOTA approximate methods DDSketch (up to 10×4.7× on average) and KLL (up to 71.2×10.1× on average).

# Summary. An optional shortened abstract.
summary: 

tags: ['Accuracy', 'Design automation', 'Approximate computing', 'Approximation algorithms', 'Real-time systems', 'Spatiotemporal phenomena', 'approximate computing', 'approximate median', 'spatiotemporal similarity', 'synopsis']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/11133038'
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
