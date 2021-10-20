---
layout: home
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/header.jpg
    background_image_opacity: 65
    content: >-
      # Real, beautiful plants right to your door

      Don't forget to add your Snipcart API key to the site's configuration to
      enable Cart actions.
    actions:
      - title: See all items
        url: /store
        arrow: true
        style: primary
  - type: featured_products_section
    section_id: best_sellers_section
    title: Best sellers
    icon: true
    light_title: true
    featured_products:
      - content/pages/products/plant1.md
      - content/pages/products/plant3.md
      - content/pages/products/plant5.md
      - content/pages/products/plant7.md
  - type: promotion_section
    section_id: promotion_section
    title: A new home interior for summer
    subtitle: from $149.99
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      title: Discover
      url: /store
      style: secondary
      arrow: true
seo:
  title: Planty Theme
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Planty Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Planty Theme
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
---
