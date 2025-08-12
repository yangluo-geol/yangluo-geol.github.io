---
layout: default
title: "Portfolio"
permalink: /portfolio/
---

<h1>Photography Portfolio</h1>

<div class="photo-grid">
  <a href="/assets/images/DP22-CL-015.png" target="_blank">
    <img src="/assets/images/DP22-CL-015.png" alt="Description 1">
  </a>
  <a href="/assets/images/DP22-CL-025.png" target="_blank">
    <img src="/assets/images/DP22-CL-025.png" alt="Description 2">
  </a>
  <a href="/assets/images/DUIT3-CL-005.png" target="_blank">
    <img src="/assets/images/DUIT3-CL-005.png" alt="Description 3">
  </a>
  <a href="/assets/images/DP22-CL-008.png" target="_blank">
    <img src="/assets/images/DP22-CL-008.png" alt="Description 4">
  </a>
</div>

<style>
.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1rem;
  margin-top: 1.5rem;
}
.photo-grid img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  transition: transform 0.2s ease;
}
.photo-grid img:hover {
  transform: scale(1.03);
}
</style>
