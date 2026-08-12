---
layout: page
title: Probability for Quant Interviews
permalink: /probability/
images:
  lightbox2: true # Enable lightbox for this page
---

<div class="page-container container">
  <header class="faq-header">
    <!-- Photo Container moved inside the header -->
    <div class="book-gallery-container mb-4">
      <!-- Main clickable image to open the gallery -->
      <a href="/assets/img/probability_book/Quant Prep Book Cover.png" data-lightbox="book-gallery">
        <img src="/assets/img/probability_book/Quant Prep Book Cover.png" class="img-fluid rounded z-depth-1 main-gallery-image-constrained">
      </a>
      <!-- Small thumbnails displayed below the main image 
      <div class="gallery-thumbnails mt-3 d-flex justify-content-center">
        <a href="/assets/img/probability_book/contents_2.png" data-lightbox="book-gallery">
          <img src="/assets/img/probability_book/contents_2.png" class="img-thumbnail me-2" style="width: 80px; height: auto;">
        </a>
        <a href="/assets/img/probability_book/contents_1.png" data-lightbox="book-gallery">
          <img src="/assets/img/probability_book/contents_1.png" class="img-thumbnail" style="width: 80px; height: auto;">
        </a>
      </div>
      -->
      <!-- Hidden links for other images in the gallery (if the main image is also part of the gallery) 
      <a href="/assets/img/probability_book/book_toc.png" data-lightbox="book-gallery" class="d-none"></a> -->
    </div>
  </header>

  <div class="author-redirect-box" style="margin-bottom: 0.8rem;">
    <a href="/" class="about-author-link">
      About the Author <i class="bi bi-arrow-right-short"></i>
    </a>
  </div>

  <div class="faq-accordion-wrapper">
    <details class="faq-item">
      <summary class="faq-question">
        What This Book is About
        <span class="faq-icon-toggle"></span>
      </summary>
      <div class="faq-answer">
        <p style="text-align: justify; font-size: 18px; line-height: 1.75; color: #222222;">
          The book develops Probability Theory around the types of problems asked in Quantitative Finance probability interviews and assessments. You can think of it as a high-quality Probability textbook that <br>
          1) is stripped of Probability material unlikely to be relevant for interviews, <br>
          2) serves as a single consolidated space for all interview-relevant concepts a reader can get back to at their convenience, <br>
          3) relies on mathematical formalism while always translating key insights to intuitive English, and <br>
          4) offers generalized discussion of problem-solving tricks and techniques.
        </p>
      </div>
    </details>
    <details class="faq-item">
      <summary class="faq-question">
        Who This Book is For
        <span class="faq-icon-toggle"></span>
      </summary>
      <div class="faq-answer">
        <p style="text-align: justify; font-size: 18px; line-height: 1.75; color: #222222;">
          While primarily targeted at the individuals preparing for Quantitative Finance Probability assessments and interviews (see "What This Book is About" section), the book is useful for anyone looking for a quick and intuitive introduction to a wide range of probability concepts. It will also help undergraduate and graduate students who might find standard textbook language too formal and unintuitive. 
        </p>
      </div>
    </details>
    <details class="faq-item">
      <summary class="faq-question">
        More Than a Book
        <span class="faq-icon-toggle"></span>
      </summary>
      <div class="faq-answer">
        <p style="text-align: justify; font-size: 18px; line-height: 1.75; color: #222222;">
          A buyer of the book does not simply get access to an electronic copy of the book. They also get access to all future updates and an ability to interact with the author and ask any clarifying questions. Hence, buyers get a lifetime subscription to a dynamic resource rather than a static copy of a book. <br><br>
          Readers are welcome to request content additions or solutions to specific problems they find challenging. I strive to respond to all such requests as soon as time allows.
        </p>
      </div>
    </details>
    <details class="faq-item">
      <summary class="faq-question">
        Reading Experience
        <span class="faq-icon-toggle"></span>
      </summary>
      <div class="faq-answer">
        <p style="text-align: justify; font-size: 18px; line-height: 1.75; color: #222222;">
          The book can be accessed on any device using any modern browser with a built-in PDF reader, and it comes with clickable links for easy navigation to and from sections and equations.
        </p>
      </div>
    </details>
    <details class="faq-item">
      <summary class="faq-question">
        Institutional Disclaimer
        <span class="faq-icon-toggle"></span>
      </summary>
      <div class="faq-answer">
        <p style="text-align: justify; font-size: 18px; line-height: 1.75; color: #222222;">
          The book is an independent work and is not associated with any of my current or former institutions.
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
