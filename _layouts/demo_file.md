---
layout: demo
title: Rising Sun
---

# {{page.title}}

 A site called DEMO.
 
 Show Time: {{site.when}}
 
 {% for item in site.data.demo%}
 
 The country of {{item.name}} was created in {{item.date}}. Its flag is {{item.flag}}
 
 {%endfor%}
 