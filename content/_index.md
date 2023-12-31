---
# Leave the homepage title empty to use the site title
title:
date: 2023-08-04
type: landing

design:
  background:
    # Choose a color such as from https://html-color-codes.info
    color: 'navy'
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true

sections:
  - block: hero
    content:
      title: |
        BMIC
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **B**io-**M**edical **I**mage **C**omputing (BMIC) research combines computer vision and bio-medical image analysis (MRI, CT, Cell microscopy, etc.) . The lab is lead by Prof. Tammy Riklin Raviv.

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
      title: BGU
      subtitle: 
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: bgu_building.jpg
          filters:
            brightness: 1
          parallax: false
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
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
