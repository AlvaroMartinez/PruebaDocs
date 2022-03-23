---
title: Sitio de prueba'
layout: 'layouts/page.njk'
metaDesc: '11ty theme'
imageURL: 
permalink: '{% if pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html'

eleventyNavigation:
  key: Home
  title: 🏠 Home
  order: 1
---
Aqui va la descripción, no se como se vea
