---
layout: custom_home
title: "Home"
---

Our laboratory focuses on studying the intersection between urbanization, socioeconomic inequities and infectious diseases.

<div class="photo-grid">
  <img src="{{ '/assets/ko-lab.jpg' | relative_url }}" alt="Ko Group">
  <img src="{{ '/assets/mosquitorat.png' | relative_url }}" alt="Mosquito and rat">
  <img src="{{ '/assets/lab2.jpg' | relative_url }}" alt="Photo 3">
  <img src="{{ '/assets/lab3.jpg' | relative_url }}" alt="Photo 4">
  <img src="{{ '/assets/test.jpg' | relative_url }}" alt="Photo 5">
  <img src="{{ '/assets/test.jpg' | relative_url }}" alt="Photo 6">
</div>

<style>
.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 10px;
  margin-top: 20px;
}

.photo-grid img {
  width: 100%;
  height: auto;
  border-radius: 5px; /* Optional: Add rounded corners */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2); /* Optional: Add slight shadow */
}
</style>