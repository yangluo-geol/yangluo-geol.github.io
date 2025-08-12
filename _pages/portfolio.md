---
layout: default
title: "Portfolio"
permalink: /portfolio/
---

<h1>Photography Portfolio</h1>

<div class="photo-grid">
  <img src="/assets/images/portfolio/photo1.jpg" alt="Description 1">
  <img src="/assets/images/portfolio/photo2.jpg" alt="Description 2">
  <img src="/assets/images/portfolio/photo3.jpg" alt="Description 3">
  <img src="/assets/images/portfolio/photo4.jpg" alt="Description 4">
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
