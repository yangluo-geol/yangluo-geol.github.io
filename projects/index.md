---
title: "Zircon Cathodoluminescence Imaging"
layout: single
permalink: /projects/
---

<div style="border: 3px solid #e74c3c; padding: 20px; background: #f9f9f9; margin-bottom: 30px;">
  <h2>Image Loading Test</h2>
  <p>Testing all image display methods simultaneously. At least one <strong>must</strong> work if files exist.</p>
</div>

## Sample EBA1

### Method 1: GitHub Pages Direct
<img src="https://yangluo-geol.github.io/assets/images/projects/EBA1-CL-007.png" 
     style="max-width: 500px; border: 3px solid blue; margin: 20px 0;"
     onerror="this.parentElement.innerHTML += '<div style=color:red>❌ Method 1 failed</div>'">

### Method 2: Raw GitHub URL
<img src="https://raw.githubusercontent.com/yangluo-geol/yangluo-geol.github.io/master/assets/images/projects/EBA1-CL-007.png"
     style="max-width: 500px; border: 3px solid green; margin: 20px 0;"
     onerror="this.parentElement.innerHTML += '<div style=color:red>❌ Method 2 failed</div>'">

### Method 3: Base64 Fallback
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR42mP8z/C/HgAGgwJ/lK3Q6wAAAABJRU5ErkJggg=="
     style="max-width: 500px; border: 3px solid purple; margin: 20px 0;"
     onerror="this.parentElement.innerHTML += '<div style=color:red>❌ Method 3 failed (THIS IS BAD)'">

<div style="background: #f0f8ff; padding: 15px; margin: 30px 0; border-left: 5px solid #4682b4;">
  <h3>Verification Steps</h3>
  <ol>
    <li>Right-click each image → "Open image in new tab"</li>
    <li>Test these direct URLs:
      <ul>
        <li><a href="https://yangluo-geol.github.io/assets/images/projects/EBA1-CL-007.png" target="_blank">GitHub Pages URL</a></li>
        <li><a href="https://raw.githubusercontent.com/yangluo-geol/yangluo-geol.github.io/master/assets/images/projects/EBA1-CL-007.png" target="_blank">Raw GitHub URL</a></li>
      </ul>
    </li>
    <li>Check console for errors (F12 → Console)</li>
  </ol>
</div>
