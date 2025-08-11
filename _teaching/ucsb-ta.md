---
title: "Teaching Assistant - Earth Science Department"
collection: teaching
type: "Undergraduate Course Instruction"
permalink: /teaching/ucsb-ta/
venue: "University of California, Santa Barbara, Department of Earth Science"
date: 2024-09-22
daterange: "September 2024 - Present"
venue: "UC Santa Barbara"
course_list:
  - code: "Earth 114"
    name: "Geomaterials"
    term: "Fall 2024"
    main content: ["mineralogy", "Crystallography"]
  - code: "Earth 103"
    name: "Structural Geology"
    term: "Winter 2025" 
    main content: ["Stereonet analysis", "Field data collection", "Stress/strain analysis"]
  - code: "Earth 161"
    name: "Earth Resources, Energy and Environment"
    term: "Spring 2025"
    main content: ["Sustainability analysis", "Geochemical data interpretation"]
  - code: "Earth 20"
    name: "Geological Catastrophes"
    term: "Summer 2025"
    main content: ["plate tectonics, natural hazards, disasters, catastrophes: like earthquake, tsunami, volcanoes and flooding"]
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
- Led weekly laboratory sessions for undergraduate students
- Developed instructional materials
- Conducted office hours
- Graded and provided feedback on:
  - Laboratory reports/assignments
- Assisted faculty with course development and curriculum improvements

### Teaching Philosophy
My approach emphasizes:
- Hands-on, experiential learning in laboratory and field settings
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

