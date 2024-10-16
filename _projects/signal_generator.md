---
layout: page
title: Signal Generator
description: 
img: assets/img/signal_generator/oscilloscope.jpeg
importance: 3
category: school
---

<div class="repo p-2 text-center">
  <a href="https://github.com/nickrallison/robot_hand_ws">
    <img
      class="repo-img-light w-100"
      alt="robot_hand_ws"
      src="https://github-readme-stats.vercel.app/api/pin/?username=nickrallison&repo=robot_hand_ws&theme={{ site.repo_theme_light }}&show_owner={{ show_owner }}&description_lines_count={{ max_lines }}"
    >
    <img
      class="repo-img-dark w-100"
      alt="robot_hand_ws"
      src="https://github-readme-stats.vercel.app/api/pin/?username=nickrallison&repo=robot_hand_ws&theme={{ site.repo_theme_dark }}&show_owner={{ show_owner }}&description_lines_count={{ max_lines }}"
    >
  </a>
</div>

I created a digital signal generator which converted to analog values using an R2R Digital Analog Converter. This version of the project was adapted from a previous project built around the Intel Quartus tool to build whereas this used Verilator, C++ and CMake.

This was able to operate from 1Hz to 1MHz at 1Hz intervals. I was able to achieve this performance by using a linear interpolation core to generate the sine wave from a few sparse samples. This core was also able to use other waveforms such as square, triangle, and sawtooth. These were generated with a python script and loaded in.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/signal_generator/oscilloscope.jpeg" title="waveform" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


