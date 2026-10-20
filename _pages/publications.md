---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<p class="pub-note">* indicates equal contribution.</p>

{% for post in site.publications reversed %}
  {% include archive-publication.html %}
{% endfor %} 
