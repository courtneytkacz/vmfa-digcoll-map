---
layout: template1
title: About
comments: false
---

<div class="jumbotron">
    <p>{{ site.desc }}</p>
    <p><a class="btn btn-lg btn-primary" href="https://github.com/uhlibraries-digital/bcdams-map" role="button">View {{ site.title }} Code on Github &raquo;</a></p>
</div>

# Description

The {{ site.title }} builds on the University of Houston Digital Library's [Metadata Dictionary](http://digital.lib.uh.edu/about/metadata). It aligns closely with the [DPLA MAP v4.0](https://dp.la/info/wp-content/uploads/2015/03/MAPv4.pdf).

# API

| Function                          | Returns |
| --------------------------------- | ------- |
| ```/api/brays.json```             | [Brays](https://github.com/uhlibraries-digital/brays) application data as JSON |
| ```/api/carpenters.json```        | [Carpenters](https://github.com/uhlibraries-digital/carpenters) application data as JSON |
| ```/api/elements.json```          | All metadata elements as JSON |
| ```/api/graph.jsonld```           | {{ site.title }} graph as JSON-LD |
