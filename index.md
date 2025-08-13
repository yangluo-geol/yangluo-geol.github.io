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
      <h3>Email: yangluo@ucsb.edu</h3>
      <p>Department of Earth Science<br>University of California, Santa Barbara</p>
    </div>
  </div>
    
  <a href="https://scholar.google.com/citations?user=IOaZk2AAAAAJ" class="btn-scholar" target="_blank" rel="noopener noreferrer">
    <i class="ai ai-google-scholar"></i> Google Scholar
  </a>
</div>

<div class="research-section">
  <h3><i class="fas fa-microscope"></i> Research </h3>
  <ul>
    <li>Petrology and mineralogy</li>
    <li>Geochronology</li>
    <li>Plate tectonics and crustal evolution</li>
  </ul>
  
  <h3><i class="fas fa-flask"></i> Analytical Methods</h3>
  <ul>
    <li>Scanning Electron Microscope (SEM)</li>
    <li>Electron Microprobe Analysis (EPMA)</li>
    <li>Laser Ablation Inductively Coupled Plasma Mass Spectrometry (LA-ICP-MS)</li>
  </ul>
</div>

<style>
.profile-container {
  max-width: 800px;
  margin: 2rem auto;
  padding: 0 1rem;
  font-family: 'Helvetica Neue', Arial, sans-serif;
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
  line-height: 1.2;
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

.btn-scholar {
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  text-decoration: none;
  color: white;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-weight: 500;
  transition: all 0.2s ease;
  background: linear-gradient(135deg, #4285F4, #3367D6);
}

.btn-scholar:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

/* Centered Research Section */
.research-section {
  background: white;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  margin-top: 1.5rem;
  text-align: center;
}

.research-section h3 {
  color: #2a7ae2;
  margin-top: 0;
  display: inline-flex;
  align-items: center;
  gap: 10px;
  font-size: 1.25rem;
}

.research-section ul {
  list-style-position: inside;
  padding-left: 0;
  margin: 0 auto 1rem;
  display: inline-block;
  text-align: left;
}

.research-section li {
  margin-bottom: 0.5rem;
}

/* Responsive Design */
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
  
  .profile-text h1 {
    font-size: 2rem;
  }
}
</style>

<script>
function copyEmail() {
  const email = 'yangluo@ucsb.edu';
  const tooltip = document.getElementById('emailTooltip');
  
  if (navigator.clipboard) {
    navigator.clipboard.writeText(email)
      .then(() => {
        tooltip.textContent = 'Copied to clipboard!';
        setTimeout(() => {
          tooltip.textContent = 'Click to copy yangluo@ucsb.edu';
        }, 2000);
      })
      .catch(() => {
        fallbackEmail();
      });
  } else {
    fallbackEmail();
  }
  
  function fallbackEmail() {
    const textarea = document.createElement('textarea');
    textarea.value = email;
    textarea.style.position = 'fixed';
    document.body.appendChild(textarea);
    textarea.select();
    
    try {
      document.execCommand('copy');
      tooltip.textContent = 'Copied to clipboard!';
    } catch (err) {
      window.location.href = 'mailto:' + email + '?subject=Website Inquiry';
      return;
    }
    
    document.body.removeChild(textarea);
    
    setTimeout(() => {
      tooltip.textContent = 'Click to copy yangluo@ucsb.edu';
    }, 2000);
  }
}
</script>
