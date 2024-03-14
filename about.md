---
layout: page
title: About
active: about
description: We are inviting the Western Australian open geospatial and mapping community to get involved by submitting a proposal.
---

FOSS4G Perth is a local, community-driven gathering of the Perth open geospatial community, focused on sharing stories and having fun with "Free and Open Source Software For Geospatial".

Free software is revolutionising how we work and play, and the geospatial community is embracing open source tools and data with gusto. Prime examples include QGIS, PostGIS, OpenStreetMap, Sentinel-2 satellite imagery, Python-based earth observation libraries and frameworks, GDAL, and many others.

The Perth community has been active in this space over the last several years. FOSS4G events are run independently by local, regional, and global community groups all over the world.

<a href="#footer">Get involved!</a>

## 2024 FOSS4G Perth Organising Committee
{% for person in site.data.committee %}
  <div><span class="bold">{{ person.name }}</span> {% if person.affiliation %}- <span class="text-sm">{{ person.affiliation}}</span>{% endif %}</div>
{% endfor %}