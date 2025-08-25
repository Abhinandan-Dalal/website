---
title: Publications
hide_title: true
slug: research
---

<!-- # Conference Publications
 
<span style="font-size: 0.9em; font-weight: bold;">*[_PrIsing: Privacy-Preserving Peer Effect Estimation via Ising Model._](https://proceedings.mlr.press/v238/chakraborty24a.html)* [<i class="fa-solid fa-book"></i>](https://proceedings.mlr.press/v238/chakraborty24a.html) &nbsp; [<i class="ai ai-arxiv ai"></i>](https://arxiv.org/abs/2401.16596) &nbsp; [<i class="fab fa-github"></i>](https://github.com/anirbanc96/PrIsing)</span>     
<span style="font-size: 0.8em;">[Abhinav Chakraborty](https://abhinavc3.github.io/), Anirban Chatterjee, [Abhinandan Dalal](https://statistics.wharton.upenn.edu/profile/abdalal/). *International Conference on Artificial Intelligence and Statistics 2024*.</span>
 
<style>
  .content-container {
    display: flex;
    align-items: flex-start;
  }
  .text-container {
    flex-grow: 1;
  }

  .side-image {
    margin-top: 5px;
    margin-left: 30px; /* Adjust the space between the image and the text */
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

# New aspects # 
-->

<!-- Icons: Academicons (scholarly) + Font Awesome (GitHub only) -->
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

  .badge {
   display: inline-block;
   font-size: 0.8em;
   font-weight: 400;                 /* normal, not bold */
   color: #c0392b;                   /* deep red for text */
   background-color: rgba(192, 57, 43, 0.1); /* faint reddish background */
   padding: 0.15em 0.6em;
   border: 2px solid #c0392b;        /* solid fat red border */
   border-radius: 0.5em;             /* rounded rectangle */
   vertical-align: middle;
   }

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

<details style="margin:1rem 0;">
  <summary style="cursor:pointer; display:flex; align-items:center; gap:.5rem; font-weight:600; color:#333;">
    <i class="fa-solid fa-cloud" aria-hidden="true"></i> A bit of philosophy
  </summary>
  <p style="font-size:0.95em; color:#555; margin:0.5rem 0 0 1.5rem;">
    There is a widening gap between how the public understands science and what scientists actually do, which has fueled mistrust.
    As baby steps toward closing this gap, I’ve added two-sentence gists to my works under “Simply put,” written in accessible everyday language.
  </p>
</details>

<span style = "color: #556B2F; font-size: 0.9em; "> (* denotes equal contribution) </span>

<h2 style="color: #556B2F;">Publications</h2>

<div class="pub">
  <div class="title">
    <span style="font-weight: bold;">
      <strong> PrIsing: Privacy-Preserving Peer Effect Estimation via Ising Model. </strong>
      <a href="https://proceedings.mlr.press/v238/chakraborty24a.html" aria-label="Proceedings of Machine Learning Research">
        <i class="fa-solid fa-book"></i>
      </a>
      <a href="https://arxiv.org/abs/2401.16596" aria-label="arXiv">
         <i class="ai ai-arxiv ai"></i>
      </a>
<!--       <a href="https://github.com/anirbanc96/ECMMD-CondTwoSamp" aria-label="GitHub repository">
        <i class="fab fa-github"></i>
      </a> -->
    </span>
  </div>
  <div class="meta">
   <a href = "https://abhinavc3.github.io/">Abhinav Chakraborty</a>*, 
   <a href = "https://anirbanc96.github.io/main/">Anirban Chatterjee</a>*, and
   Abhinandan Dalal*. 
   <em> International Conference on Artificial Intelligence and Statistics 2024. </em>
   <details class="simple">
     <summary><i class="ai ai-open-access ai"></i> Simply put </summary>
     <div class="body">
      Suppose you want to understand how contagious a disease is as it spreads through a network. At the same time, whether an individual is infected is highly sensitive information. In this work, we show how to protect everyone’s privacy while still estimating the disease’s contagiousness with reliable accuracy.
     </div>
   </details> 
  </div>
</div>

<div class="pub">
  <div class="title">
    <span style="font-weight: bold;">
      <strong>  Feasibility of Transparent Price Discovery in Tea through Auction in India.  </strong>
      <a href="https://www.mcxindia.com/docs/default-source/about-us/commodity-insights-yearbook/2019/02-emerging-trends/feasibility-of-transparent-price-discovery-in-tea-through-auction-in-india-dr-diganta-mukherjee-mr-abhinandan-dalal-and-mr-subhrajyoty-roy.pdf?sfvrsn=ab5bb390_2">
        <i class="fa-solid fa-book"></i>
      </a>
     </span>
  </div>
  <div class="meta">
   <a href = "https://isi.irins.org/profile/111450">Diganta Mukherjee</a>, 
   Abhinandan Dalal, and 
   <a href = "https://www.statwizard.in/">Subhrajyoty Roy</a>.  
   <em> Commodity Insights Yearbook 2019, Multi Commodity Exchange of India Ltd. </em> 
   <span class="badge">Non-peer reviewed</span>
   <details class="simple">
     <summary><i class="ai ai-open-access ai"></i> Simply put </summary>
     <div class="body">We study the factors that influence tea prices when tea-gardens in India auction their leaves to teahouses. In particular, we highlight the role of professional tea-tasters who provide manual valuations.</div>
   </details>
  </div>
</div>



<h2 style="color: #556B2F;">Preprints</h2>

<div class="pub">
  <div class="title">
    <span style="font-weight: bold;">
      <strong> Partial Identification of Causal Effects for Endogenous Continuous Treatments. </strong>
      <a href="https://arxiv.org/abs/2508.13946" aria-label="arXiv">
        <i class="ai ai-arxiv ai"></i>
      </a>
<!--       <a href="https://github.com/anirbanc96/ECMMD-CondTwoSamp" aria-label="GitHub repository">
        <i class="fab fa-github"></i>
      </a> -->
    </span>
  </div>
  <div class="meta">Abhinandan Dalal and <a href = "https://statistics.wharton.upenn.edu/profile/ett/">Eric J. Tchetgen Tchetgen</a>. 
   <details class="simple">
     <summary><i class="ai ai-open-access ai"></i> Simply put </summary>
     <div class="body">An effect is causal only if it cannot be explained away by other factors. But what if some relevant factor is unmeasured? We study the sensitivity of causal claims to such unobserved confounding, focusing on continuous treatments (e.g., varying levels of exposure to secondhand smoke) and their effects on outcomes (e.g., children’s blood lead levels). Using machine learning, we estimate how much the outcome could vary once we account for potentially unmeasured biases.
     </div>
   </details>
  </div>
</div>

<div class="pub">
  <div class="title">
    <span style="font-weight: bold;">
      <strong> Anytime-Valid Inference for Double/Debiased Machine Learning of Causal Parameters. </strong>
      <a href="https://arxiv.org/abs/2408.09598" aria-label="arXiv">
        <i class="ai ai-arxiv ai"></i>
      </a>
<!--       <a href="https://github.com/anirbanc96/ECMMD-CondTwoSamp" aria-label="GitHub repository">
        <i class="fab fa-github"></i>
      </a> -->
    </span>
  </div>
  <div class="meta">Abhinandan Dalal, 
   <a href = "https://www.amazon.science/author/patrick-bloebaum">Patrick Bl&ouml;baum </a>, <a href = "https://www.shivakasiviswanathan.com/">Shiva Kasiviswanathan </a> and 
   <a href = "https://www.stat.cmu.edu/~aramdas/">Aaditya Ramdas</a>. 
   <details class="simple">
     <summary><i class="ai ai-open-access ai"></i> Simply put
     </summary>
     <div class="body">A doctor wants to test a pill by giving some people the pill and others a look-alike candy. Not everyone takes what they are given. The doctor checks results as the study goes on—ready to stop early if the pill looks harmful, or to recommend it widely if it looks helpful. In this work, we show how such continuous monitoring can be done without making the doctor’s conclusions invalid (and many more such problems), even when using machine-learning–based inference. </div>
   </details>
  </div>
</div>

<div class="pub">
  <div class="title">
    <span style="font-weight: bold;">
      <strong>  Planning for Gold: Sample Splitting for Valid Powerful Design of Observational Studies.  </strong>
      <a href="https://arxiv.org/abs/2406.00866" aria-label="arXiv">
        <i class="ai ai-arxiv ai"></i>
      </a>
<!--       <a href="https://github.com/anirbanc96/ECMMD-CondTwoSamp" aria-label="GitHub repository">
        <i class="fab fa-github"></i>
      </a> -->
    </span>
  </div>
  <div class="meta">
   <a href = "https://willbekerman.github.io/research/">William Bekerman</a>*, 
   Abhinandan Dalal*,
   <a href = "https://blogs.worldbank.org/en/team/c/carlo-del-ninno">Carlo del Ninno </a> and 
   <a href = "https://statistics.wharton.upenn.edu/profile/dsmall/">Dylan S Small</a>.  
   Major revision at <em>Biometrika</em>.
   <details class="simple">
     <summary><i class="ai ai-open-access ai"></i> Simply put </summary>
     <div class="body">Sometimes researchers want to peek at part of the data to see what they are dealing with. But once they do, that part can no longer count toward the final analysis, which means losing valuable sample size. On the other hand, studies that are not true experiments risk being swayed by hidden factors. In this work, we show a common solution: in your peek, focus on outcomes that are least likely to be distorted by any hidden influences.
     </div>
   </details>
  </div>
</div>

<p style="font-size:1em;">
  Some of my older unpublished research can be found in
  <a href="/reports/">Technical Reports</a>.
</p>


