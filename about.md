---
layout: page
title: About
active: about
description: We are inviting the Western Australian open geospatial and mapping community to get involved by submitting a proposal.
---

<div>
  <p>FOSS4G stands for "Free and Open Source Software for Geospatial." <a href="https://www.osgeo.org/initiatives/foss4g/" target="_blank">FOSS4G events</a> are part of a global conference series focused on open source geospatial software, overseen by the <a href="https://www.osgeo.org/" target="_blank">Open Source Geospatial Foundation (OSGeo)</a>. The events bring together developers, users, decision-makers, and observers from a broad spectrum of organisations and fields interested in these technologies.</p>

<p>The FOSS4G Perth community has been active in the FOSS4G space over the last several years, with local events held in 2020 and 2021.</p>

  <p></p>
</div>

<div class="grid grid-cols-2 img-right">
  <div>
    <h2>Key dates 2024</h2>
    <div>
      <ul>
        <li>Early Bird <a href="/registration">registration</a>: 22 July-10 August</li>
        <li>Call for Presentations: 1 July-21 August</li>
        <li>Standard <a href="/registration">registration</a>: 11 August-4 October</li>
        <li><a href="/program">Full program</a> released: 25 September</li>
        <li>Late <a href="/registration">registration</a>: 5-21 October</li>
        <li><a href="/program">FOSS4G Perth - Event Day! 23 October</a></li>
      </ul>
    </div>
  </div>
    <div>
    <img src="/assets/img/freo/occy2.webp" alt="Fremantle Octopus" />
  </div>
</div>


## 2024 Organising Committee & Volunteers
<div class="grid people-grid">
{% for person in site.data.committee %}
  <div class="person">
    {% if person.img %}
    <img src="/assets/img/committee/{{person.img}}" alt="{{ person.name }}"/>
    {% else %}
    <img src="/assets/img/committee/default.png" alt="FOSS4G logo"/>
    {% endif %}
    <div>
      <div class="bold">{{ person.name }}</div>
      {% if person.affiliation %}
        <div class="text-sm">{{ person.affiliation}}</div>
      {% endif %}
    </div>
  </div>
{% endfor %}
</div>

<!-- ## FOSS4G Perth 2024 Volunteers
<div>
{% for person in site.data.volunteers %}
   {{ person.name }}<span>,</span>
{% endfor %}
</div> -->
