---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<p style="margin-bottom: -10px; padding-bottom: 0; color: #888888"><i><b>J</b> — Journal papers.<br>
<b>C</b> — Conference papers.</i><br>
<b>P</b> — Pre-prints.</p>

<h2 >Software Engineering</h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<h2 >Laser Technologies</h2>

{% for post in site.publicationsphysics reversed %}
  {% include archive-single.html %}
{% endfor %}