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
  background: #efe3c9;           /* light tan */
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
    <div class="ref-badge">#1 - Tom Rolland</div>
    <div class="ref-body">
      <div class="ref-role">Human resources Manager</div>
      <div class="ref-line">33, Wrench Way, New York, 6780</div>
      <div class="ref-line"><a href="mailto:tomroll@email.com">tomroll@email.com</a></div>
      <div class="ref-line">888-903-7653</div>
      <div class="ref-line">Relationship: Direct Supervisor</div>
    </div>
  </div>

  <div class="ref-row">
    <div class="ref-badge">#2 - Dr. Susan Brown</div>
    <div class="ref-body">
      <div class="ref-role">Professor - Department of Pediatric Nursing</div>
      <div class="ref-line">Johns Hopkins University School of Nursing</div>
      <div class="ref-line">525 North Wolfe Street, Room 313</div>
      <div class="ref-line">(410) 555-6789</div>
      <div class="ref-line"><a href="mailto:sbrown@jhu.edu">sbrown@jhu.edu</a></div>
    </div>
  </div>

  <div class="ref-row">
    <div class="ref-badge">#3 - Dr. Hilda Everment</div>
    <div class="ref-body">
      <div class="ref-role">Associate Professor - Department of Psychiatry</div>
      <div class="ref-line">Johns Hopkins University School of Medicine</div>
      <div class="ref-line">525 North Wolfe Street, Room 330</div>
      <div class="ref-line">(410) 555-6790</div>
      <div class="ref-line"><a href="mailto:heverment@jhmi.edu">heverment@jhmi.edu</a></div>
    </div>
  </div>

  <div class="ref-row">
    <div class="ref-badge">#4 - Ms. Carla Castillo</div>
    <div class="ref-body">
      <div class="ref-role">Nursing Supervisor - Pediatric Critical Care Unit</div>
      <div class="ref-line">Johns Hopkins Hospital</div>
      <div class="ref-line">555 North Wolfe Street, Halstead 8</div>
      <div class="ref-line">(410) 555-6791</div>
      <div class="ref-line"><a href="mailto:ccastillo@jhmi.edu">ccastillo@jhmi.edu</a></div>
    </div>
  </div>

</div>
