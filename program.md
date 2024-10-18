---
layout: page
title: Program
active: program
description: We are inviting the Western Australian open geospatial and mapping community to get involved by submitting a presentation.
---


## Tutorial: 22 October 2024 (am)

### Collecting data in the field with free & open source geospatial tools: QGIS, QField, and Mergin Maps

**Presenters**: John Bryant, Grant Boxer, John Duncan

**Duration**: 2.5h
<details>
    <summary>More information</summary>
    {% include_relative read_more/workshop.html %}
</details>

<div class="divider"></div>


## Conference Day: 23 October 2024
<h3>Schedule</h3>

{% include schedule.html %}



<div class="divider-light"></div>


<div id="keynotes" class="anchor-offset"></div>

### Keynote Speakers

In collaboration with <a href="https://www.isprs.org/tc4-symposium2024/index.html" target="_blank" rel="noreferrer">ISPRS</a>, FOSS4G Perth is hosting two keynote speakers:


<div class="grid grid-cols-2">
    <div class="speaker-container">
        <a href="https://www.linkedin.com/in/drkjoyce/" target="_blank"><img src="/assets/img/program/karen-joyce.png" class="keynote-img" alt="karen-joyce">
        <h4>Karen Joyce</h4></a>
        <a href="https://www.isprs.org/tc4-symposium2024/speakers.html" target="_blank" rel="noreferrer">A biographer for Mother Earth, using satellites and drones as my scientific illustrators</a>
        <p>I share my experiences drawn from 25 years as a geospatial scientist in academia, military, industry, and small business to help people discover science beyond lab coats and test tubes. But I have an ulterior motive. I am passionate about how we can use drones and geospatial technology to watch over our environment and its changes. So the more people I can inspire to join me, the faster we can put plans in place to help keep our environment healthy into the future.
        </p>
    </div>
    <div class="speaker-container">
        <a href="https://www.linkedin.com/in/ahi-saipaia-761874207/" target="_blank"><img src="/assets/img/program/ahi-saipaia.png" class="keynote-img" alt="ahi-saipaia">
        <h4>Ahi Saipaia</h4></a>
        <a href="https://www.isprs.org/tc4-symposium2024/speakers.html" target="_blank" rel="noreferrer">From Paddock to Polygon: co-development of open-source geospatial applications and workflows for mapping diverse cropping systems in the Pacific</a>
        <p>Ahi is the lead Technical Officer for the Ministry of Agriculture, Food, Forests and Fisheries (MAFFF), Tonga. Ahi was a technical expert on an Australian Centre for International Agricultural Research (ACIAR) funded project using open-source geospatial applications to map and monitor Tonga’s diverse agricultural landscapes. Since the project’s end, she has assumed a lead technical role with MAFFF overseeing multiple nation wide crop surveys and agricultural mapping initiatives, resulting in one of the South Pacific’s most detailed and temporally consistent agricultural datasets.
        </p>
    </div>
</div>

<div class="divider-light"></div>


<div id="guests" class="anchor-offset"></div>

### Invited Speakers

<p>FOSS4G Perth welcomes special guest speaker Andrew Dowding from <a target="_blank" href="https://www.winyama.com.au/">Winyama</a>.</p>
<h5>Empowering Indigenous Communities with GIS: Micro-credentialing for First Nations Land Management</h5>

<div class="grid grid-cols-2">
    <div class="speaker-container">
        <a href="https://www.linkedin.com/in/andrew-dowding-036aaa11/" target="_blank"><img src="/assets/img/program/andrew_dowding.webp" class="keynote-img" alt="Andrew Dowding">
        <h4>Andrew Dowding</h4></a>
        <p>
        Andrew’s role is to manage and guide Winyama, create opportunities for the team to grow into their roles and most importantly to generate work for the organisation to be sustainable. Andrew is from the Ngarluma traditional owner group and grew up between Perth, Sydney, and the Pilbara. Andrew’s passion is Indigenous mapping and the use of technology for cultural safeguarding. He co-founded Winyama in 2018 to provide more opportunity for Indigenous people to work in the geospatial industry and within the broader digital economy.
        </p>
    </div>
    <!-- <div class="speaker-container">
        <a href="https://www.linkedin.com/in/kass-boladeras/" target="_blank"><img src="/assets/img/program/kass_boladeras.webp" class="keynote-img" alt="Kass Boladeras">
        <h4>Kass Boladeras</h4></a>
        <p>
        Kass is responsible for leading the marketing team and overseeing the company’s human resource department. Additionally, Kass manages and oversees Winyama’s social initiative, the Indigenous Mapping Workshop Australia program. Born and raised in Fremantle, Kass is a proud Ballardong woman with familial ties to the Wheatbelt (Northam, York, Toodyay).
        </p>
    </div> -->
</div>

<div class="divider-light"></div>

<div id="main-program" class="anchor-offset"></div>

<h3>Presentations</h3>

<div id="presentations">
{% for presentation in site.data.presentations %}
    {% include presentation_full.html
        presenter=presentation.presenter
        title=presentation.title
        abstract=presentation.abstract
        id=presentation.id
        organisation=presentation.organisation
    %}
{% endfor %}
</div>


<div class="divider"></div>

<div id="social" class="anchor-offset"></div>

## Social Event

<div class="social-program">
    <div>
        <a href="https://en.wikipedia.org/wiki/Bon_Scott" target="_blank"><img src="/assets/img/freo/bonscott.webp" alt="Statue of Bon Scott"></a>
    </div>
    <div>
        <p>At the end of the day, we'll kick off a fun social evening for registered FOSS4G and ISPRS attendees.</p>
        <p>We'll head to classic Freo venue <a href="https://beerpourium.com.au/" target="_blank">Beerpourium</a> to wind down, play foosball/pool/lawn bowls, and enjoy the warm glow of our wonderful geospatial community.</p>
        <p>We look forward to seeing you there :)</p>
    </div>
</div>
