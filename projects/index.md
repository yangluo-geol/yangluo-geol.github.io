---
title: "Research Projects"
layout: single
permalink: /projects/
---

<script>
// Debugging script that logs image status
document.addEventListener('DOMContentLoaded', function() {
  const images = document.querySelectorAll('img');
  images.forEach(img => {
    // Test if image loads
    img.onload = () => console.log(`✅ Loaded: ${img.src}`);
    img.onerror = () => console.log(`❌ Failed: ${img.src}`);
    
    // Force fresh load (bypass cache)
    img.src = img.src + '?t=' + new Date().getTime();
  });
});
</script>

## Zircon CL Images (Live Test)

### Sample EBA1
<!-- First image with backup option -->
<picture>
  <source srcset="https://yangluo-geol.github.io/images/projects/EBA1-CL-007.png" type="image/png">
  <img src="https://yangluo-geol.github.io/images/projects/EBA1-CL-007.png" 
       width="500" 
       alt="EBA1 Zircon 007"
       style="border:1px solid #ddd;background:white;padding:5px;">
</picture>

<!-- Second image with direct link fallback -->
<a href="https://yangluo-geol.github.io/images/projects/EBA1-CL-015.png" target="_blank">
  <img src="https://yangluo-geol.github.io/images/projects/EBA1-CL-015.png" 
       width="500" 
       alt="EBA1 Zircon 015"
       style="border:1px solid #ddd;background:white;padding:5px;margin-top:10px;">
</a>

### Debugging Instructions:
1. Press **F12 → Console** to see which images load
2. Click any image to open full version in new tab
3. If you see "❌ Failed", check:
   - Exact filename match (case-sensitive)
   - File exists in `/images/projects/`
   - No ad-blockers interfering
</markdown>
