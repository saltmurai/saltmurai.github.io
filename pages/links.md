---
layout: mypost
title: link
---

lorem ipsum

```
tile：{{ site.title }}
descript：{{ site.description }}
baseurl：{{ site.domainUrl }}{{ site.baseurl }}
logo：{{ site.domainUrl }}{{ site.baseurl }}/static/img/logo.jpg
```

<ul>
  {%- for link in site.links %}
  <li>
    <p><a href="{{ link.url }}" title="{{ link.desc }}" target="_blank" >{{ link.title }}</a></p>
  </li>
  {%- endfor %}
</ul>
