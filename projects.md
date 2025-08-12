---
layout: default
title: "Projects"
permalink: /projects/
---

<h1>Research Projects</h1>

<div class="projects-grid">
{% for project in site.projects reversed %}
  <div class="project-card">
    <a href="{{ project.url | relative_url }}">
      <img src="{{ project.image | relative_url }}" alt="{{ project.title }}">
      <h2>{{ project.title }}</h2>
    </a>
    <p class="meta">
      {{ project.location }} • {{ project.age }}
    </p>
    <p>{{ project.summary }}</p>
  </div>
{% endfor %}
</div>

<style>
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}
.project-card {
  background: #fff;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}
.project-card:hover {
  transform: translateY(-5px);
}
.project-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}
.project-card h2 {
  font-size: 1.2rem;
  margin: 0.5rem;
}
.project-card .meta {
  font-size: 0.9rem;
  color: #666;
  margin: 0 0.5rem;
}
.project-card p {
  font-size: 0.95rem;
  padding: 0 0.5rem 0.8rem;
}
</style>
