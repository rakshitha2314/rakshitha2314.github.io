---
permalink: /teaching/
title: "Teaching"
---

<div class="project-list">
  <!-- Project 1 -->
<div class="project">
    <h3 class="project-title">
      Teaching Assistant, <a href="" target="_blank">MTL103 - Optimization Methods and Applications</a> 
      <br>[Semester-II, 2024-25]
    </h3>
    <p class="contributors"><strong>Professor.</strong> Ashutosh Rai</p>
  </div>
  <hr>

  <!-- Project 2 -->
<div class="project">
    <h3 class="project-title">
      Teaching Assistant, <a href="https://sites.google.com/view/dalujacob/teaching/analysis-and-design-of-algorithms?authuser=0" target="_blank">MTL342 - Analysis and Design of Algorithms</a> 
      <br>[Semester-I, 2024-25]
    </h3>
    <p class="contributors"><strong>Professor.</strong> Dalu Jacob</p>
  </div>
  <hr>

  
</div>

<script>
function toggleAbstract(abstractId, button) {
  const abstract = document.getElementById(abstractId);

  if (abstract.classList.contains("hidden")) {
    abstract.classList.remove("hidden");
    abstract.style.display = "block"; // Ensure visibility
    button.innerText = "Hide Abstract";
  } else {
    abstract.classList.add("hidden");
    abstract.style.display = "none"; // Hide the content
    button.innerText = "View Abstract";
  }
}
</script>

<style>
/* General Styles */
body {
  /* font-family: 'Arial', sans-serif; */
  line-height: 1.6;
  color: #333;
}

.project-list {
  max-width: 800px;
  margin: 30px auto;
  padding: 0 20px;
}

.project {
  margin-bottom: 20px;
}

.project-title {
  font-size: 18px;
  font-weight: bold;
  color: #222;
}

.contributors {
  margin: 5px 0 10px;
  font-size: 15px;
  color: #555;
}

.toggle-abstract {
  background-color: #f8f8f8;
  color: #555;
  border: 1px solid #ccc;
  padding: 6px 12px;
  font-size: 14px;
  border-radius: 4px;
  cursor: pointer;
  transition: background-color 0.3s, color 0.3s, border-color 0.3s;
}

.toggle-abstract:hover {
  background-color: #e8e8e8;
  color: #222;
  border-color: #999;
}

.abstract-content {
  margin-top: 10px;
  font-size: 15px;
  color: #444;
  line-height: 1.6;
  border-left: 3px solid #ddd;
  padding-left: 10px;
  display: none; /* Hidden by default */
}

.project-link {
  color: #007acc;
  text-decoration: none;
  font-weight: bold;
}

.project-link:hover {
  text-decoration: underline;
}

hr {
  border: 0;
  border-top: 1px solid #ddd;
  margin: 20px 0;
}
</style>