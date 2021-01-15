---
layout: home
title: "COMP 152: Explainable Artificial Intelligence"
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

As machine learning systems are increasingly being considered for employments in contexts where their decisions can have real (positive and negative) impacts on people's lives, scholars and activists have increasingly raised concerns about the transparency and accountability of such systems and their designers. The field of explainable artificial intelligence (XAI) has sprung up in recent years to address some of these concerns by developing systems which can explain the reasons behind their decisions and outputs to users.  In this course, we explore this up-and-coming subfield of AI by learning the basic concepts and ideas, and discussing recent research papers in the field.  We will study both the central ideas and concrete systems constructed using these ideas. We will also think more broadly about the assumptions underlying the field of XAI and the ethical debates within the field.

This class meets **Monday** and **Wednesday**, **10:30-11:45AM** on Zoom.

## Instructor
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}