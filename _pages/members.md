---
layout: archive
title: "Members"
permalink: /members/
author_profile: true
---

<style>
.tab-container {
  display: flex;
  border-bottom: 2px solid #e0e0e0;
  margin-bottom: 25px;
}
.tab-button {
  padding: 10px 25px;
  cursor: pointer;
  border: none;
  background: none;
  font-size: 1.15rem;
  font-weight: bold;
  color: #666;
  transition: all 0.2s ease;
}
.tab-button.active {
  color: #000;
  border-bottom: 3px solid #000;
}
.tab-content {
  display: none;
}
.tab-content.active {
  display: block;
}
.member-card {
  margin-bottom: 25px;
}
.member-card img {
  border-radius: 50%;
  margin-right: 20px;
  object-fit: cover;
}
</style>

<!-- 탭 버튼 -->
<div class="tab-container">
  <button class="tab-button active" onclick="openTab(event, 'professor')">Professor</button>
</div>

<!-- ================= 1. PROFESSOR TAB ================= -->
<div id="professor" class="tab-content active">
  <div class="member-card">
    <!-- <img src="/images/professor.jpg" width="160" height="160" align="left" alt="Professor"> -->
    <h2>Yongjae Park</h2>
    <p><strong>Assistant Professor</strong><br>
    - Department of Semiconductor Systems Engineering, Inha University<br>
    - Principal Investigator of "Atelier of Microelectronics (AME)"<br>
    <strong>Office:</strong> TBD<br>
    <strong>Email:</strong> yong27.park@inha.ac.kr<br>
    <strong>Publications:</strong> <a href="https://scholar.google.com">[Google Scholar]</a>
    </p>

    <h3><i>Education</i></h3>
    <ul>
      <li><strong>Ph.D.</strong> in Electrical Engineering, Ulsan National Institute of Science and Technology (UNIST), 2024</li>
      <li><strong>B.S.</strong> in Electrical Engineering, Ulsan National Institute of Science and Technology (UNIST), 2018</li>
    </ul>
      
    <h3><i>Experiences</i></h3>
    <ul>
      <li>
        <strong>Assistant Professor @ Inha University, Korea, 2026 - Present</strong>
      </li>
      <li><strong>Staff Engineer @ IP Development Team, Samsung Electronics, Korea, 2024 - 2026</strong><br>
        &nbsp;&nbsp;– Electrical IC (EIC) Design for Silicon-Photonics<br>
        &nbsp;&nbsp;– Custom Die to Die (D2D) Interface Design
      </li>
      <li><strong>Visiting Researcher @ University of California San Diego (UCSD), United States, 2022 - 2023</strong><br>
        &nbsp;&nbsp;– Neural Recording and Stimulation SoC Design
      </li>
    </ul>

    <h3><i>Research Interests</i></h3>
    <ul>
      <li>Biomedical Wearable Sensors / Neural Interfaces / High-Precision Analog-Front-Ends</li>
      <li>Time-of-Flight Imager</li>
      <li>High-Speed Interfaces / Silicon-Photonics</li>
    </ul>

    <h3><i>Activities</i></h3>
    <ul>
      <li><strong>Journals/Conferences Review</strong><br>
        &nbsp;&nbsp;– <i>IEEE Journal of Solid-State Circuits (JSSC)</i><br>
        &nbsp;&nbsp;– <i>IEEE Transactions on Biomedical Circuits and Systems (TBioCAS)</i><br>
        &nbsp;&nbsp;– <i>IEEE International Symposium on Circuits and Systems (ISCAS)</i><br>
        &nbsp;&nbsp;– <i>IEEE Biomedical Circuits and Systems (BioCAS)</i><br>
      </li>
    </ul>

    <h3><i>Honors/Grants</i></h3>
    <ul>
      <li>2023-2024 Pre-Doctoral Achievement Award<br>
        &nbsp;&nbsp;<i>Granted by IEEE Solid-State Circuits Society (SSCS)</i> [<a href="https://sscs.ieee.org/membership/awards/predoctoral-achievement-award/">IEEE SSCS</a>]<br>
      </li>
      <li>2026 Best Reviewer<br>
        &nbsp;&nbsp;<i>IEEE Transactions on Biomedical Circuits and Systems (TBioCAS)</i> [<a href="https://ieee-cas.org/post/news/ieee-cass-announces-2026-publications-best-associate-editor-and-best-reviewer-award">IEEE CAS</a>]<br>
      </li>
    </ul>
  </div>
</div>

<!-- ================= 2. FAMILY TAB ================= -->
<div id="family" class="tab-content">

<!--
  <h2>Ph.D. Students</h2>

  <div class="member-card">
    <img src="/images/avatar.jpg" width="110" height="110" align="left" alt="Gildong Hong">
    <h3>Gildong Hong (홍길동)</h3>
    <p><strong>Ph.D. Candidate</strong> (2022.03 ~ Present)<br>
    <strong>Research Interest:</strong> High-Efficiency DC-DC Converters<br>
    <strong>Email:</strong> gdhong@university.ac.kr<br>
    <a href="https://scholar.google.com">[Google Scholar]</a></p>
  </div>
  <br clear="all">
-->

</div>

<!-- ================= TAB SCRIPT ================= -->
<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tab-content");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tab-button");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>
