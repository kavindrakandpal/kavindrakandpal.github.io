---
layout: page
permalink: /research-interest/
title: Research
# description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 3
---

<style>
    img{
        max-width:100%;
    }
    @media screen and (min-width:786px){
        img{
            max-width:100%;
        }
    }
</style>


<div id="project" class="projects">
<hr>
<h3><b>Sponsored Projects</b></h3>
{% assign sorted_projects = site.projects  %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
    </div>
  </div>
  <br><br>
</div>
<hr>
<h3><b>Research Interests</b></h3>
<br>
<img src="/al-folio/assets/img/r1.jpg">
<br>
<ol>
<li>Analog IC Design: Low power, high speed CMOS Operational Amplifier design, High speed comparators, current references and bandgap reference circuits design.</li>

<li>Mixed Signal Design: Sigma-Delta modulators, DQPSK demodulators, clocked comparators and filp-flops, memory circuit design</li>

<li>Oxide TFTs: Device modelling, transparent electronics, device fabrication, threshold voltage insensitive pixel driver circuitry design.</li>
</ol>
<br>
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="../assets/img/r1.png" alt="Design of DQPSK demodulator for implantable biomedical devices, V. Garg and K. Kandpal, JCSC, 2020">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="../assets/img/r2.png" alt="Design of 6T-1C pixel circuit for flexible displays, A. Srivastava, D. Dubey, M. Goswami, and K. Kandpal, Microelectronics Journal, 2021">
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
<br><br>