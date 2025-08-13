---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- ===== DOWNLOAD CV LINK ===== -->
<div class="cv-download" style="margin-bottom: 1.5rem;">
  <a href="/assets/files/CV.pdf" download class="btn-download">
    📄 Download My CV
  </a>
</div>

<style>
body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  background: #f8f9fa;
  padding: 2rem;
}

/* Download button style */
.btn-download {
  display: inline-block;
  padding: 0.6rem 1.2rem;
  background-color: #2a7ae2;
  color: white;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
  transition: background 0.2s ease;
}

.btn-download:hover {
  background-color: #1a5bb8;
}

/* CV headings */
h2 {
  color: #2a7ae2;
  font-size: 1.5rem; /* same size for all sections */
  margin-top: 2rem;
  margin-bottom: 0.5rem;
}

ul {
  padding-left: 1.5rem;
  margin: 0.5rem 0 1rem 0;
}

ul ul {
  padding-left: 1.2rem;
}
</style>

<!-- ===== CV CONTENT ===== -->
<section>
  <h2>Education</h2>
  <ul>
    <li>Ph.D. in Geochemistry, University of California, Santa Barbara, 2024-present</li>
    <li>M.S. in Mineralogy, Petrology, Mineral Deposit Geology, University of Chinese Academy of Sciences, 2021-2024</li>
    <li>B.S. in Geology, Chengdu University of Technology, 2016-2020</li>
  </ul>
</section>

<section>
  <h2>Work Experience</h2>
  <ul>
    <li>
      Summer 2020: Research Assistant
      <ul>
        <li>Chengdu University of Technology</li>
        <li>Duties included: Collecting data and writing report</li>
        <li>Supervisor: Professor Xiong</li>
      </ul>
    </li>
  </ul>
</section>

<section>
  <h2>Skills</h2>
  <ul>
    <li>Office software, Adobe Illustrator</li>
    <li>Lab skills:
      <ul>
        <li>Optical microscope</li>
        <li>Scanning Electron Microscope (SEM)</li>
        <li>Electron Microprobe Analysis (EPMA)</li>
        <li>Laser Ablation Inductively Coupled Plasma Mass Spectrometry (LA-ICP-MS)</li>
      </ul>
    </li>
  </ul>
</section>

<section>
  <h2>Publications</h2>
  <ul>
    {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>
</section>

<section>
  <h2>Teaching</h2>
  <ul>
    {% for post in site.teaching reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>
</section>
