---
title: "Yu Wang - Research"
layout: textlay
excerpt: "Yu Wang -- Research"
sitemap: false
permalink: /research/
---

# Research

## Group highlights
(For a full list of publications and codes see [below](#full-list-of-publications) or go to [Google Scholar](https://scholar.google.com/citations?user=XPCmiz4AAAAJ&hl=en))

## Full list of publications
{%for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
