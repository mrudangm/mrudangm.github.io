---
layout: page_AR
title: augmented reality
permalink: /ar/
description: 
nav: true
nav_order: 3
display_categories: [work, fun]
horizontal: false
---


<style>
  .grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1rem;
    margin-top: 2rem;
  }

  model-viewer {
    width: 100%;
    height: 300px;
    background-color: #ffffff;
    border-radius: 8px;
    border: 0px solid #ccc;
  }

  .model-caption {
    text-align: center;
    font-weight: 800;
    margin-top: 0.5rem;
    font-familt: inherit
  }

    .header-image {
    display: block;
    width: 100%;
    max-width: 100%;
    height: auto;
    margin: 2rem auto 1rem;
    border-radius: 8px;
    }
</style>

 I developed augmented reality models for scientific visualization to help students at UT-Austin better understand **[crystal structures](https://en.wikipedia.org/wiki/Crystal_structure)** (see below). Given the impact of these models, I **independently conducted workshops** at the 17<sup>th</sup> US National Congress for Computational Mechanics ([USNCCM17](https://17.usnccm.org/)) and the Summer Bioengineering, Biomechanics, & Biotransport Conference ([SB3C](https://archive.sb3c.org/sb3c2023/)), to share my methods with the scientific community. I've also **[published](https://static1.squarespace.com/static/562c1058e4b0f8ea949c2a94/t/635d5c7a227cca7a1389205e/1667062908130/FEAD22.pdf)** these techniques and **[open-sourced]((https://github.com/SoftTissueBiomechanicsLab/AR_Pipeline)**)** the corresponding code. As a result, these methods are now integrated into the mechanics of materials curriculum at **UT-Austin (ASE324L)** as well as **MIT ([2.002](https://portela.mit.edu/2-002-design-challenge-2025/))** and are used internationally by researchers at **[ETH-Zurich](https://www.sciencedirect.com/science/article/pii/S001379442400482X)** and **[TU-Delft](https://peirlincklab.com/ar/)**. 

Scan the QR code below to begin!


## Crystal Structures 


<img src="/assets/img/AR_Instructions.png" alt="Grid Overview Image" class="header-image">


<div class="grid-container">

  <div>
  <div class="model-caption">HCP ABA Packing</div>
    <model-viewer alt="Hex_Packing" src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/Packing_Hex.glb" ios-src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/Packing_Hex.usdz" ar ar-modes="webxr scene-viewer quick-look" ar-scale="auto" camera-controls>
</model-viewer>
  </div>

  <div>
    <div class="model-caption">FCC ABC Packing</div>
    <model-viewer alt="FCP_Packing" src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/Packing_FCP.glb" ios-src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/Packing_FCP.usdz" ar ar-modes="webxr scene-viewer quick-look" ar-scale="auto" camera-controls>
</model-viewer>
  </div>
 
  <div>
    <div class="model-caption">HCP</div>
    <model-viewer alt="HCP_Structure" src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/HCP_Atoms.glb" ios-src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/HCP_Atoms.usdz" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>
 

  <div>
    <div class="model-caption">FCC</div>
    <model-viewer alt="FCC_Structure" src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/FCC_Atoms.glb" ios-src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/FCC_Atoms.usdz" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>

  <div>
    <div class="model-caption">BCC</div>
    <model-viewer alt="BCC_Structure" src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/BCC_Atoms.glb" ios-src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/BCC_Atoms.usdz" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>

  <div>
    <div class="model-caption">SC</div>
    <model-viewer alt="SCC_Structure" src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/SCC_Atoms.glb" ios-src="https://softtissuebiomechanicslab.github.io/assets/ASE324L/SCC_Atoms.usdz" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>

</div>


<!--
<model-viewer alt="OCS13_AR Model" src="/assets/ar_models/OCS13/OCS13_1015_elset.glb" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
</model-viewer>
-->





