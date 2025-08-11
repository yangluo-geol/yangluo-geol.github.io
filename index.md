---
layout: home
title: "Yang Luo - Geochemistry PhD Student"
author_profile: true
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
    <a href="mailto:yangluo@ucsb.edu?subject=Website%20Inquiry" class="btn-email">
      <i class="fas fa-envelope"></i> Email
    </a>
    <a href="https://scholar.google.com/citations?user=IOaZk2AAAAAJ" class="btn-scholar" target="_blank" rel="noopener">
      <i class="ai ai-google-scholar"></i> Scholar
    </a>
    <a href="https://github.com/yangluo-geol" class="btn-github" target="_blank" rel="noopener">
      <i class="fab fa-github"></i> GitHub
    </a>
  </div>

  <div class="research-section">
    <h3><i class="fas fa-microscope"></i> Research Focus</h3>
    <ul>
      <li>Petrology and mineral chemistry</li>
      <li>Geochronology and thermochronology</li>
      <li>Crustal evolution and tectonics</li>
    </ul>
    
    <h3><i class="fas fa-flask"></i> Analytical Methods</h3>
    <ul>
      <li>SEM-EDS/WDS</li>
      <li>LA-ICP-MS</li>
      <li>Electron microprobe analysis</li>
    </ul>
  </div>
</div>

<style>
.profile-container {
  max-width: 800px;
  margin: 2rem auto;
  padding: 0 1rem;
}

.profile-header {
  display: flex;
  align-items: center;
  gap: 2rem;
  margin-bottom: 1.5rem;
}

.profile-image {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #2a7ae2;
  box-shadow: 0 3px 10px rgba(0,0,0,0.2);
}

.profile-text h1 {
  margin: 0;
  font-size: 2.2rem;
  color: #333;
}

.profile-text h2 {
  margin: 0.3rem 0;
  font-size: 1.3rem;
  color: #2a7ae2;
  font-weight: 600;
}

.profile-text p {
  margin: 0.5rem 0;
  color: #555;
  line-height: 1.5;
}

.profile-links {
  display: flex;
  gap: 1rem;
  margin: 2rem 0;
  flex-wrap: wrap;
}

.btn-email, .btn-scholar, .btn-github {
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  text-decoration: none;
  color: white;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-weight: 500;
  transition: all 0.2s ease;
}

.btn-email {
  background: linear-gradient(135deg, #d44638, #c53727);
}

.btn-scholar {
  background: linear-gradient(135deg, #4285F4, #3367D6);
}

.btn-github {
  background: linear-gradient(135deg, #333, #222);
}

.btn-email:hover, .btn-scholar:hover, .btn-github:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.research-section {
  background: white;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  margin-top: 1.5rem;
}

.research-section h3 {
  color: #2a7ae2;
  margin-top: 0;
  display: flex;
  align-items: center;
  gap: 10px;
}

.research-section ul {
  padding-left: 1.5rem;
  line-height: 1.7;
}

@media (max-width: 700px) {
  .profile-header {
    flex-direction: column;
    text-align: center;
    gap: 1.5rem;
  }
  
  .profile-image {
    width: 140px;
    height: 140px;
  }
  
  .profile-links {
    justify-content: center;
  }
}
</style>
