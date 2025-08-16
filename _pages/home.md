---
layout: page
permalink: /
title: home
nav: home
---

<!-- Header Section -->
<div class="row">
  <div class="col-md-4 text-center">
    <img class="profile-img rounded-circle mb-3" src="{{ 'prof_pic.jpeg' | prepend: '/assets/img/' | prepend: site.baseurl }}" style="width: 200px; height: 200px; object-fit: cover;">
  </div>
  <div class="col-md-8">
    <h1 class="title font-weight-bold mb-2">YOU Yufa</h1>
    <h5 class="text-muted mb-3">PhD Student</h5>
    <p class="lead">The Hong Kong Polytechnic University | Aeronautical and Aviation Engineering</p>
    
    <!-- Contact Links -->
    <div class="mb-3">
      <a href="mailto:iyouyufa@gmail.com" class="btn btn-outline-primary btn-sm mr-2">📧 Email</a>
      <a href="/assets/pdf/cv_en.pdf" target="_blank" class="btn btn-outline-secondary btn-sm mr-2">📄 CV</a>
      <a href="https://github.com/edyou25" target="_blank" class="btn btn-outline-dark btn-sm">💻 GitHub</a>
    </div>
  </div>
</div>

<!-- About Section -->
<div class="row mt-5">
  <div class="col-12">
    <h2 class="mb-4">About</h2>
    <p class="text-justify">
      I am currently a PhD student in the <strong>Department of Aeronautical and Aviation Engineering</strong> at <strong>The Hong Kong Polytechnic University</strong>, supervised by <a href="https://www.polyu.edu.hk/en/aae/people/academic-staff/dr-huang-hailong/" target="_blank">Prof. Huang Hailong</a>. My research focuses on <strong>Flight Mechanics and Control</strong>, exploring advanced control algorithms for aerospace applications.
    </p>
    
    <p class="text-justify">
      Previously, I worked as a Motion Planning Engineer at <strong>BYD Ltd.</strong> in the Autonomous Driving Unit, where I developed the E4APA Parking Assistance system for 4WD vehicles. I also contributed to the MPilot Self-Driving Project at <strong>Momenta Tech Ltd.</strong> for Mercedes-Benz and Toyota. I hold an M.S. in Control Engineering from <strong>Harbin Institute of Technology</strong>, where my research focused on vehicle motion planning in both on-road and open-space environments.
    </p>

    <!-- Key Achievement -->
    <div class="alert alert-info" role="alert">
      🏆 <strong>Achievement:</strong> National Award Winner at NXP Cup Intelligent Car Race (2019)
    </div>
  </div>
</div>

<!-- Featured Work Section -->
<div class="row mt-5">
  <div class="col-12">
    <h2 class="mb-4">Featured Work</h2>
    
    <!-- E4APA Project -->
    <div class="card mb-4">
      <div class="card-body">
        <h5 class="card-title">E4APA - 4WD Parking Assistance System</h5>
        <p class="card-text">Advanced motion planning algorithms for autonomous parking in complex scenarios.</p>
        
        <!-- Featured YouTube Video -->
        <div class="row mb-4">
          <div class="col-12">
            <div class="embed-responsive embed-responsive-16by9 mb-3">
              <iframe class="embed-responsive-item" 
                      src="https://www.youtube.com/embed/XRDDc8HkzMI?si=UVLOhKN1yFvj0gl4&mute=1&autoplay=1&loop=1&playlist=XRDDc8HkzMI" 
                      title="E4APA Demo Video" 
                      frameborder="0" 
                      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                      allowfullscreen>
              </iframe>
            </div>
            <div class="text-center">
              <small class="text-muted">E4APA System Demonstration</small>
              
              <!-- YouTube Stats -->
              <div class="d-flex justify-content-center align-items-center mt-2 mb-2">
                <span class="badge badge-light mr-2">
                  <i class="fas fa-play"></i> 508K views
                </span>
                <span class="badge badge-light mr-2">
                  <i class="fas fa-thumbs-up"></i> 2.1k likes
                </span>
                <span class="badge badge-light">
                  <i class="fas fa-comment"></i> 296 comments
                </span>
              </div>
              
            </div>
          </div>
        </div>
        
        <!-- Local Videos -->
        <div class="row">
          <div class="col-md-4 mb-3">
            <video class="w-100" controls muted autoplay>  
              <source src="assets/vid/e4apa-plot.mp4" type="video/mp4">  
            </video>
            <small class="text-muted">Path Planning Visualization</small>
          </div>
          <div class="col-md-4 mb-3">
            <video class="w-100" controls muted autoplay>  
              <source src="assets/vid/e4apa-race.mp4" type="video/mp4">  
            </video>
            <small class="text-muted">Racing with humans at OpenDay</small>
          </div>
          <div class="col-md-4 mb-3">
            <div class="embed-responsive embed-responsive-16by9">
              <iframe class="embed-responsive-item" 
                      src="//player.bilibili.com/player.html?bvid=BV1aFfAY2EW6&page=1&muted=true&autoplay=1" 
                      title="Magic movements with 4DW"
                      frameborder="0" 
                      scrolling="no" 
                      allowfullscreen>
              </iframe>
            </div>
            <small class="text-muted d-block mt-2">Magic movements with 4DW</small>
          </div>
        </div>
      </div>
    </div>

    <!-- NXP Cup Project -->
    <div class="card mb-4">
      <div class="card-body">
        <h5 class="card-title">NXP Cup Intelligent Car Race - National Award</h5>
        <p class="card-text">Autonomous vehicle control and navigation system for competitive racing.</p>
        
        <div class="row">
          <div class="col-md-8 mb-3">
            <video class="w-100" controls muted>  
              <source src="assets/vid/race.mp4" type="video/mp4">  
            </video>
            <small class="text-muted">Competition Performance</small>
          </div>
          <div class="col-md-4 d-flex align-items-center">
            <div>
              <h6>🏆 National Award Winner</h6>
              <p class="text-muted">Recognized for excellence in autonomous vehicle control algorithms and system integration.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- GitHub Contributions Section -->
