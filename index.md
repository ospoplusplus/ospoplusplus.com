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
        <img src="./assets/images/logo.svg" class="logo" alt="OSPO++ Logo" />
        <h1 class="heading">OSPO++</h1>
      </div>
    </div>
  </div>
</div>

<div class="container">
  <div class="row text-left justify-content-md-center content intro-para">
    <div class="col-lg-12">
      <p>OSPO++ is a network and a community of collaborative open source program offices in universities, governments, and civic institutions. We're building resources to help create OSPOs, actively engaging in discussions on how to best manage and grow open source programs, and how to garden sustainable communities that last.</p>

      <p>Register and attend our <a class="get-in-touch" href="https://ospoplusplus.com/working-group/">Working Group Discussions</a>.</p>

      <p>More questions, or interested in joing us? <a class="get-in-touch" href="mailto:info@mosslabs.io">Get in touch.</a></p>
    </div>
  </div>
</div>

<div class="logos">
  <div class="container content">
    <div class="row text-center justify-content-md-center">
      <div class="col-sm-12">
        <p class="rainbow">Current OSPO++ Members</p>
      </div>
      
      <div class="col-6 col-md-3">
        <img src="assets/images/members/alfred_sloan_logo.png" title="Alfred P. Sloan Foundation" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/apereo_foundation_logo.png" title="Apereo Foundation" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/baskin_enginnering_logo.jpg" title="Baskin Engineering UCSC" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/bitergia_logo_text.svg" title="Bitergia" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/brandeis_logo.png" title="Brandeis" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/cmu_logo.jpg" title="Carnegie Mellon University" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/cross_logo.png" title="CROSS" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/eclipse_foundation_logo.png" title="Eclipse Foundation" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/fau_logo.png" title="Friedrich-Alexander Universität Erlangen-Nürnberg" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/github_logo.png" title="GitHub" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/innersource_commons_logo.jpg" title="InnerSource Commons" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/johns_hopkins_university_logo.png" title="Johns Hopkins Libraries" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/lero_logo.jpg" title="LERO" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/longsight_logo.png" title="Longsight" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/moss_labs_logo.png" title="MOSS Labs" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/oasis_open_logo.svg" title="Oasis Open" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/ofe_logo.png" title="Open Forum Europe" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/open_commons_logo.jpg" title="Open Commons" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/paris_logo.png" title="Paris" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/psu_logo.png" title="PSU" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/rit_logo.png" title="RIT" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/slu_logo.png" title="Saint Louis University" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/stsci_logo.png" title="Space Telescope Science Institute" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/trinity_college_logo.jpg" title="Trinity College Dublin" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/ubc_logo.png" title="UBC" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/urban_systems_logo.png" title="" class="align-middle" />
      </div>
      <div class="col-6 col-md-3">
        <img src="assets/images/members/eaafb-images_uwm-university-of-vermont-logo.jpg" title="UVM" class="align-middle" />
      </div>
    </div>
    <div class="row text-center justify-content-md-center" id="posts-list">
      <div class="col-sm-12">
        <p class="rainbow">Recent posts</p>
      </div>
      <div class="col-sm-12">
        {% for post in site.posts %}
        <p class="text-center"><a href="{{ site.url }}/{{ post.url }}">{{ post.title }} by {{ site.data.authors[post.author].name }}</a></p>
        {% endfor %}
      </div>
    </div>
  </div>
</div>