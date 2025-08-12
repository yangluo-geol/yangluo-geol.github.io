---
title: "Zircon CL Images"
layout: single
permalink: /projects/
---

<script>
// LIVE IMAGE VERIFIER
document.addEventListener('DOMContentLoaded', function() {
  const images = [
    '/images/projects/EBA1-CL-007.png',
    '/images/projects/EBA1-CL-015.png',
    '/images/projects/DP22-CL-015.png',
    '/images/projects/DP22-CL-025.png',
    '/images/projects/DUIT3-CL-005.png',
    '/images/projects/DUIT3-CL-008.png'
  ];

  // 1. Verify images exist
  console.log('=== IMAGE VERIFICATION ===');
  images.forEach(url => {
    const img = new Image();
    img.onload = () => console.log(`✓ ${url} EXISTS`);
    img.onerror = () => console.log(`❌ ${url} MISSING (404)`);
    img.src = url;
  });

  // 2. Force display with cache busting
  document.querySelectorAll('img').forEach(img => {
    img.src = img.dataset.rawSrc + '?t=' + Date.now();
  });
});
</script>

<style>
/* Irresistible styling */
.zircon-container {
  border: 3px solid #e74c3c !important;
  padding: 20px !important;
  background: #f9f9f9 !important;
}
.zircon-img {
  max-width: 100% !important;
  height: auto !important;
  border: 2px solid #3498db !important;
  margin: 10px 0 !important;
  box-shadow: 0 0 10px rgba(0,0,0,0.1) !important;
}
.debug {
  background: #ffecb3 !important;
  padding: 15px !important;
  font-family: monospace !important;
}
</style>

<div class="zircon-container">
  <h2>ZIRCON IMAGE FORCE-DISPLAY</h2>
  
  <!-- EBA1 -->
  <h3>EBA1 Samples</h3>
  <img data-raw-src="/images/projects/EBA1-CL-007.png" 
       class="zircon-img" 
       alt="EBA1-007" 
       onerror="this.style.display='none'">
  <img data-raw-src="/images/projects/EBA1-CL-015.png" 
       class="zircon-img" 
       alt="EBA1-015" 
       onerror="this.style.display='none'">

  <!-- DP22 -->
  <h3>DP22 Samples</h3>
  <img data-raw-src="/images/projects/DP22-CL-015.png" 
       class="zircon-img" 
       alt="DP22-015" 
       onerror="this.style.display='none'">
  <img data-raw-src="/images/projects/DP22-CL-025.png" 
       class="zircon-img" 
       alt="DP22-025" 
       onerror="this.style.display='none'">

  <!-- DUIT3 -->
  <h3>DUIT3 Samples</h3>
  <img data-raw-src="/images/projects/DUIT3-CL-005.png" 
       class="zircon-img" 
       alt="DUIT3-005" 
       onerror="this.style.display='none'">
  <img data-raw-src="/images/projects/DUIT3-CL-008.png" 
       class="zircon-img" 
       alt="DUIT3-008" 
       onerror="this.style.display='none'">

  <div class="debug">
    <strong>TROUBLESHOOTING:</strong>
    <ol>
      <li>Press F12 → Console to see which images fail</li>
      <li>Verify files exist at:
        <code>https://yangluo-geol.github.io/images/projects/FILENAME.png</code>
      </li>
      <li>Check filenames are EXACT (case-sensitive)</li>
      <li>Disable ad-blockers/extensions</li>
    </ol>
  </div>
</div>
