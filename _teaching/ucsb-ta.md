---
title: "Teaching Assistant - Earth Science Department"
collection: teaching
type: "Undergraduate Course Instruction"
permalink: /teaching/2024-2025-ucsb-ta
venue: "University of California, Santa Barbara, Department of Earth Science"
date: 2024-09-22
daterange: "September 2024 - Present"
location: "Santa Barbara, California"
course_list:
  - code: "Earth 114"
    name: "Geomaterials"
    term: "Fall 2024"
    skills: ["Optical mineralogy", "Crystallography", "Thin section analysis"]
  - code: "Earth 103"
    name: "Structural Geology"
    term: "Winter 2025" 
    skills: ["Stereonet analysis", "Field mapping", "Stress/strain modeling"]
  - code: "Earth 161"
    name: "Earth Resources, Energy and Environment"
    term: "Spring 2025"
    skills: ["Resource evaluation", "Sustainability analysis", "Geochemical data interpretation"]
  - code: "Earth 20"
    name: "Geological Catastrophes"
    term: "Summer 2025"
    skills: ["Hazard assessment", "Risk modeling", "Emergency preparedness"]
---

## Teaching Assistant Experience

### Course Instruction
{% for course in page.course_list %}
- **{{ course.term }}:** {{ course.code }} — *{{ course.name }}*  
  {% if course.skills %}
  <span class="course-skills">Skills emphasized: {{ course.skills | join: ", " }}</span>
  {% endif %}
{% endfor %}

### Key Responsibilities
- Designed and led weekly laboratory sessions for 20-30 undergraduate students
- Developed instructional materials including:
  - Mineral identification flow charts
  - Structural geology problem sets
  - Resource evaluation case studies
- Conducted office hours and provided individualized academic support
- Evaluated and provided feedback on:
  - Laboratory reports (15-20 pages each)
  - Field mapping exercises
  - Final research projects
- Assisted faculty with course development and curriculum improvements

### Teaching Philosophy
My approach emphasizes:
- Hands-on, experiential learning in laboratory and field settings
- Integrating current research into undergraduate curriculum
- Developing quantitative and analytical skills through geoscience applications
- Fostering inclusive learning environments

<style>
.course-skills {
    display: block;
    font-size: 0.85em;
    color: #555;
    margin-left: 2em;
    margin-top: 0.25em;
    font-style: italic;
}
</style>

