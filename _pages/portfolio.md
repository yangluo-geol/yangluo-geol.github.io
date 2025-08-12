---
layout: default
title: "Portfolio"
permalink: /portfolio/
---

<h1>CL images of zircons</h1>

<div class="photo-grid">
  <a href="/assets/images/DP22-CL-015.png" data-lightbox="zircons" data-title="Description 1">
    <img src="/assets/images/DP22-CL-015.png" alt="Description 1">
  </a>
  <a href="/assets/images/DP22-CL-025.png" data-lightbox="zircons" data-title="Description 2">
    <img src="/assets/images/DP22-CL-025.png" alt="Description 2">
  </a>
  <a href="/assets/images/DUIT3-CL-005.png" data-lightbox="zircons" data-title="Description 3">
    <img src="/assets/images/DUIT3-CL-005.png" alt="Description 3">
  </a>
  <a href="/assets/images/DUIT3-CL-008.png" data-lightbox="zircons" data-title="Description 4">
    <img src="/assets/images/DUIT3-CL-008.png" alt="Description 4">
  </a>
</div>

<h1>Field images</h1>

<div class="photo-grid">
  <a href="/assets/images/field1.jpg" data-lightbox="field" data-title="Field Image 1">
    <img src="/assets/images/field1.jpg" alt="Field Image 1">
  </a>
  <a href="/assets/images/field2.jpg" data-lightbox="field" data-title="Field Image 2">
    <img src="/assets/images/field2.jpg" alt="Field Image 2">
  </a>
  <a href="/assets/images/field3.jpg" data-lightbox="field" data-title="Field Image 3">
    <img src="/assets/images/field3.jpg" alt="Field Image 3">
  </a>
  <a href="/assets/images/field4.jpg" data-lightbox="field" data-title="Field Image 4">
    <img src="/assets/images/field4.jpg" alt="Field Image 4">
  </a>
</div>

<style>
h1 {
  text-align: center;
  margin-bottom: 1rem;
}

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
