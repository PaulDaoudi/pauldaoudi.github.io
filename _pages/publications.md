---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
  a {
    text-decoration: none; /* Remove underlines from all links */
  }

  a:hover {
    text-decoration: underline; /* Add underline on hover */
  }
</style>

{% if site.author.googlescholar %}
  You can also find my articles on my <a href="{{ site.author.googlescholar }}">Google Scholar</a> profile.
{% endif %}

{{author}}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
