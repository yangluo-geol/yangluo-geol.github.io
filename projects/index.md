---
title: "Zircon Image Diagnostic Test"
layout: single
permalink: /projects/
---

<div style="border: 3px solid red; padding: 20px; background: #fff9f9; margin: 30px 0;">

## 🔬 IMAGE LOADING TEST

### Testing Method
We'll attempt to load your images through 5 different methods. At least one MUST work if your files exist.

```html
<!-- Method 1: Direct GitHub Pages URL -->
<img src="/images/projects/EBA1-CL-007.png" 
     style="width:300px; border:2px solid blue; margin:10px;"
     onerror="console.error('Method 1 failed')">

<!-- Method 2: Raw GitHub URL -->
<img src="https://raw.githubusercontent.com/yangluo-geol/yangluo-geol.github.io/master/images/projects/EBA1-CL-007.png"
     style="width:300px; border:2px solid green; margin:10px;"
     onerror="console.error('Method 2 failed')">

<!-- Method 3: GitHub Pages absolute URL -->
<img src="https://yangluo-geol.github.io/images/projects/EBA1-CL-007.png"
     style="width:300px; border:2px solid orange; margin:10px;"
     onerror="console.error('Method 3 failed')">

<!-- Method 4: Base64 encoded test image (control) -->
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAADUlEQVR42mP8z/C/HgAGgwJ/lK3Q6wAAAABJRU5ErkJggg=="
     style="width:300px; border:2px solid purple; margin:10px;"
     onerror="console.error('Method 4 failed (this is BAD)')">

<!-- Method 5: Iframe fallback -->
<iframe src="https://yangluo-geol.github.io/images/projects/EBA1-CL-007.png"
        style="width:300px; height:300px; border:2px dashed red; margin:10px;">
</iframe>
