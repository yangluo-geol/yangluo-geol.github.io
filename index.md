---
layout: home
title: "Yang Luo"
permalink: /
---

<div class="profile-container">
  <div class="profile-header">
    <img src="/assets/images/profile.jpg" alt="Yang Luo" class="profile-image">
    <div class="profile-text">
      <h1>Yang Luo</h1>
      <h2>Ph.D. Candidate in Geochemistry</h2>
      <p>Department of Earth Science<br>University of California, Santa Barbara</p>
    </div>
  </div>

  <div class="profile-links">
    <a href="mailto:yangluo@ucsb.edu" class="btn-email">
      <i class="fas fa-envelope"></i> Email
    </a>
    <a href="https://orcid.org/0000-0001-8821-9899" class="btn-orcid" target="_blank">
      <i class="ai ai-orcid"></i> ORCID
    </a>
    <a href="https://github.com/yangluo-geol" class="btn-github" target="_blank">
      <i class="fab fa-github"></i> GitHub
    </a>
  </div>

  <div class="research-section">
    <h3>Research Interests</h3>
    <ul>
      <li>Petrology and geochemistry</li>
      <li>Geochronology</li>
      <li>Crustal evolution</li>
    </ul>

    <h3>Current Projects</h3>
    <p>Dating of glacial diamictites using detrital zircons to study atmospheric oxygen variations.</p>
  </div>
</div>

<style>
.profile-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
}

.profile-header {
  display: flex;
  align-items: center;
  gap: 2rem;
  margin-bottom: 2rem;
}

.profile-image {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #2a7ae2;
}

.profile-text h1 {
  margin: 0;
  font-size: 2rem;
}

.profile-text h2 {
  margin: 0.5rem 0;
  font-size: 1.25rem;
  color: #2a7ae2;
}

.profile-links {
  display: flex;
  gap: 1rem;
  margin-bottom: 2rem;
  flex-wrap: wrap;
}

.btn-email, .btn-orcid, .btn-github {
  padding: 0.5rem 1rem;
  border-radius: 4px;
  text-decoration: none;
  color: white;
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
}

.btn-email {
  background-color: #d44638;
}

.btn-orcid {
  background-color: #a6ce39;
}

.btn-github {
  background-color: #333;
}

.research-section {
  line-height: 1.6;
}

@media (max-width: 600px) {
  .profile-header {
    flex-direction: column;
    text-align: center;
  }
}
</style>
