---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle: ''
      text: The **Zeolando** project aims to unveil the mysteries of zeolites under *operando* conditions by leveraging machine-learning accelerated molecular dynamic simulations and experimental methods such as Nuclear Magnetic Resonance and vibrational spectroscopies.
       Zeolando is currently awaiting approval for funding from the **Marie Skłodowska-Curie Actions Postdoctoral Fellowships**
    design:
      columns: '1'
      css_class: fullscreen

  - block: hero
    content:
      title: |

      #image:
      #  filename: welcome.jpg
      text: |

        <div style="text-align: center;">The **Zeolando** project aims to unveil the mysteries of zeolites under *operando* conditions by leveraging machine-learning accelerated molecular dynamic simulations and experimental methods such as Nuclear Magnetic Resonance and vibrational spectroscopies.</div>

        <div style="text-align: center;">Zeolando is currently awaiting approval for funding from the **Marie Skłodowska-Curie Actions Postdoctoral Fellowships**.</div>
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
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---