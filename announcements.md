---
layout: page
title: Announcements
nav_exclude: true
description: A feed containing all of the class announcements.
---

# Announcements

{% assign asize = announcements | size %}
{% if asize == 0 %}
There are no announcements to display.
{% endif %}

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
