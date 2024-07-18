---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Below is a list of some of my representative works.


{% include base_path %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


{% if site.author.googlescholar %}
  <div class="wordwrap">For a fuller list, see my google scholar:  <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}