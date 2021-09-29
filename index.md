---
layout: home
title: "OSPO++"
ignore_title: true
excerpt: ""
search_omit: true
---

<div class="color">
  <div class="container">
    <div class="row text-left justify-content-md-center content">
      <div class="col-lg-12">
        <img src="./assets/images/logo.svg" class="logo" alt="OSPO++ Logo"/>
        <h1 class="heading">OSPO++</h1>
      </div>
    </div>
  </div>
</div>

<div class="container">
  <div class="row text-left justify-content-md-center content intro-para">
    <div class="col-lg-12">
      <p>OSPO++ is a network and a community of collaborative open source program offices in universities, governments, and civic institutions. We're building resources to help create OSPOs, actively engaging in discussions on how to best manage and grow open source programs, and how to garden sustainable communities that last.</p>

      <p>Interested in joining us? <a class="get-in-touch" href="mailto:info@mosslabs.io">Get in touch.</a> Register and Attend our <a class="get-in-touch2" href="https://ospoplusplus.com/events/">Working Group Events</a></p>
</div></div></div>

<div class="logos">
  <div class="container content">
    <div class="row text-center justify-content-md-center">
      <div class="col-sm-12">
        <p class="rainbow">Current OSPO++ Members</p>
      </div>

      <div class="col-6 col-md-3">
        <img src="assets/images/members/ApereoFoundationLogo.png" title="Apereo Foundation" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/baskin-logo-new.jpg" title="BASKIN CROSS" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/bitergia_logo_text.svg" title="Bitergia" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/brandeis-logo-stacked-seal-blue-digital (1).png" title="Brandeis" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/CROSS-logo.png" title="CROSS" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <!-- <a href="https://www.eclipse.org/" target="_blank"> -->
          <img src="assets/images/members/eclipse_foundation_logo/EF_GRY-OR_jpg.jpg" title="Eclipse Foundation" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/fauen.png" title="Friedrich-Alexander Universität Erlangen-Nürnberg" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/GitHub_Logo.png" title="GitHub" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/ISC logo on transparent.jpg" title="InnerSource Commons" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/Lero_Logo 270x226.jpg" title="LERO" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/longsight.png" title="Longsight" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <!-- <a href="https://www.mosslabs.io/" target="_blank"> -->
        <img src="assets/images/members/moss labs black.png" title="MOSS Labs" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/OpenCommons.jpg" title="Open Commons" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <!-- <a href="https://openforumeurope.org/" target="_blank"> -->
          <img src="assets/images/members/logo-ofe.png" title="Open Forum Europe" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/Paris-escolhe-sua-nova-identidade-visual (1).png" title="Paris" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/PSU_logo_transparent-1.png" title="PSU" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <!-- <a href="https://www.rit.edu/research/open" target="_blank"> -->
        <img src="assets/images/members/RIT.png" title="RIT" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/sheridan.png" title="Johns Hopkins Libraries" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/Logo-1B-SMALL-Gold-Blue.png" title="Alfred P. Sloan Foundation" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/st_logo.png" title="Space Telescope Science Institute" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/Trinity_Main_logo.jpg" title="Trinity College Dublin" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <!-- <a href="https://www.ubc.ca/" target="_blank"> -->
          <img src="assets/images/members/ubc.png" title="UBC" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/Urban Systems.png" title="" class="align-middle"/>
      </div>
      <div class="col-6 col-md-3">
          <img src="assets/images/members/eaafb-images_uwm-university-of-vermont-logo.jpg" title="UVM" class="align-middle"/>
      </div>
    </div>
    <div class="row text-center justify-content-md-center" id="posts-list">
      <div class="col-sm-12">
        <p class="rainbow">Recent posts</p>
      </div>
      <div class="col-sm-12">
        {% for post in site.posts %}
          <p class="text-center"><a href="{{ site.url }}/{{ post.url }}">{{ post.title }} by {{ site.data.authors[post.author].name }}<a/></p>
        {% endfor %}
      </div>
    </div>
  </div>
</div>
