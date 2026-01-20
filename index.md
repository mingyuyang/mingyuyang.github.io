---
layout: default
title: Home
permalink: /
custom_color: sky
custom_font: urbanist
scroll_top_btn:
  enable: true

# Hero Section
hero:
  title: Hi, I'm Ming!
  subtitle: I’m an Assistant Teaching Professor at UC San Diego, in the Department of Cell and Developmental Biology. As a teaching-focused faculty member, my primary role (and passion) is teaching and designing undergraduate courses. I also research how students develop mechanistic reasoning and visual literacy, and I develop curricular materials to equip biologists with programming and quantitative skills. I love being in the classroom, and I care deeply about building a culture of joy and inclusion in my classes.
  button:
    label: Download my CV
    url: "#"
    class: btn btn-lg btn-primary rounded-pill
  image: /assets/img/photos/ming_headshot2.png
  image2x: /assets/img/photos/ming_headshot2.png
  
# Services Section
services:
  title: What am I teaching this year?
  service_items:
    - image: /assets/img/icons/seasons/fall.png
      image2x: /assets/img/icons/seasons/fall.png
      title: Fall 2025
      text: <ul> <li>BIPN 100 Human Physiology I</li> <li>BIPN 103 Human Anatomy w/ Lab</li></ul>
    - image: /assets/img/icons/seasons/winter.png
      image2x: /assets/img/icons/seasons/winter.png
      title: Winter 2026
      text: <ul> <li>BIPN 100 Human Physiology I</li><li>BILD 5 Data Analysis & Design for Biologists</li> </ul>
    - image: /assets/img/icons/seasons/spring.png
      image2x: /assets/img/icons/seasons/spring.png
      title: Spring 2026
      text: <ul> <li>BIPN 100 Human Physiology I</li><li>BIPN 103 Human Anatomy w/ Lab</li> </ul>


# Footer CTA
footer_cta:
  title: Join our community by using our services and grow your business.
  button:
    label: Try It For Free
    url: "#"
    class: btn btn-primary rounded-pill

---

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
<!-- /header -->

{% include components/sections/demo21/hero.html %}
{% include components/sections/demo21/services.html %}


