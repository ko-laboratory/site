---
layout: custom_home
title: "Home"
---

<div style="font-size: 1.5rem; margin-bottom: 20px;">
The Ko Laboratory works at the intersection of urbanization, socioeconomic inequities and infectious diseases.
</div>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer elementum ornare lectus, in dapibus sapien dignissim ut. Vivamus cursus ornare mi, at tincidunt nunc laoreet sed. Ut ullamcorper feugiat convallis. Ut pharetra est eu mauris facilisis, nec posuere metus mollis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Proin ligula erat, ultricies vitae lacus sit amet, commodo ornare orci. Quisque eu est in metus iaculis rutrum a a dolor. Nulla nec velit ac ligula volutpat mollis.

<div class="photo-grid">
    <div class="photo-cell">
        <img src="{{ '/assets/ko-lab.jpg' | relative_url }}" alt="Ko Group">
    </div>
    <div class="photo-cell">
        <img src="{{ '/assets/mosquitorat.png' | relative_url }}" alt="Mosquito and rat">
    </div>
    <div class="photo-cell">
       <img src="{{ '/assets/lab2.jpg' | relative_url }}" alt="Photo 3">
    </div>
    <div class="photo-cell">
        <img src="{{ '/assets/lab3.jpg' | relative_url }}" alt="Photo 4">
    </div>
    <div class="photo-cell">
        <img src="{{ '/assets/test.jpg' | relative_url }}" alt="Photo 5">
    </div>
    <div class="photo-cell">
        <img src="{{ '/assets/test.jpg' | relative_url }}" alt="Photo 6">
    </div>
    <div class="photo-cell">
        <img src="{{ '/assets/test.jpg' | relative_url }}" alt="Photo 6">
    </div>
    <div class="photo-cell">
        <img src="{{ '/assets/test.jpg' | relative_url }}" alt="Photo 6">
    </div>
    <div class="photo-cell">
        <img src="{{ '/assets/test.jpg' | relative_url }}" alt="Photo 6">
    </div>
</div>

<style>
.photo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 10px;
  margin-top: 20px;
}

.photo-cell {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
}

.photo-grid img {
  max-width: 100%;
  max-height: 100%;
  border-radius: 3px; /* Optional: Add rounded corners */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2); /* Optional: Add slight shadow */
}
</style>