---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<p><b><span style="color: #992017">Red</span></b> titles indicate published or accepted papers.</p>
<p><b><span style="color: #888888">Grey</span></b> titles indicate pre-prints.</p>

<h2 >Software Engineering</h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2 >Physics</h2>

{% for post in site.publicationsphysics reversed %}
  {% include archive-single.html %}
{% endfor %}