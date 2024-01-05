---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: 
      text: |
        <p style="text-align: center; font-size: 1.5em;">Zeolando is currently awaiting approval for funding from the <strong>Marie Skłodowska-Curie Actions Postdoctoral Fellowships</strong></p>

        <p style="text-align: center; font-size: 1.5em;">Keep visiting for more updates!.</p>

  #
  #- block: collection
  #  content:
  #    title: Latest News
  #    subtitle:
  #    text:
  #    count: 5
  #    filters:
  #      author: ''
  #      category: ''
  #      exclude_featured: false
  #      publication_type: ''
  #      tag: ''
  #    offset: 0
  #    order: desc
  #    page_type: post
  #  design:
  #    view: card
  #    columns: '1'
  #

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
        {{% cta cta_link="./publication/" cta_text="See group work →" %}}
    design:
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: slab_water.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['0', '0', '0', '0']
      css_class: fullscreen
---