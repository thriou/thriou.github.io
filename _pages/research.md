---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<style>
  .research-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 25px;
    margin-top: 20px;
  }
  .research-card {
    border: 1px solid #e0e0e0;
    border-radius: 6px;
    padding: 20px;
    background-color: #fafafa;
  }
  .video-container {
    display: flex;
    gap: 10px;
    margin-bottom: 15px;
  }
  .video-box {
    flex: 1;
    text-align: center;
  }
  .video-box video {
    width: 100%;
    border-radius: 4px;
    background-color: #000;
  }
  .video-caption {
    font-size: 0.85em;
    color: #555;
    margin-top: 5px;
  }
  .pub-ref {
    font-style: italic;
    color: #666;
    margin-bottom: 10px;
  }
</style>

<div class="research-grid">

  <!-- PROJET 1 -->
  <div class="research-card">
    <h3>Hydrogen Injector Dynamics</h3>
    <p class="pub-ref">Corresponding publications: [Riou et al., 2026]</p>
    
    <div class="video-container">
      <div class="video-box">
        <video controls>
          <source src="{{ base_path }}/files/video1.mp4" type="video/mp4">
        </video>
        <div class="video-caption">Flame lift-off dynamics</div>
      </div>
      <div class="video-box">
        <video controls>
          <source src="{{ base_path }}/files/video2.mp4" type="video/mp4">
        </video>
        <div class="video-caption">Thermoacoustic instabilities</div>
      </div>
    </div>

    <ul>
      <li>Numerical simulation of transient dynamics in aircraft injectors</li>
      <li>Anchoring and lift-off dynamics in hydrogen dual-swirl burners</li>
      <li>Combustion noise analysis</li>
    </ul>
  </div>

  <!-- PROJET 2 -->
  <div class="research-card">
    <h3>Viscoelastic Duct Flows</h3>
    <p class="pub-ref">Corresponding publications: [McDermott et al., 2023]</p>
    
    <div class="video-container">
      <div class="video-box">
        <video controls>
          <source src="{{ base_path }}/files/video3.mp4" type="video/mp4">
        </video>
        <div class="video-caption">Drag reduction in pipe</div>
      </div>
    </div>

    <ul>
      <li>Anisotropic $k\text{-}\epsilon\text{-}v^2\text{-}f$ model</li>
      <li>OpenFoam implementation for viscoelastic fluids</li>
      <li>Turbulence calibration for drag reduction</li>
    </ul>
  </div>

</div>
