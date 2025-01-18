---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        DeepThinking Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        <div style = "text-align: justify; font-size: 18px;">
          The <strong>DeepThinking Lab</strong> is dedicated to conducting cutting-edge research in the fields of high-performance computing and computer architecture. Our research scope also extends to areas such as Data Compression, and Parallel Computing.
        <br>
          The name "DeepThinking" represents our pursuit of in-depth exploration and innovation in these research areas. It implies that we are committed to profound thinking and analysis, constantly striving to break through the existing boundaries and discover new solutions.
        <br>
          In the domain of high-performance computing, we focus on developing advanced algorithms and techniques to improve the computational speed and efficiency of supercomputers. In the area of Data Compression, we concentrate on devising strategies to cut down data storage space and transmission bandwidth without sacrificing data integrity. In the field of Parallel Computing, we explore parallel algorithms and programming models to fully utilize multi-core processors and distributed computing platforms.
        <br>
          Through continuous efforts in these research directions, the DeepThinking Lab aspires to contribute meaningfully to the development of computer science and related technologies.
        </div>
        
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
