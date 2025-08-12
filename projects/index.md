---
title: "Zircon Cathodoluminescence Imaging"
layout: single
permalink: /projects/
---

<!-- Debugging Script -->
<script>
// Will show image status in console (F12)
document.addEventListener('DOMContentLoaded', function() {
  console.log('=== IMAGE VERIFICATION ===');
  document.querySelectorAll('.zircon-img').forEach(img => {
    const test = new Image();
    test.onload = () => console.log(`✓ Loaded: ${img.dataset.src}`);
    test.onerror = () => console.log(`❌ Failed: ${img.dataset.src}`);
    test.src = img.dataset.src;
  });
});
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
    border: 2px solid #3498db;
    background: white;
    padding: 5px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.1);
  }
  .debug-box {
    background: #f8f9fa;
    border: 1px solid #e1e4e8;
    padding: 15px;
    margin: 20px 0;
    font-family: monospace;
  }
</style>

## Zircon CL Image Gallery

<div class="image-grid">
  <!-- EBA1 Images -->
  <div>
    <h3>EBA1-007</h3>
    <img class="zircon-img" 
         data-src="/images/projects/EBA1-CL-007.png"
         src="/images/projects/EBA1-CL-007.png"
         onerror="this.src='https://placehold.co/600x400?text=Image+Not+Found'"
         alt="EBA1 Zircon CL 007">
  </div>
  <div>
    <h3>EBA1-015</h3>
    <img class="zircon-img" 
         data-src="/images/projects/EBA1-CL-015.png"
         src="/images/projects/EBA1-CL-015.png"
         onerror="this.src='https://placehold.co/600x400?text=Image+Not+Found'"
         alt="EBA1 Zircon CL 015">
  </div>
</div>

<div class="image-grid">
  <!-- DP22 Images -->
  <div>
    <h3>DP22-015</h3>
    <img class="zircon-img" 
         data-src="/images/projects/DP22-CL-015.png"
         src="/images/projects/DP22-CL-015.png"
         onerror="this.src='https://placehold.co/600x400?text=Image+Not+Found'"
         alt="DP22 Zircon CL 015">
  </div>
  <div>
    <h3>DP22-025</h3>
    <img class="zircon-img" 
         data-src="/images/projects/DP22-CL-025.png"
         src="/images/projects/DP22-CL-025.png"
         onerror="this.src='https://placehold.co/600x400?text=Image+Not+Found'"
         alt="DP22 Zircon CL 025">
  </div>
</div>

<div class="image-grid">
  <!-- DUIT3 Images -->
  <div>
    <h3>DUIT3-005</h3>
    <img class="zircon-img" 
         data-src="/images/projects/DUIT3-CL-005.png"
         src="/images/projects/DUIT3-CL-005.png"
         onerror="this.src='https://placehold.co/600x400?text=Image+Not+Found'"
         alt="DUIT3 Zircon CL 005">
  </div>
  <div>
    <h3>DUIT3-008</h3>
    <img class="zircon-img" 
         data-src="/images/projects/DUIT3-CL-008.png"
         src="/images/projects/DUIT3-CL-008.png"
         onerror="this.src='https://placehold.co/600x400?text=Image+Not+Found'"
         alt="DUIT3 Zircon CL 008">
  </div>
</div>

<div class="debug-box">
  <strong>TROUBLESHOOTING GUIDE:</strong>
  <ol>
    <li>Press <kbd>F12</kbd> → Console to see which images load</li>
    <li>Test these direct URLs (replace FILENAME):
      <ul>
        <li><code>https://yangluo-geol.github.io/images/projects/FILENAME.png</code></li>
        <li><code>https://raw.githubusercontent.com/yangluo-geol/yangluo-geol.github.io/main/images/projects/FILENAME.png</code></li>
      </ul>
    </li>
    <li>Verify filenames match exactly (case-sensitive)</li>
    <li>Clear browser cache (Ctrl+Shift+Delete)</li>
  </ol>
</div>
