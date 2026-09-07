---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

An overview of all primary pages and resources on this site. For search engines and automated crawlers, a machine-readable [XML Sitemap]({{ base_path }}/sitemap.xml) is also available.

## Main Navigation

* **[Welcome to Hitender Oswal’s Research Page]({{ base_path }}/)**  
  Academic background, research at KurtLab, industry experience at AWS GuardDuty, and news & recent activities.

* **[Research Projects]({{ base_path }}/publications/)**  
  Selected research projects and publications:
  * **Synthetic CT Generation for Stroke Lesion Segmentation** (KurtLab ongoing research with diffusion models)
  * **Stroke Lesion Segmentation** (MICCAI ISLES'24 Challenge Winner, Shapley explainability, low-resource clinical settings)
  * **Software and Systems Design Work** (AWS GuardDuty autonomous AI threat framework & scalable telemetry microservice)
  * **Other Peer-reviewed Published Research** (Human-computer interaction projects at UW)

* **[Curriculum Vitae (PDF)]({{ base_path }}/files/Hitender_K_Oswal_CV.pdf)**  
  Complete academic CV including education, appointments, publications, honors, and technical leadership.

{% if site.posts.size > 0 %}
## Posts
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if site.publications.size > 0 %}
## Publications
{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

## Search Engine Index

* **[XML Sitemap]({{ base_path }}/sitemap.xml)** — Complete machine-readable XML sitemap for search engines.

