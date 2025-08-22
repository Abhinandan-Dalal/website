---
layout: about
title: "About me"
math: true
hide_title: true
---


<!-- Wrap your content in a container div -->
<div class="content-container">

  <div class="text-container">
  <!-- Add your text inside a paragraph -->
  <p>
  
  I'm Anirban, a Ph.D. candidate in Statistics at [The Wharton School](https://www.wharton.upenn.edu/), [University of Pennsylvania](https://www.upenn.edu/) advised by [Prof. Bhaswar B. Bhattacharya](http://www-stat.wharton.upenn.edu/~bhaswar/index.html). Before joining here, I earned both my Bachelor of Statistics and Master of Statistics at the [Indian Statistical Institute, Kolkata](https://www.isical.ac.in/). These formative years equipped me with a strong mathematical foundation to explore the depths of statistical theory and its real-world applications. 
  
  My research is primarily focused on exploring and understanding connections between non-parametric statistical inference, network models and nearest-neighbor methods. Furthermore, my interests span across different domains, including but not limited to differential privacy, distribution-free inference, and random-matrix theory. My current publications and preprints can be found [here.](https://anirbanc96.github.io/anirban/research/)


  </p>
  </div>
    <!-- Add the image and give it a class for styling -->
  <img class="side-image" src="/images/mountains.jpeg" alt="" />

</div>

<!-- Add a style tag with CSS to control the layout -->
<style>
  .content-container {
    display: flex;
    align-items: flex-start;
  }
  .text-container {
    flex-grow: 1;
  }

  .side-image {
    margin-top: 50px;
    margin-left: 20px; /* Adjust the space between the image and the text */
    max-width: 40%; /* Adjust the width of the image */
    border-radius: 2%; /* Make the image circular */
    overflow: hidden; /* Hide anything outside of the circle */
  }

  /* Responsive design for smaller screens */
  @media (max-width: 768px) {
    .side-image {
      max-width: 100%;
      margin-left: 0;
      margin-bottom: 20px;
    }

    .content-container {
      flex-direction: column;
    }
  }
</style>
