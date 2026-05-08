---
layout: home
# title: After Hours Sidequests
---

Welcome to After Hours Sidequests.

This is a personal build log for small engineering projects, prototypes, and experiments. Mostly embedded systems, robotics, control systems, CAD, and things that started as quick ideas but turned into longer side quests.

## Current Builds

<div style="
display:grid;
grid-template-columns:repeat(3, 1fr);
gap:30px;
margin-top:30px;
">

<div>

<h3>
  <a href="{{ '/projects/clock/' | relative_url }}">
    ESP8266 OLED Clock
  </a>
</h3>

<a href="{{ '/projects/clock/' | relative_url }}">
  <img
    src="{{ '/assets/images/clock/thumbnail.jpeg' | relative_url }}"
    alt="ESP8266 OLED Clock thumbnail"
    style="
      width:100%;
      max-width:320px;
      border-radius:10px;
    ">
</a>

<p>
Wi-Fi synchronized desk clock using an ESP8266 D1 Mini and SSD1306 OLED display.
</p>

</div>

<div>

<h3>Rover Project</h3>

<img
  src="{{ '/assets/images/placeholder.jpg' | relative_url }}"
  alt="Rover placeholder"
  style="
    width:100%;
    max-width:320px;
    border-radius:10px;
  ">

<p>
Incremental robotics project focused on sensing, motion control, and embedded systems.
</p>

</div>

<div>

<h3>Future Project</h3>

<img
  src="{{ '/assets/images/placeholder.jpg' | relative_url }}"
  alt="Future project placeholder"
  style="
    width:100%;
    max-width:320px;
    border-radius:10px;
  ">

<p>
More side quests coming soon.
</p>

</div>

</div>