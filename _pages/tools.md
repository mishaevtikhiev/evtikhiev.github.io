---
layout: archive
title: "Tools"
permalink: /tools/
author_profile: true
---

{% include base_path %}

In my research, I have personally developed and maintained only one tool: 
<a href="https://areyde.com/tool/buckwheat">Buckwheat</a>, a multi-language tokenizer for extracting identifiers from source code.
However, I participated in the development of several other tools created in the [Machine Learning Methods in Software Engineering](https://research.jetbrains.org/groups/ml_methods/) group at
[JetBrains Research](https://research.jetbrains.org/), or applied them for the analysis of large corpora of code. 
This page aims to conveniently list all such tools.

{% for post in site.tools %}
{% include archive-single.html %}
{% endfor %}