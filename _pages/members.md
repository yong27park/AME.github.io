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
  <button class="tab-button" onclick="openTab(event, 'family')">Family</button>
</div>

<!-- ================= 1. PROFESSOR TAB ================= -->
<div id="professor" class="tab-content active">
  <div class="member-card">
    #<img src="/images/professor.jpg" width="160" height="160" align="left" alt="Professor">
    <h2>Yongjae Park</h2>
    <p><strong>Assistant Professor</strong><br>
    Department of Semiconductor Systems Engineering<br>
    Principle Investigator of Atelier of Microelectronics (AME)<br><br>
    <strong>Office:</strong> TBD<br>
    #<strong>Tel:</strong> +82-2-1234-5678<br>
    <strong>Email:</strong> yong27.park@inha.ac.kr<br>
    #<a href="/files/cv.pdf">[Download CV]</a> <a href="https://scholar.google.com">[Google Scholar]</a></p>
  </div>
  <br clear="all">

  <hr>

  <h3>Education</h3>
  <ul>
    <li><strong>Ph.D.</strong> in Electrical Engineering, KAIST, 2018</li>
    <li><strong>M.S.</strong> in Electrical Engineering, KAIST, 2014</li>
    <li><strong>B.S.</strong> in Electrical Engineering, Seoul National University, 2012</li>
  </ul>

  <h3>Research Interests</h3>
  <ul>
    <li>Analog & Mixed-Signal Integrated Circuit Design</li>
    <li>Power Management ICs (PMIC)</li>
    <li>High-Speed Transceiver Interfaces</li>
  </ul>
</div>

<!-- ================= 2. FAMILY TAB ================= -->
<div id="family" class="tab-content">

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

  <div class="member-card">
    <img src="/images/avatar.jpg" width="110" height="110" align="left" alt="John Doe">
    <h3>John Doe</h3>
    <p><strong>Ph.D. Student</strong> (2024.03 ~ Present)<br>
    <strong>Research Interest:</strong> Low-Power Analog-to-Digital Converters (ADC)<br>
    <strong>Email:</strong> johndoe@university.ac.kr</p>
  </div>
  <br clear="all">

  <hr>

  <h2>M.S. Students</h2>

  <div class="member-card">
    <img src="/images/avatar.jpg" width="110" height="110" align="left" alt="Younghee Kim">
    <h3>Young-Hee Kim (김영희)</h3>
    <p><strong>M.S. Student</strong> (2024.09 ~ Present)<br>
    <strong>Research Interest:</strong> High-Speed SerDes Link Interfaces<br>
    <strong>Email:</strong> yhkim@university.ac.kr</p>
  </div>
  <br clear="all">

  <hr>

  <h2>Alumni</h2>

  <h3>M.S. Graduates</h3>
  <ul>
    <li><strong>Min-Soo Park (박민수)</strong> - Graduated Feb 2025 (Thesis: <i>A 10-bit SAR ADC Design</i>) / Currently at Samsung Electronics</li>
    <li><strong>Jane Smith</strong> - Graduated Aug 2024 / Currently at SK Hynix</li>
  </ul>

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
