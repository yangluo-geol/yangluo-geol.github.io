---
title: "Zircon Cathodoluminescence Imaging"
layout: single
permalink: /projects/
---

<script>
// Debugging tool - will show in browser console (F12)
function verifyImages() {
  const images = [
    '/images/projects/EBA1-CL-007.png',
    '/images/projects/EBA1-CL-015.png',
    '/images/projects/DP22-CL-015.png',
    '/images/projects/DP22-CL-025.png',
    '/images/projects/DUIT3-CL-005.png',
    '/images/projects/DUIT3-CL-008.png'
  ];
  
  console.log('=== Image Verification ===');
  images.forEach(img => {
    const testImg = new Image();
    testImg.onload = () => console.log(`✓ ${img} exists`);
    testImg.onerror = () => console.log(`✗ ${img} MISSING`);
    testImg.src = img;
  });
}
document.addEventListener('DOMContentLoaded', verifyImages);
</script>

<style>
.image-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 20px;
  margin: 30px 0;
}
.zircon-img {
  width: 100%;
  border: 1px solid #eaeaea;
  padding: 5px;
  background: white;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}
.debug-info {
  background: #f8f9fa;
  padding: 15px;
  border-radius: 4px;
  margin: 20px 0;
  font-family: monospace;
}
</style>

## Zircon CL Image Gallery

### Sample EBA1
<div class="image-grid">
  <img src="/images/projects/EBA1-CL-007.png" 
       class="zircon-img" 
       alt="EBA1 Zircon CL 007"
       onerror="this.src='/assets/images/image-error.png'">
  
  <img src="/images/projects/EBA1-CL-015.png" 
       class="zircon-img" 
       alt="EBA1 Zircon CL 015"
       onerror="this.src='/assets/images/image-error.png'">
</div>

### Sample DP22
<div class="image-grid">
  <img src="/images/projects/DP22-CL-015.png" 
       class="zircon-img" 
       alt="DP22 Zircon CL 015"
       onerror="this.src='/assets/images/image-error.png'">
  
  <img src="/images/projects/DP22-CL-025.png" 
       class="zircon-img" 
       alt="DP22 Zircon CL 025"
       onerror="this.src='/assets/images/image-error.png'">
</div>

### Sample DUIT3
<div class="image-grid">
  <img src="/images/projects/DUIT3-CL-005.png" 
       class="zircon-img" 
       alt="DUIT3 Zircon CL 005"
       onerror="this.src='/assets/images/image-error.png'">
  
  <img src="/images/projects/DUIT3-CL-008.png" 
       class="zircon-img" 
       alt="DUIT3 Zircon CL 008"
       onerror="this.src='/assets/images/image-error.png'">
</div>

<div class="debug-info">
  <strong>Troubleshooting:</strong>
  <ol>
    <li>Press <kbd>F12</kbd> → Console to see image verification results</li>
    <li>Check exact filenames match (case-sensitive)</li>
    <li>Images must be in <code>/images/projects/</code> folder</li>
    <li>Wait 2 minutes after uploading new images</li>
  </ol>
</div>
