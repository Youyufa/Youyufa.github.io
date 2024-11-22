---
layout: page
permalink: /
title: home
nav: home
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

  I am a Motion Planning Engineer of BYD Ltd. Autonomous Driving Unit, where we are developing a Parking Assistance for 4WD vehicle, whicle called E4APA. 
  <br/><br/>
  Previously, I was an Algorithm Intern at Momenta Tech Ltd., where I participated in the MPilot Self-Driving Project, which supplied to Mercedes-Benz and Toyota. 
  <br/><br/>
  Prior to that, I was a M.E. student at Harbin Institute of Technology, advised by Linhui Zhao. I worked on vehicle motion planning for on-road and openspace scenes. My M.S. thesis can be found here: <a class="ml-auto mr-2" href="/assets/pdf/thesis.pdf" target="_blank">
    <img height="30px" src="/assets/img/pdf_icon.svg"></a>
  <br/><br/>
  Before I joined HIT, I won a national award in the NXP Cup Intelligent Car Race 2019.
   <br/><br/>
  Here is my CV: <a class="ml-auto mr-2" href="/assets/pdf/resume.pdf" target="_blank">
    <img height="30px" src="/assets/img/pdf_icon.svg"></a>
</div>

<!-- News -->
<div class="news mt-3 p-0">
  <h1 class="title mb-4 p-0">publications</h1>
  [1] Y. You, L. Zhao, H. Liu and Z. Liu, "A Hybrid Trajectory Planning Strategy for Intelligent Vehicles with Collision Avoidance," 2022 41st Chinese Control Conference (CCC), Hefei, China, 2022, pp. 5353-5358, doi: 10.23919/CCC55666.2022.9901901.<a class="ml-auto mr-2" href="/assets/pdf/ccc.pdf" target="_blank">
    <img height="30px" src="/assets/img/pdf_icon.svg"></a>
</div>

<!-- News -->
<div class="news mt-3 p-0">
  <h1 class="title mb-4 p-0">news</h1>
  {% assign news = site.news | reverse %}
  {% for item in news limit: site.news_limit %}
    <div class="row p-0">
      <div class="col-sm-2 p-0">
        <span class="badge black font-weight-bold text-uppercase align-middle date ml-3">
          {{ item.date | date: "%b %-d, %Y" }}
        </span>
      </div>
      <div class="col-sm-10 mt-2 mt-sm-0 ml-3 ml-md-0 p-0 font-weight-light text">
        <p>{{ item.content | remove: '<p>' | remove: '</p>' | emojify }}</p>
      </div>
    </div>
  {% endfor %}
</div>
