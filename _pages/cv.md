---
layout: page
title: CV
permalink: /cv/
nav: true
nav_order: 2
---

<div class="cv-embed-container">
    <iframe src="{{ '/assets/pdf/cv.pdf' | relative_url }}" width="100%" height="900px" style="border: none; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.08);">
        <p>Your browser does not support embedding PDFs. 
           <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}" class="button btn-primary">Download </a> the CV Document instead.
        </p>
    </iframe>
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
