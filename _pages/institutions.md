---
layout: page
title: Institutions
permalink: /institutions/
---

<div style="text-align: center; margin-bottom: 40px; margin-top: 10px;">
    <h1 style="font-size: 32px; font-weight: bold; color: #1f3b73; margin-bottom: 5px;">Research Statement</h1>
    <p style="font-size: 18px; font-style: italic; color: #222222; margin: 0;">Giorgi Chavchanidze</p>
</div>

<p style="text-align: justify; font-size: 16.5px; line-height: 1.75; color: #222222; margin-bottom: 20px;">
    CERGE-EI <a href="https://www.cerge-ei.cz/governance/executive-and-supervisory-committee" target="_blank" rel="noopener noreferrer"> Executive and Supervisory Committee </a> includes 3 Nobel laureates in Economics.
</p>

<p style="text-align: justify; font-size: 16.5px; line-height: 1.75; color: #222222; margin-bottom: 20px;">
    To capture these latent variations, I introduce an empirical tracking framework designed to mitigate high-dimensional structural data distortions. Unlike traditional aggregates, this baseline implementation retains granular behavioral signals without risking model over-fitting. Full technical equations are covered in my active <a href="/projects/" style="color: #1f3b73; font-weight: bold; text-decoration: underline;">Working Projects Registry</a>.
</p>

<p style="text-align: justify; font-size: 16.5px; line-height: 1.75; color: #222222; margin-bottom: 20px;">
    A significant portion of my current portfolio operationalizes these optimization parameters against high-frequency datasets spanning a multi-year horizon. This stream isolates clear friction patterns within distribution networks. For supplementary reading, feel free to visit the external <a href="https://google.com" target="_blank" rel="noopener noreferrer" style="color: #1f3b73; font-weight: bold; text-decoration: underline;">Research Database Gateway</a>.
</p>

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
