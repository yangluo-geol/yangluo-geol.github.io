---
layout: home
title: "Yang Luo - Geochemistry PhD Student"
author_profile: true
---

<!-- ===== HERO SECTION ===== -->
<div class="hero">
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

<!-- ===== CONTENT SECTIONS ===== -->
<div class="content-sections">
  <div class="card">
    <h3><i class="fas fa-microscope"></i> Research</h3>
    <ul>
      <li>Petrology and mineralogy</li>
      <li>Geochronology</li>
      <li>Plate tectonics and crustal evolution</li>
    </ul>
  </div>

  <div class="card">
    <h3><i class="fas fa-flask"></i> Analytical Methods</h3>
    <ul>
      <li>Scanning Electron Microscope (SEM)</li>
      <li>Electron Microprobe Analysis (EPMA)</li>
      <li>Laser Ablation ICP-MS</li>
    </ul>
  </div>
</div>

<style>
/* ===== GLOBAL ===== */
body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  background: #f8f9fa;
  margin: 0;
  padding: 0;
  color: #333;
}

/* ===== HERO SECTION ===== */
.hero {
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 3rem 1rem;
  background: linear-gradient(135deg, #2a7ae2, #0056b3);
  color: white;
  text-align: center;
  flex-wrap: wrap;
}

.profile-pic {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid white;
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
  margin-bottom: 1rem;
}

.hero-text {
  max-width: 500px;
  margin-left: 2rem;
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

/* ===== CONTENT SECTIONS ===== */
.content-sections {
  display: flex;
  justify-content: center;
  gap: 2rem;
  padding: 2rem 1rem;
  flex-wrap: wrap;
}

.card {
  background: white;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  width: 280px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 14px rgba(0,0,0,0.15);
}

.card h3 {
  color: #2a7ae2;
  display: flex;
  align-items: center;
  gap: 8px;
  margin-top: 0;
}

.card ul {
  list-style-position: inside;
  padding: 0;
  margin: 0.5rem 0 0 0;
}

.card li {
  margin: 0.4rem 0;
}

@media (max-width: 700px) {
  .hero {
    flex-direction: column;
    text-align: center;
  }
  .hero-text {
    margin-left: 0;
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
