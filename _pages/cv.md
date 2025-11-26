---
layout: archive
title: "Principal Investigator"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
/* CV Page Styles */
.cv-download-section {
  padding-bottom: 1.25rem;
  border-bottom: 1px solid #e5e7eb;
  margin-bottom: 1.5rem;
}

.cv-download-btn {
  text-decoration: none;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  font-size: 0.875rem;
  padding: 0.625rem 1.25rem;
  background-color: #3D0000 !important;
}

.cv-download-btn:hover {
  background-color: #240000 !important;
}

.cv-section-title {
  color: #2c3e50;
  margin: 0 0 1.5rem 0;
  font-size: 1.25rem;
  display: flex;
  align-items: center;
  gap: 0.875rem;
}

.cv-section-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 2.25rem;
  height: 2.25rem;
  border-radius: 50%;
  font-size: 1rem;
  transition: all 0.2s ease;
  flex-shrink: 0;
}

.cv-section-title:hover .cv-section-icon {
  transform: scale(1.1);
}

.cv-section-icon--education,
.cv-section-icon--work,
.cv-section-icon--research {
  color: #3D0000;
  background-color: #F7EDED;
  border: 2px solid #3D0000;
}

.cv-section-content {
  padding-left: 1.25rem;
  margin-left: 0.3125rem;
  margin-bottom: 2.5rem;
}

.cv-section-content--education,
.cv-section-content--work {
  border-left: 4px solid #3D0000;
}

.cv-item {
  margin-bottom: 1.25rem;
}

.cv-item:last-child {
  margin-bottom: 0;
}

.cv-item-header {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  margin-bottom: 0.25rem;
}

.cv-item-title {
  font-size: 1.1em;
  font-weight: 600;
  color: #1a202c;
}

.cv-item-date {
  color: #7f8c8d;
  font-weight: 500;
  white-space: nowrap;
}

.cv-item-subtitle {
  color: #555;
  font-size: 1em;
  line-height: 1.5;
}

.cv-interests-container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.75rem;
}

.cv-interest-tag {
  background-color: #F7EDED;
  color: #3D0000;
  padding: 0.625rem 1.25rem;
  border-radius: 30px;
  border: 1px solid #e5c9c9;
  font-size: 1em;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  font-weight: 500;
}
</style>

<div class="cv-download-section">
  <a href="/files/CV_Lei Yang.pdf" target="_blank" class="btn btn--info cv-download-btn">
    <i class="fas fa-file-download"></i> Download CV
  </a>
</div>

<h2 class="cv-section-title">
  <i class="fas fa-graduation-cap cv-section-icon cv-section-icon--education"></i>Education
</h2>

<div class="cv-section-content cv-section-content--education">
  <div class="cv-item">
    <div class="cv-item-header">
      <strong class="cv-item-title">Johns Hopkins University</strong>
      <span class="cv-item-date">2023 - 2025</span>
    </div>
    <div class="cv-item-subtitle">Postdoc in Mechanical Engineering</div>
  </div>

  <div class="cv-item">
    <div class="cv-item-header">
      <strong class="cv-item-title">The University of Sydney</strong>
      <span class="cv-item-date">2022</span>
    </div>
    <div class="cv-item-subtitle">Ph.D. in Civil Engineering</div>
  </div>

  <div class="cv-item">
    <div class="cv-item-header">
      <strong class="cv-item-title">Northeastern University</strong>
      <span class="cv-item-date">2018</span>
    </div>
    <div class="cv-item-subtitle">M.S. in Mining Engineering</div>
  </div>

  <div class="cv-item">
    <div class="cv-item-header">
      <strong class="cv-item-title">Northeastern University</strong>
      <span class="cv-item-date">2015</span>
    </div>
    <div class="cv-item-subtitle">B.S. in Mining Engineering</div>
  </div>
</div>

<h2 class="cv-section-title">
  <i class="fas fa-briefcase cv-section-icon cv-section-icon--work"></i>Work Experience
</h2>

<div class="cv-section-content cv-section-content--work">
  <div class="cv-item">
    <div class="cv-item-header">
      <strong class="cv-item-title">Honor Device Co., Ltd.</strong>
      <span class="cv-item-date">Mar 2022 - Aug 2023</span>
    </div>
    <div class="cv-item-subtitle">Senior R&D and Project Manager</div>
  </div>

  <div class="cv-item">
    <div class="cv-item-header">
      <strong class="cv-item-title">The University of Sydney</strong>
      <span class="cv-item-date">Aug 2019 - Dec 2019</span>
    </div>
    <div class="cv-item-subtitle">Teaching Assistant</div>
  </div>

  <div class="cv-item">
    <div class="cv-item-header">
      <strong class="cv-item-title">RMIT University</strong>
      <span class="cv-item-date">Apr 2017 - July 2018</span>
    </div>
    <div class="cv-item-subtitle">Research Assistant</div>
  </div>
</div>

<h2 class="cv-section-title">
  <i class="fas fa-flask cv-section-icon cv-section-icon--research"></i>Research Interests
</h2>

<div class="cv-interests-container">
  <span class="cv-interest-tag">Geomechanics</span>
  <span class="cv-interest-tag">Impact Dynamics</span>
  <span class="cv-interest-tag">Planetary Defense</span>
  <span class="cv-interest-tag">AI-driven Composite Design</span>
</div>
