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
      <h2>PhD Student in Geochemistry</h2>
      <h3>Email: <span class="email" onclick="copyEmail()" id="emailTooltip">Click to copy yangluo@ucsb.edu</span></h3>
      <p>Department of Earth Science<br>University of California, Santa Barbara</p>
      <a href="https://scholar.google.com/citations?user=IOaZk2AAAAAJ" class="btn-scholar" target="_blank" rel="noopener noreferrer">
        <i class="ai ai-google-scholar"></i> Google Scholar
      </a>
    </div>
  </div>
</div>

<!-- Wrapper to center the two sections -->
<div class="center-wrapper">
  <div class="info-section">
    <h3><i class="fas fa-microscope"></i> Research</h3>
    <ul>
      <li>Petrology and mineralogy</li>
      <li>Geochronology</li>
      <li>Plate tectonics and crustal evolution</li>
    </ul>
  </div>

  <div class="info-section">
    <h3><i class="fas fa-flask"></i> Analytical Methods</h3>
    <ul>
      <li>Scanning Electron Microscope (SEM)</li>
      <li>Electron Microprobe Analysis (EPMA)</li>
      <li>Laser Ablation Inductively Coupled Plasma Mass Spectrometry (LA-ICP-MS)</li>
    </ul>
  </div>
</div>

<style>
.profile-container {
  max-width: 850px;
  margin: 2rem auto;
  padding: 0 1rem;
  font-family: 'Helvetica Neue', Arial, sans-serif;
}

.profile-header {
  display: flex;
  align-items: center;
  gap: 2rem;
  flex-wrap: wrap;
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

.email {
  color: #2a7ae2;
  cursor: pointer;
  text-decoration: underline;
}

.btn-scholar {
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  text-decoration: none;
  color: white;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-weight: 500;
  background: linear-gradient(135deg, #4285F4, #3367D6);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.btn-scholar:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

/* Center wrapper for the two sections */
.center-wrapper {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 2rem;
  margin-top: 2rem;
}

.info-section {
  background: white;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  max-width: 320px;
}

.info-section h3 {
  color: #2a7ae2;
  margin-top: 0;
  display: flex;
  align-items: center;
  gap: 10px;
  font-size: 1.3rem;
}

.info-section ul {
  list-style-position: inside;
  padding-left: 0;
  margin: 0;
}

.info-section li {
  margin-bottom: 0.5rem;
}

@media (max-width: 700px) {
  .profile-header {
    flex-direction: column;
    text-align: center;
  }
  .center-wrapper {
    flex-direction: column;
    align-items: center;
  }
}
</style>

<script>
function copyEmail() {
  const email = 'yangluo@ucsb.edu';
  const tooltip = document.getElementById('emailTooltip');
  navigator.clipboard.writeText(email).then(() => {
    tooltip.textContent = 'Copied to clipboard!';
    setTimeout(() => { tooltip.textContent = 'Click to copy yangluo@ucsb.edu'; }, 2000);
  });
}
</script>
