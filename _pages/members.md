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

# Yongjae Park

**Assistant Professor**<br>
@ Department of Semiconductor Systems Engineering, Inha University<br>
Principal Investigator of "Atelier of Microelectronics (AME)"<br>
**Office:** TBD<br>
**Email:** yong27.park@inha.ac.kr<br>
**Research Interests:**
- Biomedical Wearable Sensors / Neural Interfaces / High-Precision Analog Front-Ends
- Time-of-Flight Imager
- High-Speed Interfaces / Silicon Photonics<br>

**Publications:** [Google Scholar](https://scholar.google.com)

### Experiences

- **Assistant Professor**, Inha University, Korea *(2026 – Present)*

- **Staff Engineer**, IP Development Team, Samsung Electronics *(2024 – 2026)*
  - Electrical IC (EIC) Design for Silicon Photonics
  - Custom Die-to-Die (D2D) Interface Design

- **Visiting Researcher**, University of California San Diego (UCSD), United States *(2022 – 2023)*
  - Neural Recording and Stimulation SoC Design

### Education

- **Ph.D.**, Electrical Engineering, Ulsan National Institute of Science and Technology (UNIST), 2024
- **B.S.**, Electrical Engineering, Ulsan National Institute of Science and Technology (UNIST), 2018

### Activities

- **Journal / Conference Reviewer**
  - IEEE Journal of Solid-State Circuits (JSSC)
  - IEEE Transactions on Biomedical Circuits and Systems (TBioCAS) *(Best Reviewer, 2026)*
  - IEEE International Symposium on Circuits and Systems (ISCAS)
  - IEEE Biomedical Circuits and Systems (BioCAS)

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
