---
layout: page_AR
title: augmented reality
permalink: /ar/
description: 
nav: true
nav_order: 2
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


## Crystal Structures 


<img src="/assets/img/AR_Instructions.png" alt="Grid Overview Image" class="header-image">

### HCP ABA Packing
<model-viewer alt="Hex_Packing" src="http://softtissuebiomechanicslab.github.io/assets/ASE324L/Packing_Hex.glb" ar ar-modes="webxr scene-viewer quick-look" ar-scale="auto" camera-controls>
</model-viewer>
<div class="progress-bar hide" slot="progress-bar">
        <div class="update-bar"></div>
    </div>

### FCC ABC Packing
<model-viewer alt="FCP_Structure" src="/assets/ar_models/Crystal_Structures/GLB_Files/Packing_FCP_Compressed.glb" ar ar-modes="webxr scene-viewer quick-look" ar-scale="auto" camera-controls>
</model-viewer>

### HCP 
<model-viewer alt="HCP_Structure" src="/assets/ar_models/Crystal_Structures/GLB_Files/HCP_Atoms_Compressed.glb" ar ar-modes="webxr scene-viewer quick-look" ar-scale="auto" camera-controls>
</model-viewer>

#### FCC 
<model-viewer alt="FCC_Structure" src="/assets/ar_models/Crystal_Structures/GLB_files/FCC_Atoms_Compressed.glb" ar ar-modes="webxr scene-viewer quick-look" ar-scale="auto" camera-controls>
</model-viewer>

### BCC
<model-viewer alt="BCC_Structure" src="/assets/ar_models/Crystal_Structures/GLB_Files/BCC_Atoms_Compressed.glb" ar ar-modes="webxr scene-viewer quick-look" ar-scale="auto" camera-controls>
    </model-viewer>

### SC
<model-viewer alt="SCC_Structure" src="/assets/ar_models/Crystal_Structures/GLB_Files/SCC_Atoms_Compressed.glb" ar ar-modes="webxr scene-viewer quick-look" ar-scale="auto" camera-controls>
    </model-viewer>


<!--
<div class="grid-container">

  <div>
    <div class="model-caption">HCP ABA-Packing</div>
    <model-viewer alt="Hex_Packing" src="/assets/ar_models/Crystal_Structures/GLB_Files/Packing_Hex_Compressed.glb" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>

  <div>
    <div class="model-caption">FCC ABC-Packing</div>
    <model-viewer alt="FCP_Structure" src="/assets/ar_models/Crystal_Structures/GLB_Files/Packing_FCP_Compressed.glb" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>

 
  <div>
    <div class="model-caption">HCP</div>
    <model-viewer alt="HCP_Structure" src="/assets/ar_models/Crystal_Structures/GLB_Files/HCP_Atoms_Compressed.glb" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>
 

  <div>
    <div class="model-caption">FCC</div>
    <model-viewer alt="FCC_Structure" src="/assets/ar_models/Crystal_Structures/GLB_files/FCC_Atoms_Compressed.glb" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>

  <div>
    <div class="model-caption">BCC</div>
    <model-viewer alt="BCC_Structure" src="/assets/ar_models/Crystal_Structures/GLB_Files/BCC_Atoms_Compressed.glb" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>

  <div>
    <div class="model-caption">SC</div>
    <model-viewer alt="SCC_Structure" src="/assets/ar_models/Crystal_Structures/GLB_Files/SCC_Atoms_Compressed.glb" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
    </model-viewer>
  </div>

</div>



## Model Viewer Integration


<model-viewer alt="OCS13_AR Model" src="/assets/ar_models/OCS13/OCS13_1015_elset.glb" ar  shadow-intensity="1" camera-controls touch-action="pan-y">
</model-viewer>

-->





