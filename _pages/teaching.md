---
layout: page
title: Teaching
permalink: /teaching/
nav: true
nav_order: 4
---

<div class="teaching-page-wrapper">
  
  <div class="page-header-block">
    <h1 class="page-main-title">Teaching</h1>
    <div class="header-accent-bar"></div>
  </div>

  <div class="teaching-intro-note">
    <p>You can read about my teaching philosophy <a href="https://github.com/" target="_blank" rel="noopener noreferrer" class="custom-link">here</a>.</p>
  </div>

  <h2 class="section-courses-title">Courses</h2>

  <div class="courses-container">
    
    <div class="course-item">
      <h3 class="course-title">MFIN 1021: Fundamentals of Finance</h3>
      <div class="course-metadata">
        <span class="meta-institution">Boston College</span>
        <span class="meta-separator">&middot;</span>
        <span class="meta-role">Teaching Assistant</span>
        <span class="meta-separator">&middot;</span>
        <span class="meta-duration">2 Semesters</span>
        <span class="meta-separator">&middot;</span>
        <span class="meta-duration">100-150 students per Semester</span>
      </div>
      <div class="course-description">
        <p>The course covers fundamental topics in finance, such as Time Value of Money, Inflation, Retirement, Bond Valuation, Financial Statements and Ratios, Capital Budgeting (with Risk and Taxes), Scenario Analysis, Risk and Return, CAPM and Beta, Stock Valuation and Efficient Markets Hypothesis.</p>
      </div>
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

