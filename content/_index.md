---
# Leave the homepage title empty to use the site title
title: 
date: 2024-01-10
type: landing

#<!--Custom spacing-->
#<div class="mb-4"></div>
#cta:
 #label: About
 #url: about

sections:
  - block: hero
    content:
      title: #|
        #-1 Lab
      image:
        filename: welcome.png
      text: |
        <br>
        
        Welcome! Our group uses an interdisciplinary approach that combines physics, mathematics, data, and network science to provide insights into the complexity of **social systems and behaviors**, particularly in the areas of behavioral contagion, discovery processes, and group dynamics.

        We are part of the [Network Science Institute](https://www.networkscienceinstitute.org/) at [Northeastern University London](https://www.nulondon.ac.uk/).
    design:
      background:
        gradient_end: '#ffffff'
        gradient_start: '#fffae0'
        #'#d9efff'
        text_color_light: false
  
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
      page_type: news
    design:
      view: compact
      columns: '2'
      background:
        gradient_end: '#ffffff'
        gradient_start: '#d9efff'
        text_color_light: false
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: london-tunnel.jpg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Blog Posts
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: posts
    design:
      view: showcase
      columns: '2'      
      flip_alt_rows: true
      background:
        gradient_start: '#d9efff'
        gradient_end: '#fffae0'
        text_color_light: false

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: vdf-fog.jpg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Featured Publications
      count: 6
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: '2'
      background:
        gradient_end: '#d9efff'
        gradient_start: '#fffae0'
        text_color_light: false

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 8
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: compact
      columns: '2'
      background:
        gradient_start: '#fffae0'
        gradient_end: '#ffffff'
        text_color_light: false

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: fermo-campagna.jpg
          filters:
            brightness: 1
          parallax: true
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./publication/" cta_text="See more publications →" %}}
    design:
      columns: '1'
      background:
        gradient_start: '#fffae0'
        gradient_end: '#ffffff'
        text_color_light: true
---
