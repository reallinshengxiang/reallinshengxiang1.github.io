---
layout: archive
title: "achievements"
permalink: /achievement/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/achievementmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.achievement reversed %}
  {% include archive-single-achievement.html %}
{% endfor %}
