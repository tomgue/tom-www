---
isPage: false
draft: false
title: Home
hero:
  surtitle: Bienvenue
  title: Sur TomLab
  text: Mon petit "digital garden" 🌱
  image:
    src: /images/uploads/pages/alex-pavor-VUnjE00FRSA-unsplash.jpg
    src_mobile: /images/uploads/pages/alex-pavor-VUnjE00FRSA-unsplash.jpg
    credit: Photo de [Alex Pavor](https://unsplash.com/fr/@pavor99?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) sur [Unsplash](https://unsplash.com/fr/photos/un-fond-noir-aux-formes-hexagonales-VUnjE00FRSA?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
    background: true
    darken: true
  ui:
    theme: accent
    align: start
    vertical_align: center
    darken: false
blocks:
  - type: latest
    heading:
      surtitle: Blog
      title: Derniers articles du blog
    ui:
      grid: large
      offset: center
      align: start
      scrollsnap: md
      layout: grid
    limit: 6
    section: posts
    show_more: true
  - type: selected-docs
    heading:
      surtitle: Documentation
      title: Homelab
      text: Petite documentation pour mon homelab, pour moi-même, mais qui peut également servir à d'autres.
    ui:
      grid: large
      offset: center
      align: start
      scrollsnap: md
      layout: grid
    section: docs
    show_more: true
    source: toplevel
    items:
      - materiel-du-homelab
      - services-docker
isIndex: true
---
