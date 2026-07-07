---
layout: page
title: Institutions
permalink: /institutions/
---

<div style="text-align: left; margin-bottom: 40px; margin-top: 10px;">
    <h1 style="font-size: 32px; font-weight: bold; color: #1f3b73; margin-bottom: 5px;"> About Affiliated Institutions </h1>

<div style="height: 30px; clear: both;"></div>

<div style="border-left: 3px solid #1f3b73; padding-left: 25px; margin-left: 2.5px;">

    <p style="text-align: justify; font-size: 18px; line-height: 1.75; color: #222222; margin-bottom: 20px;">
        CERGE-EI <a href="https://www.cerge-ei.cz/governance/executive-and-supervisory-committee" target="_blank" rel="noopener noreferrer" style="color: #1f3b73; font-weight: bold; text-decoration: underline;">Executive and Supervisory Committee</a> includes 3 Nobel laureates in Economics.
    </p>
    
    <p style="text-align: justify; font-size: 18px; line-height: 1.75; color: #222222; margin-bottom: 20px;">
        Boston College has been consistently ranked by <a href="https://www.shanghairanking.com/rankings/gras/2025/AS0510" target="_blank" rel="noopener noreferrer" style="color: #1f3b73; font-weight: bold; text-decoration: underline;">Shanghai Academic Rankings</a> among Top-10/Top-20 academic research institions in Finance in recent years.
    </p>
    
    <p style="text-align: justify; font-size: 18px; line-height: 1.75; color: #222222; margin-bottom: 20px;">
        EDHEC is particularly strong at the intersection of academic and industry research and its Master's Program in Finance has been consistenly ranked among Top-5/Top-10 globally by <a href="https://rankings.ft.com/rankings/3045/masters-in-finance-pre-experience-2026" target="_blank" rel="noopener noreferrer" style="color: #1f3b73; font-weight: bold; text-decoration: underline;">Financial Times</a> in recent years. 
    </p>

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