<div class="row mt-5">
  <div class="col-12">
    <h2 class="mb-4">GitHub Activity</h2>
    
    
    <div class="github-contributions mb-4">
          <img src="https://ghchart.rshah.org/edyou25" alt="GitHub Contributions" class="w-100" style="max-width: 100%; height: auto;">
        </div>
        
  </div>
</div>

<!-- Career Timeline Section -->
<div class="row mt-5">
  <div class="col-12">
    <h2 class="mb-4">Career</h2>
    
    <div class="timeline-container">
      <div class="timeline-item current">
        <div class="timeline-date">
          <span class="badge">2024-Present</span>
        </div>
        <div class="timeline-content">
          <img src="{{ '/assets/img/institutions/polyu.png' | prepend: site.baseurl }}" alt="PolyU Logo" class="institution-logo">
          <div class="timeline-info">
            <h6 class="timeline-title">The Hong Kong Polytechnic University</h6>
            <p class="timeline-subtitle">PhD Student</p>
          </div>
        </div>
      </div>
      
      <div class="timeline-item">
        <div class="timeline-date">
          <span class="badge">2023-2024</span>
        </div>
        <div class="timeline-content">
          <img src="{{ '/assets/img/institutions/byd_logo.svg' | prepend: site.baseurl }}" alt="BYD Logo" class="institution-logo">
          <div class="timeline-info">
            <h6 class="timeline-title">BYD Motor Ltd.</h6>
            <p class="timeline-subtitle">Motion Planning Engineer</p>
          </div>
        </div>
      </div>
      
      <div class="timeline-item">
        <div class="timeline-date">
          <span class="badge">2022</span>
        </div>
        <div class="timeline-content">
          <img src="{{ '/assets/img/institutions/Momenta.png' | prepend: site.baseurl }}" alt="Momenta Logo" class="institution-logo">
          <div class="timeline-info">
            <h6 class="timeline-title">Momenta Tech Ltd.</h6>
            <p class="timeline-subtitle">Algorithm Intern</p>
          </div>
        </div>
      </div>
      
      <div class="timeline-item">
        <div class="timeline-date">
          <span class="badge">2020-2023</span>
        </div>
        <div class="timeline-content">
          <img src="{{ '/assets/img/institutions/hit_logo.svg' | prepend: site.baseurl }}" alt="HIT Logo" class="institution-logo">
          <div class="timeline-info">
            <h6 class="timeline-title">Harbin Institute of Technology</h6>
            <p class="timeline-subtitle">M.S. in Control Engineering</p>
          </div>
        </div>
      </div>
      
      <div class="timeline-item">
        <div class="timeline-date">
          <span class="badge">2016-2020</span>
        </div>
        <div class="timeline-content">
          <img src="{{ '/assets/img/institutions/dmu_logo.svg' | prepend: site.baseurl }}" alt="DMU Logo" class="institution-logo">
          <div class="timeline-info">
            <h6 class="timeline-title">Dalian Maritime University</h6>
            <p class="timeline-subtitle">B.Eng. in Automation</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>


<!-- Publications Section -->
<div class="row mt-5">
  <div class="col-12">
    <h2 class="mb-4">Selected Publications</h2>
    
    <div class="card">
      <div class="card-body">
        <h6 class="card-title">A Hybrid Trajectory Planning Strategy for Intelligent Vehicles with Collision Avoidance</h6>
        <p class="card-text">
          <strong>Y. You</strong>, L. Zhao, H. Liu and Z. Liu<br>
          <em>2022 41st Chinese Control Conference (CCC)</em>, Hefei, China, 2022, pp. 5353-5358
        </p>
        <div class="mt-2">
          <a href="/assets/pdf/ccc.pdf" target="_blank" class="btn btn-outline-primary btn-sm">
            📄 PDF
          </a>
          <a href="/assets/pdf/thesis.pdf" target="_blank" class="btn btn-outline-secondary btn-sm">
            📖 Thesis
          </a>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- News Section -->
<div class="row mt-5">
  <div class="col-12">
    <h2 class="mb-4">Recent News</h2>
    {% assign news = site.news | reverse %}
    {% for item in news limit: site.news_limit %}
      <div class="d-flex mb-3">
        <div class="flex-shrink-0">
          <span class="badge badge-primary">
            {{ item.date | date: "%b %Y" }}
          </span>
        </div>
        <div class="flex-grow-1 ml-3">
          <p class="mb-0">{{ item.content | remove: '<p>' | remove: '</p>' | emojify }}</p>
        </div>
      </div>
    {% endfor %}
  </div>
</div>


