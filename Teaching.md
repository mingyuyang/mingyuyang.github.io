---
layout: default
title: Teaching
permalink: /teaching/
custom_color: sky
custom_font: urbanist
scroll_top_btn:
  enable: true
              
---
<style>

/* ✅ Default (applies everywhere unless overridden) */
.course-tag {
  font-size: 11px !important;
}

/* ✅ Mobile overrides */
@media (max-width: 768px) {
  html {
    font-size: 85% !important;
  }

  #hero-img {
    max-height: 270px !important;
  }

  #hero-text {
    padding: 0 24px;
  }

  .course-icon {
    width: 70px !important;
  }

  .course-tag {
    font-size: 9px !important;
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
<!-- /header -->

<section class="wrapper bg-light">
  <div class="container py-8 py-md-13 text-center">
    <div class="row">
      <div class="col-md-10 offset-md-1 col-lg-8 offset-lg-2">
      <h3 class="display-4 mb-7 px-xl-7">Teaching</h3>
      </div>
    </div>
    <div class="position-relative">
      <div class="shape rounded-circle bg-soft-blue rellax w-16 h-16" data-rellax-speed="1" style="bottom: -0.5rem; right: -2.2rem; z-index: 0;"></div>
      <div class="shape bg-dot yellow rellax w-16 h-17" data-rellax-speed="1" style="top: -0.5rem; left: -2.5rem; z-index: 0;"></div>
      <div class="row gx-md-5 gy-5 text-center">
        
        <div class="col-md-6 col-xl-4">
          <div class="card shadow-lg">
            <div class="card-body text-start">
              <img class="course-icon"
                src="/assets/img/icons/courses/bild5_icon.png"
                alt=""
                style="width: 100px; height: auto;" />
              <h3>BILD 005 Data Analysis & Design for Biologists</h3>
              <p class="mb-2">Introduction to information literacy, experimental design, and data analysis for biologists, including coding, data management, and quantitative analysis. Practical skills related to effectively asking and answering biological questions with data.</p>
            </div>
          </div>
        </div>
        

        <div class="col-md-6 col-xl-4">
          <div class="card shadow-lg">
            <div class="card-body text-start">
              <img class="course-icon" 
                src="/assets/img/icons/courses/bipn100_icon.png"
                alt=""
                style="width: 100px; height: auto;" />
              <h3>BIPN 100 Human Physiology I</h3>
              <p class="mb-2">Concepts of physiological regulation, controlled and integrated by the nervous and endocrine systems. Structure and function of the muscular, cardiovascular, and renal systems in detail and their control through the interaction of nervous activity and hormones. </p>
            </div>
          </div>
        </div>

        <div class="col-md-6 col-xl-4">
          <div class="card shadow-lg">
            <div class="card-body text-start">
              <img class="course-icon" 
                src="/assets/img/icons/courses/bipn102_icon.png"
                alt=""
                style="width: 100px; height: auto;" />
              <h3>BIPN 102 Human Physiology II</h3>
              <p class="mb-2"><i>(Starting Summer 2027)</i> Completes the survey of organ systems begun in BIPN 100 by considering the respiratory and gastrointestinal systems, and the interactions of these systems in weight and temperature regulation, exercise physiology, stress, and metabolism.</p>
            </div>
          </div>
        </div>

        <div class="col-md-6 col-xl-4">
          <div class="card shadow-lg">
            <div class="card-body text-start">
              <img class="course-icon"
                src="/assets/img/icons/courses/bipn103_icon.png"
                alt=""
                style="width: 100px; height: auto;" />
              <h3>BIPN 103 Human Anatomy w/ Lab</h3>
              <p class="mb-2">Tour of the human body, emphasizing the cellular and structural organization of the major organ systems. Covers the skeletal, muscular, nervous, cardiovascular, respiratory, digestive, urinary, and reproductive systems.</p>
            </div>
          </div>
        </div>

        <div class="col-md-6 col-xl-4">
          <div class="card shadow-lg">
            <div class="card-body text-start">
              <img class="course-icon"
                src="/assets/img/icons/courses/bipn104_icon.png"
                alt=""
                style="width: 100px; height: auto;" />
              <h3>BIPN 104 Physiological Inquiry</h3>
              <p class="mb-2"><i>(Starting Summer 2027)</i> Analysis of primary literature in physiology and clinical case studies. Emphasis on analyzing research data, developing critical thinking skills, and applying physiological principles to understand scientific discoveries and human health.</p>
            </div>
          </div>
        </div>

        <div class="col-md-6 col-xl-4">
          <div class="card shadow-lg">
            <div class="card-body text-start">
              <img class="course-icon"
                src="/assets/img/icons/courses/bggn277_icon.png"
                alt=""
                style="width: 100px; height: auto;" />
              <h3>BGGN 277 Integrative Anatomy, Physiology, Pathophysiology</h3>
              <p class="mb-2"><i>(Starting Spring 2027)</i> Third course in a year-long sequence for master’s students. Integrates advanced human anatomy and physiology with pathophysiological mechanisms of disease. Emphasis on digestive, renal, and gastrointestinal systems, and multisystem processes and disorders.</p>
            </div>
          </div>
        </div>



      </div>
    </div>
  </div>
</section>



<section class="wrapper bg-light">
  <div class="container py-0 py-md-0">
    <div class="row text-center">
      <div class="col-xl-10 mx-auto">
       <h2 class="fs-15 text-uppercase text-muted mb-3">Click on a course for my end-of-quarter reflections</h2>

      
      </div>
    </div>

    <div class="row">
      <div class="col-xl-10 mx-auto">
        <form class="filter-form mb-10">
          <div class="row">
            
            <div class="col-md-4 mb-3">
              <div class="form-select-wrapper">
                <select class="form-select" id="courseFilter" aria-label="">
                  <option value="">Course</option>
                  
                  <option value="BILD 005">BILD 005</option>
                  
                  <option value="BIPN 100">BIPN 100</option>
                  
                  <option value="BIPN 103">BIPN 103</option>
                </select>
              </div>
            </div>
            
            <div class="col-md-4 mb-3">
              <div class="form-select-wrapper">
                <select class="form-select" id="yearFilter" aria-label="">
                  <option value="">Academic Year</option>
                  
                  <option value="25-26">25-26</option>

                  <option value="24-25">24-25</option>
                  
                </select>
              </div>
            </div>
            
            <div class="col-md-4 mb-3">
              <div class="form-select-wrapper">
                <select class="form-select" id="buildingFilter" aria-label="">
                  <option value="">Location</option>
                
                  <option value="Catalyst">Catalyst</option>
                  
                  <option value="Center Hall">Center Hall</option>

                  <option value="CSB">CSB</option>

                  <option value="FAH">FAH</option>
                  
                  <option value="HSS">HSS</option>

                  <option value="Mosaic">Mosaic</option>

                  <option value="Solis Hall">Solis Hall</option>
                  
                  <option value="TATA">TATA</option>
                  
                </select>
              </div>
            </div>
            
          </div>
        </form>

        
        <div class="job-list mb-10">



        <a class="job-item card mb-2 lift" 
          data-course="BIPN 100" 
          data-year = "25-26" 
          data-building = "">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-blue text-white w-11 h-11 me-2 course-tag">BIPN 100</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Human Physiology I
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Summer 2026
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> TBD
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  TBD
                </span>
              </span>
            </div>
          </a> 

        <a class="job-item card mb-2 lift" 
          data-course="BIPN 100" 
          data-year = "25-26" 
          data-building = "FAH">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-blue text-white w-11 h-11 me-2 course-tag">BIPN 100</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Human Physiology I
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Spring 2026
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> FAH 1301
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  236 students
                </span>
              </span>
            </div>
          </a>

        <a class="job-item card mb-2 lift" 
          data-course="BIPN 103" 
          data-year = "25-26" 
          data-building = "TATA">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-red text-white w-11 h-11 me-2 course-tag">BIPN 103</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Human Anatomy w/ Lab
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Spring 2026
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> TATA 2501
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  47 students
                </span>
              </span>
            </div>
          </a>

        <a href="/blog/bipn-100-wi26-course-retrospective/" class="job-item card mb-2 lift" 
          data-course="BIPN 100" 
          data-year = "25-26" 
          data-building = "Mosaic">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-blue text-white w-11 h-11 me-2 course-tag">BIPN 100</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Human Physiology I
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Winter 2026
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> MOS 0114
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  245 students
                </span>
              </span>
            </div>
          </a>
          

      <a href="/blog/bild-005-wi26-course-retrospective/" class="job-item card mb-2 lift" 
        data-course="BILD 005" 
        data-year = "25-26" 
        data-building = "Catalyst">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-yellow text-white w-11 h-11 me-2 course-tag">BILD 005</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Data Analysis & Design for Biologists
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Winter 2026
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> CTL 0125
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  344 students
                </span>
              </span>
            </div>
          </a>




        <a href="/blog/bipn-100-fa25-course-retrospective/" class="job-item card mb-2 lift" 
          data-course="BIPN 100" 
          data-year = "25-26" 
          data-building = "HSS">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-blue text-white w-11 h-11 me-2 course-tag">BIPN 100</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Human Physiology I
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Fall 2025
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> Ledden AUD
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  213 students
                </span>
              </span>
            </div>
          </a>

         <a href="/blog/bipn-103-fa25-course-retrospective/" class="job-item card mb-2 lift"
          data-course="BIPN 103" 
          data-year = "25-26" 
          data-building = "TATA">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-red text-white w-11 h-11 me-2 course-tag">BIPN 103</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Human Anatomy w/ Lab
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Fall 2025
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> TATA 2501
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  48 students
                </span>
              </span>
            </div>
          </a>


         <a href="/blog/bipn-100-su25-course-retrospective/" class="job-item card mb-2 lift" 
          data-course="BIPN 100" 
          data-year = "24-25" 
          data-building = "CSB">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-blue text-white w-11 h-11 me-2 course-tag">BIPN 100</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Human Physiology I
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Summer 2025
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> CSB 002
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  89 students
                </span>
              </span>
            </div>
          </a>



         <a href="/blog/bipn-100-sp25-course-retrospective/" class="job-item card mb-2 lift" 
          data-course="BIPN 100" 
          data-year = "24-25" 
          data-building = "HSS">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-blue text-white w-11 h-11 me-2 course-tag">BIPN 100</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Human Physiology I
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Spring 2025
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> HSS 1330
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  142 students
                </span>
              </span>
            </div>
          </a>

         <a href="/blog/bild-005-sp25-course-retrospective/" class="job-item card mb-2 lift" 
          data-course="BILD 005" 
          data-year = "24-25" 
          data-building = "Center Hall">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-yellow text-white w-11 h-11 me-2 course-tag">BILD 005</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Data Analysis & Design for Biologists
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Spring 2025
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> Center 101
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  183 students
                </span>
              </span>
            </div>
          </a>
          


         <a href="/blog/bipn-100-wi25-course-retrospective/" class="job-item card mb-2 lift" 
          data-course="BIPN 100" 
          data-year = "24-25" 
          data-building = "Solis Hall">
            <div class="card-body p-2">
             <span class="row justify-content-between g-2">
               <span class="col-1 col-md-1 mb-2 mb-md-0 text-body">
                  <span class="avatar bg-blue text-white w-11 h-11 me-2 course-tag">BIPN 100</span>
                  </span>
                <span class="col-2 col-md-5 text-body d-flex align-items-center">
                  Human Physiology I
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-clock me-1"></i> Winter 2025
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  <i class="uil uil-location-arrow me-1"></i> Solis 107
                </span>
                <span class="col-2 col-md-2 text-body d-flex align-items-center">
                  130 students
                </span>
              </span>
            </div>
          </a>
  
    
        </div>
      
          
     
      
        </div>
        
      </div>
    </div>
</section>
              

<script>
const course = document.getElementById('courseFilter');
const year = document.getElementById('yearFilter');
const building = document.getElementById('buildingFilter');

const items = document.querySelectorAll('.job-item');

function filterItems() {
  const c = course.value;
  const y = year.value;
  const r = building.value;

  items.forEach(item => {
    const matchCourse  = !c || item.dataset.course === c;
    const matchYear    = !y || item.dataset.year === y;
    const matchBuilding = !r || item.dataset.building === r;

    item.style.display = (matchCourse && matchYear && matchBuilding)
      ? ''
      : 'none';
  });
}

course.addEventListener('change', filterItems);
year.addEventListener('change', filterItems);
building.addEventListener('change', filterItems);


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
