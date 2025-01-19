---
title: 'MF-Net: A Multimodal Fusion Model for Fast Multi-object Tracking'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.

authors:
  - Shirui Tian
  - Mingxing Duan
  - Jiayan Deng
  - Huizhang Luo
  - Yikun Hu

  
# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - ''

  

date: '2024-03-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Vehicular Technology (Volume 73, Issue 8, August 2024)*
publication_short: In *IEEE TVT 2024*

abstract: In the realm of multimodal multi-object tracking (MOT) applications based on point clouds and images, the current research predominantly focuses on enhancing tracking accuracy, often neglecting the issue of computational efficiency. Consequently, these models often struggle to exhibit optimal tracking capabilities in scenarios demanding high real-time performance. To address these challenges, this paper introduces a fast multi-object tracking model based on multimodal fusion (MF-Net). The model is divided into three primary modules object detection, multimodal fusion, and trajectory matching. Firstly, a 2D detector is used to identify objects in the image and compute their posterior estimate, and a 3D classification network extracts the foreground points of the object from the point cloud. Subsequently, a perspective projection module is then designed to determine the transformation matrix and the minimum number of vertex pairs that map the coordinates of the foreground points onto a 2D plane. Based on the model, a Planar Gaussian Function (PGF) model was constructed to fit small and hard objects that were missed in the image according to the foreground points, thus compensating for the limitations of 2D detectors and ensuring accuracy while reducing training time. Finally, the merged object performs trajectory matching. The performance of MF-Net has been verified through experiments in plenty conducted on publicly available KITTI and nuScenes datasets. In comparison to existing competitive models, our algorithm demonstrates a substantial enhancement in both detection and tracking performance, achieving satisfactory accuracy but showcasing superior real-time efficiency.

# Summary. An optional shortened abstract.
summary: In *IEEE Transactions on Vehicular Technology (Volume 73, Issue 8, August 2024)(IEEE TVT 2024)*

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10465629'
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
