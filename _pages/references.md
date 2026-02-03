---
layout: archive
title: "References"
permalink: /references/
author_profile: true
---

<style>
/* Reference layout */
.refs {
  display: grid;
  gap: 22px;
}

/* One row (left badge + right content) */
.ref-row {
  display: grid;
  grid-template-columns: 180px 1fr;
  gap: 22px;
  align-items: start;
}

/* Left badge box */
.ref-badge {
  background: #499FC1;           /* light tan */
  padding: 10px 14px;
  font-weight: 700;
  border-radius: 3px;
}

/* Right content */
.ref-body .ref-role {
  font-style: italic;
  font-weight: 600;
  margin-bottom: 4px;
}
.ref-body .ref-line {
  margin: 2px 0;
  line-height: 1.35;
}
.ref-body a { text-decoration: underline; }

/* Mobile: stack */
@media (max-width: 700px) {
  .ref-row {
    grid-template-columns: 1fr;
  }
  .ref-badge {
    width: fit-content;
  }
}
</style>

<div class="refs">

  <div class="ref-row">
    <div class="ref-badge">Dr. Ellis Solaiman</div>
    <div class="ref-body">
      <div class="ref-role">Reader in Computer Science</div>
      <div class="ref-line">Newcastle University, UK</div>
      <div class="ref-line"><a href="mailto:ellis.solaiman@newcastle.ac.uk">ellis.solaiman@newcastle.ac.uk</a></div>
      <!--<div class="ref-line">888-903-7653</div>-->
      <div class="ref-line">Relationship: Primary PhD Supervisor</div>
    </div>
  </div>

  <div class="ref-row">
    <div class="ref-badge">Prof. Rajiv Ranjan</div>
    <div class="ref-body">
      <div class="ref-role">Chair Professor in Computing Science and Internet of Things</div>
      <div class="ref-role">Academic Director, School of Computing</div>
      <div class="ref-line">Newcastle University, UK</div>
      <!--<div class="ref-line">525 North Wolfe Street, Room 313</div>
      <div class="ref-line">(410) 555-6789</div> -->
      <div class="ref-line"><a href="https://rajivranjan.net">Personal Blog</a></div>
       <div class="ref-line">Relationship: PhD Supervisor</div>
    </div>
  </div>


</div>
