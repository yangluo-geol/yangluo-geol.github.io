---
title: "Zircon CL Images - Diagnostic Test"
layout: single
permalink: /projects/
---

<div style="border: 3px solid #e74c3c; padding: 20px; background: #f9f9f9; margin: 30px 0;">

## 🔍 IMAGE LOADING TEST

<script>
// Nuclear verification method
document.addEventListener('DOMContentLoaded', function() {
  const images = [
    '/images/projects/EBA1-CL-007.png',
    '/images/projects/EBA1-CL-015.png',
    '/images/projects/DP22-CL-015.png',
    '/images/projects/DP22-CL-025.png',
    '/images/projects/DUIT3-CL-005.png',
    '/images/projects/DUIT3-CL-008.png'
  ];

  // 1. Console verification
  console.log('=== IMAGE VERIFICATION ===');
  images.forEach(url => {
    const img = new Image();
    img.onload = () => console.log(`✓ ${url} LOADED`);
    img.onerror = () => console.log(`❌ ${url} FAILED (404)`);
    img.src = url + '?t=' + Date.now(); // Cache busting
  });

  // 2. Force display with multiple fallbacks
  const container = document.getElementById('image-test');
  images.forEach(url => {
    // Method 1: Direct img tag
    container.innerHTML += `
    <div style="margin: 20px 0; padding: 10px; background: white;">
      <h3>Testing: ${url.split('/').pop()}</h3>
      <strong>Method 1:</strong> Direct image tag<br>
      <img src="${url}" style="max-width: 300px; border: 2px solid blue; margin: 10px 0;" 
           onerror="this.parentNode.innerHTML += '<span style=color:red>❌ FAILED</span>'">
      
      <div style="margin-top: 10px;">
        <strong>Method 2:</strong> GitHub Raw URL<br>
        <img src="https://raw.githubusercontent.com/yangluo-geol/yangluo-geol.github.io/main${url}" 
             style="max-width: 300px; border: 2px solid green; margin: 10px 0;"
             onerror="this.parentNode.innerHTML += '<span style=color:red>❌ FAILED</span>'">
      </div>
      
      <div style="margin-top: 10px;">
        <strong>Test Links:</strong>
        <a href="${url}" target="_blank">GitHub Pages</a> | 
        <a href="https://raw.githubusercontent.com/yangluo-geol/yangluo-geol.github.io/main${url}" target="_blank">Raw GitHub</a>
      </div>
    </div>
    `;
  });
});
</script>

<div id="image-test"></div>

<div style="background: #ffecb3; padding: 15px; margin-top: 30px;">
  <h3>🚨 TROUBLESHOOTING GUIDE</h3>
  <ol>
    <li><strong>Press F12 → Console</strong> to see verification results</li>
    <li><strong>Click the test links</strong> under each image</li>
    <li>If both methods show ❌:
      <ul>
        <li>Files don't exist at the specified locations</li>
        <li>Repository isn't properly connected to GitHub Pages</li>
      </ul>
    </li>
    <li>If only Method 2 works:
      <ul>
        <li>Your GitHub Pages build is failing</li>
        <li>Try rebuilding: Settings → Pages → Build</li>
      </ul>
    </li>
  </ol>
</div>

</div>
