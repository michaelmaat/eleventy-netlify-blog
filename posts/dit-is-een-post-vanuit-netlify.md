---
title: Dit is een post vanuit Netlify
date: 2020-06-10T05:46:13.719Z
author: Dan Urbanowicz
summary: Een korte samenvatting
tags:
  - post
  - bami
---
Dit is dan de hoofdtekst. Het lijkt me dat de samenvatting al in het overzicht te zien is. Ik vraag me af of dat klopt?

![Overzicht van het kaas bos](/static/img/182_2160.jpg "Het kaas bos in volle glorie")



```javascript
// Universal slug filter strips unsafe chars from URLs
eleventyConfig.addFilter("slugify", function(str) {
  return slugify(str, {
    lower: true,
    replacement: "-",
    remove: /[*+~.·,()'"`´%!?¿:@]/g
  });
});
```