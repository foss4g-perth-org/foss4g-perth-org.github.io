---
layout: page
title: Registration
active: registration
description:
---

FOSS4G Perth 2024 is a one day event taking place on October 23rd at the Esplanade Hotel, Fremantle, WA.

Registration includes a fully catered day, with presentations from local and regional speakers. In addition to the FOSS4G event, participants are welcome to attend other ISPRS sessions happening on the same day. After the conference day, we'll head to a social event hosted by FOSS4G Perth.

<div id="register" class="anchor-offset"></div>


<!-- Trigger/Open The Modal -->
<div class="button_wrapper center">
  <button id="regoBtn" class="button">Register</button>
</div>

<!-- The Modal -->
<div id="regoModal" class="modal">

  <!-- Modal content -->
  <div class="modal-content">
    <span class="close">&times;</span>
    <div>DISCOUNT CODE: <span class="bold">FremantleOct24</span> (for FOSS4G Perth participants only)</div>
    <div class="inner-regobutton">
      <a href="https://interpoint.eventsair.com/isprs/isprsrego" class="btn" target="_blank">Register Now</a>
    </div>
    <div>
      When you select the "Register Now" button you will be redirected to the ISPRS Technical Commission IV Symposium registration portal, where you can register for FOSS4G Perth. Remember to use the provided discount code.
    </div>
  </div>

</div>

Early Bird: until Saturday 10 August 2024
* ~~Full price: $100~~ CLOSED
* Student: $50

Standard: until Friday 4 October 2024
* Full price: $150
* Student: $50

Late: closes Monday 21 October 2024
* Full price: $200
* Student: $50

Workshop registration
22 Oct 2024 (am): Collecting data in the field with free & open source geospatial tools: QGIS, QField, and Mergin Maps (<a href="/program#workshop">more info here</a>)
* Full price: $100
* Student: $70

<div id="grant-program" class="anchor-offset"></div>

<hr/>

## FOSS4G Perth Grant Program


We recognise that some people are self-funded, travel can be expensive, and every little bit helps. The FOSS4G Perth Grant Program is designed to support Western Australian residents who require assistance in covering some of the costs of attending FOSS4G Perth 2024.

### Who can apply?

Western Australian residents who might otherwise have difficulty attending FOSS4G Perth.

### What can you apply for?

Successful applicants will receive a free (non-transferable) conference registration.

### Application criteria

The grant program will be determined based on available funding and merit. Applicants will be assessed against the following criteria:
- Your contributions to open communities and community-building activities, such as Geogeeks, OpenStreetMap, or open source software projects.
- Extra consideration for those who have submitted a talk, students, individuals from diverse backgrounds, and those travelling from regional WA.
- Preference will be given to applicants who are paying their own way.

### Important dates

**Application Deadline**: Applications are open until 25 September.

**Evaluation Period**: Grant applications will be evaluated as they are received, starting from 28 August.

### How to apply

Send us an email at <grants@foss4g-perth.org> answering these questions:

1. Why do you want to attend FOSS4G Perth 2024?
2. Have you contributed to open geospatial community activities and projects? If so, how?
3. Have you submitted a talk to this year's FOSS4G Perth, or spoken at one of our previous events?
4. Do you have an alternate source of funding (e.g. employer)?

For more information, please email us at <grants@foss4g-perth.org>

### Supporting the grant program

The funding for this grant program comes from our conference partner, OSGeo Oceania, and our conference sponsors.  You can help make FOSS4G Perth more accessible and increase the diversity of attendees by becoming a sponsor of the conference.

For more information, visit our [sponsors page](/sponsors) or email us at <sponsor@foss4g-perth.org>.

<script>
var modal = document.getElementById("regoModal");
var btn = document.getElementById("regoBtn");
var span = document.getElementsByClassName("close")[0];

btn.onclick = function() {
  modal.style.display = "block";
}

span.onclick = function() {
  modal.style.display = "none";
}

window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}

document.addEventListener('click', function(event) {
  if (event.target.tagName === 'A' && event.target.target === '_blank') {
    modal.style.display = "none";
  }
});

</script>