---
layout: page
permalink: /
title: about
nav: about
---

<div class="text-center mt-5">
  <img class="profile-img" src="{{ 'prof_pic.jpeg' | prepend: '/assets/img/' | prepend: site.baseurl }}">
</div>

<div class="col mt-4">
  <h1 class="title text-center font-weight-bold">Yufa You</h1>
  <div class="row mt-3 mb-3">
    <div class="col">
      <h6 class="mt-1 text-center text-sm-center" style="font-stretch: ultra-condensed;">
        Motion Planning Engineer<br/>
        BYD Motor Ltd. Autonomous Driving Unit
      </h6>
    </div>
    <!-- <div class="col-sm-6">
      <h6 class="mt-1 text-left text-sm-right" style="font-stretch: ultra-condensed;">
        <a style="color: rgb(60, 72, 88);" href="http://www.ml.cmu.edu/" target="_blank">Principal Researcher</a><br/>
        <a style="color: rgb(60, 72, 88);" href="http://www.cs.cmu.edu/" target="_blank">Semantic Machines</a><br/>
        <a style="color: rgb(60, 72, 88);" href="http://www.cmu.edu/" target="_blank">Microsoft</a>
      </h6>
    </div>
    <div class="col-sm-6">
      <h6 class="mt-1 text-left text-sm-left" style="font-stretch: ultra-condensed;">
        Berkeley Way West, Floor 7<br/>
        1919 Shattuck Ave<br/>
        Berkeley, CA, 94704
      </h6>
    </div> -->
  </div>
</div>

<!-- Introduction -->

<div class="col text-justify p-0">
  I am a Motion Planning Engineer of BYD Ltd. Autonomous Driving Unit, where we are developing a new generation of APA(Automated Parking Assistance), whicle called \(e^4\)APA. I lead the design and development of the parallel slot planner. I am also charged in longitudal planning, parking decision, data interface, algorithm architecture, CI&CD and data analyse.
  <br/><br/>
  Previously, I was a Research & Develop Intern at Momenta.ai, where I participated in the design and development of the world model and new planner for MPilot, which is supplied to Mercedes-Benz and Toyota. 
  <br/><br/>
  Prior to that, I was a Master student in the Control of the <a href="https://www.scs.cmu.edu/" target="_blank">School of Computer Science</a> at Harbin Institute of Technology. My advisor was Linhui Zhao and I worked on motion planning for on-road and openspace environment. My PhD thesis on Motion Planning can be found <a href="{{ '/assets/pdf/thesis/thesis.pdf' | prepend: site.baseurl }}" target="_blank">here</a>. Throughout my PhD I also worked on <a href="{{ '/projects/' }}">multiple other projects</a> related to robotics， planning and control.
  <br/><br/>
  Before I joined HIT, I graduated with a Bachelor in Automation from Dalian Maritime University. I have been awarded the Scholarship for Outstanding Students and the Scholarship for Technological Innovation, and also won an award in the NXP Cup Intelligent Car Race 2019.
</div>

<!-- News -->
<div class="news mt-3 p-0">
  <h1 class="title mb-4 p-0">news</h1>
  {% assign news = site.news | reverse %}
  {% for item in news limit: site.news_limit %}
    <div class="row p-0">
      <div class="col-sm-2 p-0">
        <span class="badge danger-color-dark font-weight-bold text-uppercase align-middle date ml-3">
          {{ item.date | date: "%b %-d, %Y" }}
        </span>
      </div>
      <div class="col-sm-10 mt-2 mt-sm-0 ml-3 ml-md-0 p-0 font-weight-light text">
        <p>{{ item.content | remove: '<p>' | remove: '</p>' | emojify }}</p>
      </div>
    </div>
  {% endfor %}
</div>