<section class="wrapper bg-light">
  <div class="container py-0 py-md-0">
    <div class="row text-center">

    </div>

    <div class="row">
      <h2 class="text-center">News</h2>
      <div class="col-12">
        <form class="filter-form mb-5">
          <div class="row">
            
            <div class="col-md-4 mb-0">
            </div>
            
            <div class="col-md-4 mb-0">
              <div class="form-select-wrapper">
                <select class="form-select" id="yearFilter" aria-label="">
                  <option value="">Filter by academic year</option>

                  <option value="25-26">25-26</option>

                  <option value="24-25">24-25</option>

                  <option value="23-24">23-24</option>
                  
                </select>
              </div>
            </div>
            
            <div class="col-md-4 mb-0">
            </div>
            
          </div>
        </form>

        
        <div class="job-list mb-10">


        <div class="job-item card border-0 bg-transparent mb-4" data-year="25-26">
          <div class="card-body p-2">
            <span class="row justify-content-between g-4">
              <span class="col-2 col-md-2 text-body d-flex align-items-center">
                <strong>Jan 2026</strong>
              </span>
              <span class="col-10 col-md-10 text-body d-flex align-items-center">
              Heidi, my undergraduate research mentee, presented a short talk at SABER West examining how the visuals used in biology courses may shape students’ reasoning in chemistry.
              </span>
            </span>
          </div>
        </div>


        <div class="job-item card border-0 bg-transparent mb-4" data-year="25-26">
          <div class="card-body p-2">
            <span class="row justify-content-between g-4">
              <span class="col-2 col-md-2 text-body d-flex align-items-center">
                <strong>Sep 2025</strong>
              </span>
              <span class="col-10 col-md-10 text-body d-flex align-items-center">
              I gave a talk at UCSD Biology's Innovations in Teaching Symposium about my education research projects.
              </span>
            </span>
          </div>
        </div>

         <div class="job-item card border-0 bg-transparent mb-4" data-year="25-26">
          <div class="card-body p-2">
            <span class="row justify-content-between g-4">
              <span class="col-2 col-md-2 text-body d-flex align-items-center">
                <strong>Aug 2025</strong>
              </span>
              <span class="col-10 col-md-10 text-body d-flex align-items-center">
              This quarter, Carlos Rojo and I are launching BIPN 103 (Human Anatomy). We're so excited to offer an undergraduate anatomy course for the first time at UCSD!
              </span>
            </span>
          </div>
        </div>


        <div class="job-item card border-0 bg-transparent mb-4" data-year="24-25">
          <div class="card-body p-2">
            <span class="row justify-content-between g-2">
              <span class="col-2 col-md-2 text-body d-flex align-items-center">
                <strong>May 2025</strong>
              </span>
              <span class="col-10 col-md-10 text-body d-flex align-items-center">
              Heidi, my first undergraduate research mentee at UCSD, presented her research at the Summer Research Conference (SRC)! Heidi's project explored how students reconcile their conflicting disciplinary ideas about chemical bonding.
              </span>
            </span>
          </div>
        </div>

        <div class="job-item card border-0 bg-transparent mb-4" data-year="24-25">
          <div class="card-body p-2">
            <span class="row justify-content-between g-2">
              <span class="col-2 col-md-2 text-body d-flex align-items-center">
                <strong>May 2025</strong>
              </span>
              <span class="col-10 col-md-10 text-body d-flex align-items-center">
              Our paper about visual representations of bonding and energy is published in Biochemistry and Molecular Biology Education (BAMBED).
              </span>
            </span>
          </div>
        </div>

        <div class="job-item card border-0 bg-transparent mb-4" data-year="24-25">
          <div class="card-body p-2">
            <span class="row justify-content-between g-2">
              <span class="col-2 col-md-2 text-body d-flex align-items-center">
                <strong>Jan 2025</strong>
              </span>
              <span class="col-10 col-md-10 text-body d-flex align-items-center">
              I gave a talk at SABER West on how visual representations of ATP shape students' chemical reasoning. 
              </span>
            </span>
          </div>
        </div>

        <div class="job-item card border-0 bg-transparent mb-4" data-year="24-25">
          <div class="card-body p-2">
            <span class="row justify-content-between g-2">
              <span class="col-2 col-md-2 text-body d-flex align-items-center">
                <strong>Jan 2025</strong>
              </span>
              <span class="col-10 col-md-10 text-body d-flex align-items-center">
              I started teaching at UCSD! For my first quarter, I'll be teaching BIPN 100 (Human Physiology I).
              </span>
            </span>
          </div>
        </div>


        <div class="job-item card border-0 bg-transparent mb-4" data-year="23-24">
          <div class="card-body p-2">
            <span class="row justify-content-between g-2">
              <span class="col-2 col-md-2 text-body d-flex align-items-center">
                <strong>May 2024</strong>
              </span>
              <span class="col-10 col-md-10 text-body d-flex align-items-center">
              I defended my PhD thesis and graduated from MIT!
              </span>
            </span>
          </div>
        </div>

      </div>
    </div>



  </div>
</div>
</section>

<p></p>    
<p></p>            
<script>
const year = document.getElementById('yearFilter');
const items = document.querySelectorAll('.job-item');

year.addEventListener('change', () => {
  const y = year.value;

  items.forEach(item => {
    // Show item if year matches or if no year selected
    item.style.display = !y || item.dataset.year === y ? '' : 'none';
  });
});
</script>

</div>
{% include components/footer/footer.html 
  style="minimal"
  bg_color="bg-navy"
  text_color="text-inverse" 
  cta=false
  newsletter=false
  container_padding="pt-10 pb-10"
%}
