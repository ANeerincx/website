---
title: Projects
layout: default
permalink: /projects/
published: true
---

<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.project-card {
  position: relative;
  background-color: #f9f9f9;
  border: 1px solid #e1e4e8;
  border-radius: 12px;
  padding: 1rem;
  overflow: hidden;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  cursor: pointer;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.1);
}

.project-title {
  font-weight: 600;
  font-size: 1.1rem;
  margin-bottom: 0.5rem;
  color: #1a1a1a;
}

.project-date {
  font-size: 0.85rem;
  color: #666;
  margin-bottom: 0.75rem;
}

.project-description {
  font-size: 0.95rem;
  color: #333;
  display: none;
}

.project-card:hover .project-description {
  display: block;
}
</style>

<div class="project-grid">

<div class="project-card">
  <div class="project-title">PANORAIMA</div>
  <div class="project-date">2025 – ongoing</div>
  <div class="project-description">
    EU-funded project expanding AI education beyond ICT fields, building on HCAIM. Includes 16 partners co-developing AI curricula and flexible modules for up/reskilling professionals across Europe.
  </div>
</div>

<div class="project-card">
  <div class="project-title">DROOMROBOT</div>
  <div class="project-date">2025 – 2026</div>
  <div class="project-description">
    <a href="https://www.hu.nl/onderzoek/projecten/droomrobot">This project</a> explores using social robots with guided imagery to reduce anxiety and pain in hospitalized children during medical procedures.
  </div>
</div>

<div class="project-card">
  <div class="project-title">CJG Capelle</div>
  <div class="project-date">2020 – 2025</div>
  <div class="project-description">
    Exploring how social robots can support care at the Dutch Child and Family Center using mixed-methods research, including waiting room and coaching session trials.
  </div>
</div>

<div class="project-card">
  <div class="project-title">GAIPS Lab Visit</div>
  <div class="project-date">2023</div>
  <div class="project-description">
    Developed and tested a social robot game to support emotional learning in children. Evaluated robot behaviors in real classrooms at Portuguese primary schools.
  </div>
</div>

<div class="project-card">
  <div class="project-title">PAL Project</div>
  <div class="project-date">2015</div>
  <div class="project-description">
    Created a robot buddy for children with diabetes; studied how Italian and Dutch children interact differently with the robot. <a href="https://ieeexplore.ieee.org/abstract/document/7451818">Read the paper</a>.
  </div>
</div>

</div>
