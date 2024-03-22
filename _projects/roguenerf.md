---
layout: page
title: RoGUENeRF - A Robust Geometry-Consistent Universal Enhancer for NeRF 
description:
img: assets/img/roguenerf.png
importance: 2
category: work
images:
  compare: true
  slider: true
---



<center> 

<center> <h5> Sibi Catley-Chandar &nbsp; Richard Shaw &nbsp; Gregory Slabaugh &nbsp; Eduardo Pérez-Pellitero </h5> </center>

</center>

<br>

<center> 

<button class="button" onClick="window.open('https://arxiv.org/abs/2403.11909');">
     <span class="icon">arXiv</span>
</button>

<button class="button" onClick="window.open('https://arxiv.org/pdf/2403.11909');">
     <span class="icon">PDF</span>
</button>

</center>

<br>


<center> <h2> Method </h2> </center>

##### <b>RoGUENeRF is a universal NeRF enhancer which leverages geometry-aware 3D alignment and 2D refinement to enhance any NeRF model while remaining view-consistent and being robust to inaccurate camera poses.</b>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/roguenerf.png" title="architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Method Overview
</div>


<center> <h2> Results </h2> </center>

If videos do not load, please try using Mozilla Firefox or download the video from the viewer. 

<h5>MipNeRF360 - Treehill </h5>


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/compare_ours_mipnerf360_treehill_v2.mp4" class="img-fluid rounded z-depth-1" preload=auto muted=true controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/compare_ours_nerflix_treehill_v2.mp4" class="img-fluid rounded z-depth-1" preload=auto muted=true controls=true autoplay=true %}
    </div>
</div>

<h5>Nerfacto - Garden </h5>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/compare_ours_nerfacto_garden_v2.mp4" class="img-fluid rounded z-depth-1" preload=auto muted=True controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/compare_ours_nerflix_garden_v2.mp4" class="img-fluid rounded z-depth-1" preload=auto muted=True controls=true autoplay=true %}
    </div>
</div>

<h5>NeRF - Trex </h5>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/compare_ours_nerf_trex_v2.mp4" class="img-fluid rounded z-depth-1" preload=auto muted=True controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/compare_ours_nerflix_trex_v2.mp4" class="img-fluid rounded z-depth-1" preload=auto muted=True controls=true autoplay=true %}
    </div>
</div>

<h5>View Consistency</h5>


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/compare_ours_nerflix_garden_view_consistency_v2.mp4" class="img-fluid rounded z-depth-1" preload=auto muted=True controls=true autoplay=true %}
    </div>
</div>


<center> <h5> Nerfacto - Room </h5> </center>

<img-comparison-slider>
  {% include figure.liquid path="assets/img/360_room_0034_input_nerfacto_cropped.png" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/360_room_0034_pred_cropped.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
<div class="caption">
    Nerfacto (left) vs Nerfacto + Ours (right)
</div>

<center> <h5>NeRFLiX - Room </h5> </center>

<img-comparison-slider>
  {% include figure.liquid path="assets/img/360_room_0034_nerflix_cropped.png" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/360_room_0034_pred_cropped.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
<div class="caption">
    Nerfacto + NeRFLiX (left) vs Nerfacto + Ours (right)
</div>

<center><h5>MipNeRF360 - Treehill </h5> </center>

<img-comparison-slider>
  {% include figure.liquid path="assets/img/360_treehill_0410_input.png" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/360_treehill_0410_pred.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
<div class="caption">
    MipNeRF360 (left) vs MipNeRF360 + Ours (right)
</div>

<center><h5>NeRFLiX - Treehill </h5> </center>

<img-comparison-slider>
  {% include figure.liquid path="assets/img/360_treehill_0410_nerflix.png" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/360_treehill_0410_pred.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
<div class="caption">
    MipNeRF360 + NeRFLiX (left) vs MipNeRF360 + Ours (right)
</div>


<center><h5>Large Gaussian Camera Noise - Nerfacto </h5> </center>

<img-comparison-slider>
  {% include figure.liquid path="assets/img/360_garden_0003_input_large.png" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/360_garden_0003_pred_large.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
<div class="caption">
    Nerfacto + Large Camera Noise (left) vs  Nerfacto + Large Camera Noise + Ours (right)
</div>

<center><h5>Large Gaussian Camera Noise - NeRFLiX</h5> </center>

<img-comparison-slider>
  {% include figure.liquid path="assets/img/360_garden_0003_nerflix_large.png" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/360_garden_0003_pred_large.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
<div class="caption">
    Nerfacto + Large Camera Noise + NeRFLiX (left) vs  Nerfacto + Large Camera Noise + Ours (right)
</div>

<center><h5>Medium Gaussian Camera Noise - Nerfacto </h5> </center>

<img-comparison-slider>
  {% include figure.liquid path="assets/img/360_garden_0003_input_med.png" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/360_garden_0003_pred_med.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
<div class="caption">
    Nerfacto + Medium Camera Noise (left) vs  Nerfacto + Medium Camera Noise + Ours (right)
</div>

<center><h5>Medium Gaussian Camera Noise - NeRFLiX</h5> </center>

<img-comparison-slider>
  {% include figure.liquid path="assets/img/360_garden_0003_nerflix_med.png" class="img-fluid rounded z-depth-1" slot="first" %}
  {% include figure.liquid path="assets/img/360_garden_0003_pred_med.png" class="img-fluid rounded z-depth-1" slot="second" %}
</img-comparison-slider>
<div class="caption">
    Nerfacto + Medium Camera Noise + NeRFLiX (left) vs  Nerfacto + Medium Camera Noise + Ours (right)
</div>

```
@article{catleychandar2024roguenerf,
      title={RoGUENeRF: A Robust Geometry-Consistent Universal Enhancer for NeRF}, 
      author={Sibi Catley-Chandar and Richard Shaw and Gregory Slabaugh and Eduardo Perez-Pellitero},
      year={2024},
      eprint={2403.11909},
      journal={arXiv.org}
}
```