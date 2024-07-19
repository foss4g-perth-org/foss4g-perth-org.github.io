---
layout: page
title: Registration
active: registration
description:
---

FOSS4G Perth 2024 is a one day event taking place on October 23rd.

Registration includes a fully catered day, with presentations from local and regional speakers. In addition to the FOSS4G event, participants are welcome to attend other ISPRS sessions happening on the same day. After the conference day, we'll head to a social event hosted by FOSS4G Perth.

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

### Early Bird: until ***Saturday 10 August 2024***
* Full price: $100
* Student: $50

### Standard: until Friday 4 October 2024
* Full price: $150
* Student: $50

### Late: closes Monday 21 October 2024
* Full price: $200
* Student: $50

## Workshop registration
22 Oct 2024 (am): Collecting data in the field with free & open source geospatial tools: QGIS, QField, and Mergin Maps (<a href="/program#workshop">more info here</a>)
* Full price: $100
* Student: $70


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