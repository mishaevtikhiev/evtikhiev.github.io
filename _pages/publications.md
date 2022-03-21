---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<p style="margin-bottom: -10px; padding-bottom: 0; color: #888888"><i><b><span style="color: #992017">Red</span></b> titles indicate published or accepted papers.<br>
<b><span style="color: #888888">Grey</span></b> titles indicate pre-prints.</i></p>

<h2 >Software Engineering <span style="color: #888888">(16 published papers + 2 pre-prints)</span></h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2 >Laser Technologies <span style="color: #888888">(2 papers)</span></h2>

{% for post in site.publicationsphysics reversed %}
  {% include archive-single.html %}
{% endfor %}