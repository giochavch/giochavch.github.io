---
layout: page
title: Probability for Quant Interviews
permalink: /probability/
images:
  lightbox2: true # Enable lightbox for this page
---

<div class="page-container container">
  <header class="faq-header">
    <h1 style="text-align: center;">Probability for Quantitative Interviews</h1>
    <!-- Photo Container moved inside the header -->
    <div class="book-gallery-container mb-4">
      <!-- Main clickable image to open the gallery -->
      <a href="/assets/img/probability_book/Quant Prep Book Cover.png" data-lightbox="book-gallery">
        <img src="/assets/img/probability_book/Quant Prep Book Cover.png" class="img-fluid rounded z-depth-1 main-gallery-image" style="max-width: 450px; margin: auto; display: block;">
      </a>
      <!-- Small thumbnails displayed below the main image -->
      <div class="gallery-thumbnails mt-3 d-flex justify-content-center">
        <a href="/assets/img/probability_book/contents_2.png" data-lightbox="book-gallery">
          <img src="/assets/img/probability_book/contents_2.png" class="img-thumbnail me-2" style="width: 80px; height: auto;">
        </a>
        <a href="/assets/img/probability_book/contents_1.png" data-lightbox="book-gallery">
          <img src="/assets/img/probability_book/contents_1.png" class="img-thumbnail" style="width: 80px; height: auto;">
        </a>
      </div>
      <!-- Hidden links for other images in the gallery (if the main image is also part of the gallery) 
      <a href="/assets/img/probability_book/book_toc.png" data-lightbox="book-gallery" class="d-none"></a> -->
    </div>
  </header>

  <div class="author-redirect-box">
    <a href="/" class="about-author-link">
      About the Author <i class="bi bi-arrow-right-short"></i>
    </a>
  </div>

  <div class="faq-accordion-wrapper">
    <details class="faq-item">
      <summary class="faq-question">
        What mathematical prerequisites are required to comfortably follow this text?
        <span class="faq-icon-toggle"></span>
      </summary>
      <div class="faq-answer">
        <p>
          The text assumes a foundational understanding of multivariable calculus and basic linear algebra. Prior exposure to rigorous proofs or real analysis is helpful but not strictly required, as essential measure-theoretic tools are self-contained and introduced gradually.
        </p>
      </div>
    </details>
    <details class="faq-item">
      <summary class="faq-question">
        Is there an open-source repository containing the Python/R simulation code used in the examples?
        <span class="faq-icon-toggle"></span>
      </summary>
      <div class="faq-answer">
        <p>
          Yes, all computational experiments, stochastic process visualizations, and numerical simulations featured in Chapters 4 through 11 are completely open-source. You can access the official code repository via the GitHub link provided in the introductory chapter or contact the author directly for lecture integration assets.
        </p>
      </div>
    </details>
    <details class="faq-item">
      <summary class="faq-question">
        Are solutions available for the end-of-chapter exercises and structural proofs?
        <span class="faq-icon-toggle"></span>
      </summary>
      <div class="faq-answer">
        <p>
          A comprehensive Solutions Manual is available exclusively to verified course instructors and academic faculty members. If you are adopting this text for a university curriculum, please submit an official request through your institutional email.
        </p>
      </div>
    </details>
    <details class="faq-item">
      <summary class="faq-question">
        Will there be a second edition tracking modern machine learning frameworks?
        <span class="faq-icon-toggle"></span>
      </summary>
      <div class="faq-answer">
        <p>
          A revised edition is currently under development. It features expanded sections on high-dimensional probability bounds, concentration inequalities, and applications to statistical learning theory. Stay tuned for structural updates later this academic year.
        </p>
      </div>
    </details>

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
