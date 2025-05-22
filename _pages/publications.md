---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


  You can also find my articles on <u><a href="{{[author.googlescholar](https://scholar.google.com/citations?hl=en&user=K4eycz0AAAAJ&view_op=list_works&sortby=pubdate)}}">my Google Scholar profile</a>.</u>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
