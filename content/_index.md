---
isPage: false
draft: false
title: Home
blocks:
  - type: latest
    heading:
      title: Derniers articles du blog
    ui:
      theme: light
      grid: container
      offset: start
      align: start
      scrollsnap: md
      layout: grid
    section: posts
    show_more: true
  - type: selected-docs
    heading:
      surtitle: Documentation
      title: Homelab
      text: Petite documentation pour mon homelab, pour moi-même, mais qui peut également servir à d'autres.
    ui:
      theme: light
      grid: container
      offset: start
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
