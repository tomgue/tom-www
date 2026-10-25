---
isPage: false
draft: false
title: Home
hero:
  surtitle: Bienvenue
  title: Sur TomLab
  text: Mon petit "digital garden" 🌱
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
