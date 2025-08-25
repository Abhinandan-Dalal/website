---
title: 
---

<!-- Icon stylesheets (safe to keep here; remove if your theme already loads them) -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>

<style>
  /* Publication layout (same feel as your research page) */
  .pub { margin: .9rem 0 1.4rem; }
  .pub .title { font-weight: 600; font-size: 1em; }
  .pub .meta { font-size: .9em; opacity: .9; margin-top: .15rem; }

  /* Olive theme */
  :root {
    --olive-color: rgb(102, 153, 51);
  }
  .olive-word { color: var(--olive-color); }

  /* “Simply put” — inline label; body opens below */
  details.simple {
    display: inline;
    margin-left: .6rem;
    color: var(--olive-color);
  }
  details.simple > summary {
    cursor: pointer;
    list-style: none;
    display: inline-flex;
    align-items: center;
    gap: .4rem;
    font-weight: 600;
    font-size: 0.9em;
  }
  details.simple > summary::before {
    content: "▶";
    display: inline-block;
    transform: translateY(1px);
    transition: transform .15s;
  }
  details.simple[open] > summary::before { transform: rotate(90deg); }
  details.simple .body {
    display: block;
    font-size: .9rem;
    line-height: 1.35;
    color: #444;
    margin: .4rem 0 .2rem 1.4rem;
    max-width: 85%;
  }

  .content-container { display: flex; align-items: flex-start; }
  .text-container { flex-grow: 1; }
  .side-image {
    margin-top: 5px;
    margin-left: 30px;
    max-width: 40%;
    border-radius: 2%;
    overflow: hidden;
  }
  @media (max-width: 768px) {
    .side-image {
      max-width: 100%;
      margin-left: 0;
      margin-bottom: 20px;
    }
    .content-container { flex-direction: column; }
  }
</style>

This is a list of some of my older unpublished research. 
They are not peer-reviewed but are shared here for curious minds. 
For my more recent works, please see the 
<a href="/research/">Research</a> section of this site.

<h2 style="color: #556B2F;">Technical Reports</h2>

<div class="pub">
  <div class="title">
    <span style="font-weight: bold;">
      <strong>An endogenous (game-theoretic) approach to explore epidemic dynamics on a network.</strong>
      <a href="https://drive.google.com/file/d/1e69HklrFemK6LzB8KZ_QViD9XuksI7Df/view" aria-label="Google Drive">
        <i class="fab fa-google-drive"></i>
      </a>
      <!-- Optional GitHub icon if you add a repo later
      <a href="https://github.com/USER/REPO" aria-label="GitHub repository"><i class="fab fa-github"></i></a>
      -->
    </span>
  </div>
  <div class="meta">
    Abhinandan Dalal,
    <a href="https://isi.irins.org/profile/111450">Diganta Mukherjee</a> and
    <a href="https://soumendu041.gitlab.io/">Soumendu Sundar Mukherjee</a>.
    <details class="simple">
      <summary><i class="ai ai-open-access ai"></i> Simply put</summary>
      <div class="body"> An epidemic spreads through a network of people, but individuals are smart—they try to avoid infection while still staying connected to friends. How quickly does the disease spread? And what happens to society as a whole? We explore these dynamics and show that the speed of spread depends strongly on the size of the “middle class” in this networked society. </div>
    </details>
  </div>
</div>

<div class="pub">
  <div class="title">
    <span style="font-weight: bold;">
      <strong>Finding Optimal Cancer Treatment using Markov Decision Process to Improve Overall Health and Quality of Life.</strong>
      <a href="https://arxiv.org/abs/2011.13960" aria-label="arXiv">
        <i class="ai ai-arxiv ai"></i>
      </a>
      <!-- <a href="https://github.com/USER/REPO" aria-label="GitHub repository"><i class="fab fa-github"></i></a> -->
    </span>
  </div>
  <div class="meta">
    <a href="https://www.linkedin.com/in/navonil-deb-06939b1b4/">Navonil Deb</a>*,
    Abhinandan Dalal*, and
    <a href="https://isi.irins.org/profile/111458">Gopal K. Basak</a>.
    <details class="simple">
      <summary><i class="ai ai-open-access ai"></i> Simply put</summary>
      <div class="body"> Imagine a young professional and an older retiree both facing cancer. The younger person may want to return to normal life quickly, even if that means enduring side-effects, while the retiree may prefer to maximize comfortable days. Cancer treatment isn’t only about eliminating the disease—it deeply affects quality of life. In this work, we show how doctors can systematically choose the next step in treatment by considering both the patient’s medical status and their personal preferences. </div>
    </details>
  </div>
</div>

<div class="pub">
  <div class="title">
    <span style="font-weight: bold;">
      <strong>Accelerography: Feasibility of Gesture Typing using Accelerometer.</strong>
      <a href="https://arxiv.org/abs/2003.14310" aria-label="arXiv">
        <i class="ai ai-arxiv ai"></i>
      </a>
      <!-- <a href="https://github.com/USER/REPO" aria-label="GitHub repository"><i class="fab fa-github"></i></a> -->
    </span>
  </div>
  <div class="meta">
    <a href="https://ieor.columbia.edu/content/arindam-roy-chowdhury">Arindam Roy Chowdhury</a>*,
    Abhinandan Dalal*, and
    <a href="https://statistics.sciences.ncsu.edu/people/ssen8/">Shubhajit Sen</a>.
    <details class="simple">
      <summary><i class="ai ai-open-access ai"></i> Simply put</summary>
      <div class="body">Imagine typing just by moving your phone. Instead of tapping keys, we show how the phone’s 3D movements can be turned into letters, making gesture typing possible. </div>
    </details>
  </div>
</div>

