---
title: Home
sections:
  - type: features_section
    features:
      - image_alt: Brandon Guidelines
        media_position: right
        media_width: thirty-three
        actions:
          - label: Resume
            url: 'https://www.linkedin.com/in/annserba/'
            style: secondary
            has_icon: true
            icon: linkedin
            icon_position: right
            new_window: true
            no_follow: false
            type: action
        align: center
    feature_padding_vert: small
    background_color: primary
    title: Anna Serba
    subtitle: Front-end developer blog
  - type: grid_section
    title: Tehnologes
    align: center
    grid_items:
      - image: images/logo-8.svg
        image_alt: Git logo
        image_align: center
        title: Git
        title_align: center
      - image: images/logo-3.svg
        image_alt: Gatsby logo
        image_align: center
        title: Getsby
        content_align: center
        title_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
    enable_cards: false
  - type: blog_feed_section
    title: Blog Feed
    actions:
      - label: View All
        url: /blog
        style: primary
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 3
    show_image: true
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
seo:
  title: Anna Serba
  description: The preview of the DIY theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit DIY Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the DIY theme
      keyName: property
    - name: 'og:image'
      value: images/diy-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit DIY Theme
    - name: 'twitter:description'
      value: The preview of the DIY theme
    - name: 'twitter:image'
      value: images/diy-preview.png
      relativeUrl: true
template: advanced
---
