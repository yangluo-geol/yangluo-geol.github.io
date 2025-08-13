---
layout: home
title: "Yang Luo - Geochemistry PhD Student"
author_profile: true
---

<!-- ===== HERO SECTION ===== -->
<div class="hero">
  <div class="hero-overlay"></div>
  <img src="/assets/images/profile.jpg" alt="Yang Luo" class="profile-pic">
  <div class="hero-text">
    <h1>Yang Luo</h1>
    <h2>PhD Student in Geochemistry</h2>
    <p>Department of Earth Science<br>University of California, Santa Barbara</p>
    <p>Email: <span class="email" onclick="copyEmail()" id="emailTooltip">Click to copy yangluo@ucsb.edu</span></p>
    <a href="https://scholar.google.com/citations?user=IOaZk2AAAAAJ" target="_blank" class="btn-scholar">
      <i class="ai ai-google-scholar"></i> Google Scholar
    </a>
  </div>
</div>

<!-- ===== MAIN CONTENT ===== -->
<div class="main-content">
  <section class="info-block">
    <h3><i class="fas fa-microscope"></i> Research</h3>
    <ul>
      <li>Petrology and mineralogy</li>
      <li>Geochronology</li>
      <li>Plate tectonics and crustal evolution</li>
    </ul>
  </section>

  <section class="info-block">
    <h3><i class="fas fa-flask"></i> Analytical Methods</h3>
    <ul>
      <li><span class="nowrap">Scanning Electron Microscope (SEM)</span></li>
      <li><span class="nowrap">Electron Microprobe Analysis (EPMA)</span></li>
      <li><span class="nowrap">Laser Ablation Inductively Coupled Plasma Mass Spectrometry (LA-ICP-MS)</span></li>
    </ul>
  </section>
</div>

<style>
body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  background: #f8f9fa;
  margin: 0;
  padding: 0;
  color: #333;
}

.nowrap {
  white-space: nowrap;
}

/* ===== HERO ===== */
.hero {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 3rem 1rem;
  text-align: center;
  flex-wrap: wrap;
  color: white;
  min-height: 100vh;
  background: url('/assets/images/scenic2.jpg') no-repeat center center/cover,
              url('/assets/images/scenic1.jpg') no-repeat center center/cover;
}

.hero-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.25); /* lighter overlay for brighter background */
  z-index: 0;
}

.profile-pic {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid white;
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
  margin-bottom: 1rem;
  z-index: 1;
  position: relative;
}

.hero-text {
  max-width: 600px; /* wider to accommodate text */
  margin-left: 2rem;
  z-index: 1;
  position: relative;
}

.hero h1 {
  font-size: 2.2rem;
  margin: 0;
}

.hero h2 {
  font-size: 1.3rem;
  margin: 0.3rem 0 1rem 0;
  font-weight: 500;
}

.hero p {
  margin: 0.3rem 0;
  font-size: 1rem;
}

.email {
  text-decoration: underline;
  cursor: pointer;
  color: #ffdd57;
}

.btn-scholar {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  background: white;
  color: #2a7ae2;
  font-weight: 500;
  text-decoration: none;
  transition: all 0.2s ease;
}

.btn-scholar:hover {
  background: #e9ecef;
}

/* ===== MAIN CONTENT ===== */
.main-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2rem 1rem;
  gap: 1.5rem;
}

.info-block {
  background: white;
  padding: 1.5rem 2rem;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.08);
  max-width: 750px; /* wider blocks for long words */
  width: 100%;
}

.info-block h3 {
  color: #2a7ae2;
  display: flex;
  align-items: center;
  gap: 8px;
  margin-top: 0;
}

.info-block ul {
  list-style-position: inside;
  padding: 0;
  margin: 0.5rem 0 0 0;
}

.info-block li {
  margin: 0.4rem 0;
}

@media (max-width: 900px) {
  .hero-text {
    max-width: 90%; /* responsive for mobile */
    margin-left: 0;
  }
  .info-block {
    max-width: 90%;
  }
}

@media (max-width: 700px) {
  .hero {
    flex-direction: column;
    text-align: center;
  }
}
</style>

<script>
function copyEmail() {
  const email = 'yangluo@ucsb.edu';
  const tooltip = document.getElementById('emailTooltip');
  navigator.clipboard.writeText(email).then(() => {
    tooltip.textContent = 'Copied!';
    setTimeout(() => { tooltip.textContent = 'Click to copy yangluo@ucsb.edu'; }, 2000);
  });
}
</script>
