---
title: Eleventy With Eckel
layout: "base.njk"
---

JamStack!

{% for post in collections.posts %}
  
 - [{{ post.data.title }}]({{ post.url}}) 
   
{% endfor %}
