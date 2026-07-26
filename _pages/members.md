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
  margin-bottom: 20px;
}
.tab-button {
  padding: 10px 20px;
  cursor: pointer;
  border: none;
  background: none;
  font-size: 1.1rem;
  font-weight: bold;
  color: #666;
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
</style>

<div class="tab-container">
  <button class="tab-button active" onclick="openTab(event, 'professor')">Professor</button>
  <button class="tab-button" onclick="openTab(event, 'family')">Family</button>
</div>

<!-- Professor Section -->
<div id="professor" class="tab-content active">
  <h2>Professor</h2>
  <p>교수님 소개 내용을 여기에 작성하세요.</p>
</div>

<!-- Family Section -->
<div id="family" class="tab-content">
  <h2>Family</h2>
  <p>연구원 및 학생 소개 내용을 여기에 작성하세요.</p>
</div>

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
