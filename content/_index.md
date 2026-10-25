---
isPage: false
draft: false
title: Home
hero:
  surtitle: Bienvenue
  title: Sur TomLab
  text: Mon petit digital garden !
  image:
    src: https://images.unsplash.com/photo-1541701494587-cb58502866ab
    credit: Photo by <a href="https://unsplash.com/@aznbokchoy?utm_source=sveltia-cms&amp;utm_medium=referral">Lucas K</a> on <a href="https://unsplash.com/?utm_source=sveltia-cms&amp;utm_medium=referral">Unsplash</a>
    background: false
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
      grid: small
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
