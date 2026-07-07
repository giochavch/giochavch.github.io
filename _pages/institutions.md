---
layout: page
title: Institutions
permalink: /institutions/
---

<div class="content-section-header">
    <h2>Research Overview & Focus</h2>
    <span class="header-line"></span>
</div>

<p class="lead-text">
    This page outlines my primary academic research focus, ongoing working papers, and core methodological frameworks. My work lies at the intersection of quantitative analysis, economic theory, and system optimization.
</p>

<div class="content-row">
    <div class="content-column">
        <h3>Core Methodology</h3>
        <p>Utilizing high-dimensional empirical tracking alongside structural optimization vectors to evaluate network efficiency under localized volatility constraints.</p>
    </div>
    <div class="content-column">
        <h3>Primary Datasets</h3>
        <p>Primary data collection spans cross-sectional institutional registers from 2018–2026, matched with granular high-frequency transactional feeds.</p>
    </div>
</div>

<blockquote class="academic-quote">
    <p>"By re-centering structural parameters within local distribution models, we capture latent market anomalies previously obscured by broad aggregations."</p>
    <cite>— Main Thesis Framework, Chapter 2</cite>
</blockquote>

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
