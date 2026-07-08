---
layout: page
title: CV
permalink: /cv/
nav: true
nav_order: 2
---

<div class="cv-link-container" style="margin: 30px 0; text-align: center;">
    <p style="font-size: 1.1rem; margin-bottom: 15px;">
        My comprehensive CV is available as a print-ready PDF document.
    </p>
    <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}" 
       target="_blank" 
       rel="noopener noreferrer" 
       class="btn btn-primary" 
       style="padding: 10px 24px; font-size: 1rem; border-radius: 6px; text-decoration: none; display: inline-inline-block;">
       <i class="bi bi-file-earmark-pdf" style="margin-right: 8px;"></i> View Full CV Document
    </a>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    var navbar = document.getElementById("navbar");
    if (navbar) {
      // 1. Swap breakpoints to protect tablet viewports
      navbar.classList.remove("navbar-expand-sm");
      navbar.classList.add("navbar-expand-lg");
      
      // 2. Fix potential desktop visibility blocking issues
      // Forces horizontal row items to explicitly display on large viewports
      var navbarNav = navbar.querySelector(".navbar-nav");
      if (navbarNav) {
        navbarNav.classList.add("flex-lg-row");
      }
    }

    // 3. Automatically inject a clean hamburger logo if it's currently an empty box
    var togglerButton = document.querySelector(".navbar-toggler");
    if (togglerButton) {
      // Check if it's empty or doesn't have the icon class yet
      if (!togglerButton.querySelector(".navbar-toggler-icon")) {
        // Clear whatever broken or empty container is there and insert the native icon
        togglerButton.innerHTML = '<span class="navbar-toggler-icon"></span>';
      }
    }
  });
</script>
