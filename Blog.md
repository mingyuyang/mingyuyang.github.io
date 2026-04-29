---
layout: blog/standard
title: Blog
permalink: /blog/
custom_color: sky
custom_font: urbanist
scroll_top_btn:
  enable: true
pagination:
  enabled: true
---
<style>
@media (max-width: 768px) {
  html {
    font-size: 85% !important;
  }
}
</style>

<div class="content-wrapper">
<header class="wrapper bg-light">
{% include components/navbar/navbar.html 
    topAlert=false
    wrapperClass="bg-soft-primary"
    classList="classic transparent navbar-light "
    logoAlt="logo-dark"
    otherClassList="ms-lg-4"
    otherBtn=true
    otherBtnClassList="btn btn-sm btn-primary rounded-pill"
    otherBtnText="Contact"
    otherBtnLink="mailto:ymy@ucsd.edu"      
%}
</header>



{% include components/footer/footer.html 
  style="minimal"
  bg_color="bg-navy"
  text_color="text-inverse" 
  cta=false
  newsletter=false
  container_padding="pt-10 pb-10"
%}
