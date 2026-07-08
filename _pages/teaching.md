---
layout: page
title: Teaching
permalink: /teaching/
nav: true
nav_order: 4
---

<div class="courses-container">
  
  <div class="course-item">
    <h3 class="course-title">ECON 101: Introduction to Microeconomics</h3>
    <div class="course-metadata">
      <span class="meta-institution">Harvard University</span> &middot; 
      <span class="meta-role">Instructor of Record</span> &middot; 
      <span class="meta-duration">4 Semesters</span>
    </div>
    <div class="course-description">
      <p>This course introduces students to the fundamental principles of microeconomic theory, including consumer behavior, firm production dynamics, market structures, and public policy interventions. Emphasizes real-world applications and quantitative problem-solving tools.</p>
    </div>
  </div>

  <div class="course-item">
    <h3 class="course-title">STAT 210: Probability for Quantitative Interviews</h3>
    <div class="course-metadata">
      <span class="meta-institution">Stanford University</span> &middot; 
      <span class="meta-role">Graduate Teaching Assistant</span> &middot; 
      <span class="meta-duration">2 Semesters</span>
    </div>
    <div class="course-description">
      <p>A rigorous, seminar-style review of stochastic processes, conditional probability, and combinatorial analysis. Tailored specifically for advanced undergraduates preparing for quantitative research and engineering tracks.</p>
    </div>
  </div>

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

