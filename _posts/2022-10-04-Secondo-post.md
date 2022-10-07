---
layout: post
title: secondo post
author: ernia
date: 2022-10-04
permalink: secondo-post/
---
<h3> sottotitolo</h3>
testo con spazio sopra e sotto

<p>paragrafo</p>

{% if page.author == "sfera ebbasta" %}

**sono una rockstar**

{% elsif page.author == "tedua" %}

**roccia ho portato il mare a Milano**

{% else %}

**cavallini sulla mia maglietta**

{% endif %}