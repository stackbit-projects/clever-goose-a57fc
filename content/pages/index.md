---
title: Home
hide_title: true
sections:
  - section_id: hero
    type: section_hero
    title: 'Hola, soy Mauricio Gonzalez y soy programador Full Stack'
    content: |
      ##### Programmer | Software Development | Full Stack Developer |&#xA;&#xA;
    actions:
      - label: Contactame
        url: /contact
        style: button
        icon: twitter
      - label: lorem-ipsum
        url: '#'
        style: button
        icon: linkedin
        new_window: false
        no_follow: false
        type: action
  - section_id: latest-projects
    type: section_portfolio
    layout_style: mosaic
    title: Algunos de Mis Proyectos
    projects_number: 6
    view_all_label: View All
    view_all_url: portfolio
  - section_id: testimonials
    type: section_testimonials
    title: Testimonials
    subtitle: An optional subtitle of the section
    col_number: three
    testimonials:
      - author: Sean Salazar
        avatar: images/sean_salazar.jpg
        avatar_alt: Sean Salazar's photo
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla.
      - author: Aubrey Hoover
        avatar: images/aubrey_hoover.jpg
        avatar_alt: Aubrey Hoover's photo
        content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
      - author: Deegan Wallace
        avatar: images/deegan_wallace.jpg
        avatar_alt: Deegan Wallace's photo
        content: >-
          Sed laoreet magna commodo libero euismod sodales. Nunc ac libero
          convallis, interdum ligula vel, pretium diam.
  - section_id: latest-posts
    type: section_posts
    title: Blog
    subtitle: Mira alguna de nuestras publicaciones
    posts_number: 3
    col_number: three
    actions:
      - label: ¡Vamos al blog!
        url: blog
        style: button
seo:
  title: Home
  description: The preview of the Exto theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Home
      keyName: property
    - name: 'og:description'
      value: The preview of the Exto theme
      keyName: property
    - name: 'og:image'
      value: images/exto_preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: home
    - name: 'twitter:description'
      value: The preview of the Exto theme
    - name: 'twitter:image'
      value: images/exto_preview.png
      relativeUrl: true
layout: advanced
---
