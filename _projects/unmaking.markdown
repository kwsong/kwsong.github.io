---
layout: page
title: unmaking
description: celebrating the creative material of destruction
img: /assets/img/unmaking.png
importance: 4
category: HCI
---
<div class="row justify-content-sm-center">
        <img src="{{ '/assets/img/unmaking.png' | relative_url }}" alt="" title="unmaking" width="600"/>
</div>
<br><br>
The access and growing ubiquity of digital fabrication has ushered in a celebration of creativity and "making."  However, the focus is often on the resulting static artifact or the creative process and tools to design it. We envision a post-making process that extends past these final static objects – not just in their making but in their "unmaking."  By drawing from artistic movements such as Auto-Destructive Art, intentionally inverting well-established engineering principles of structurally sound designs, and safely misusing unstable materials, we demonstrate an important extension to making – unmaking.  Unmaking is an emerging topic of interest in multiple sub-communities of HCI -- including digital fabrication, critical design, and STS -- that intersects with issues of sustainability, reusability, and more-than-human design. It is the central topic of a CHI2022 workshop, an upcoming CHI2024 workshop, and a TOCHI Special Issue.

My interest in unmaking in particular is in creating the materials combinations, fabrication workflows, and software tools so that designers may build in unmaking effects during the time of conception for their designs. In our CHI2021 paper, we provide designers with a new vocabulary of unmaking operations within standard 3D modeling tools.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vocabulary.png" title="unmaking" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Proposed vocabulary for unmaking operations.
</div>
</center>

We demonstrate how such designs can be realized using a novel multi-material 3D printing process. For our exemplar workflow, we implement splitting and bulging operations in PLA objects by selectively printing chambers of thermally expanding microspheres.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/microspheres.gif" title="unmaking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Thermally expanding microspheres expand to over 60x their original volume when exposed to heat.
</div>
</center>

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_voxel8.png" width="600px" title="unmaking" %}
    </div>
</div>
<div class="caption">
    Microspheres printed alongside PLA in an FDM 3D printer.
</div>
</center>

After printing, objects appear to be normal 3D-printed PLA objects, but upon exposure to heat, they split or bulge as the designer intended.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/bulgesplit.gif" title="unmaking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Example splitting and bulging in response to heat.
</div>
</center>

We also created a custom Blender plug-in that allows designers to visualize splitting and bulging effects when designing objects to print. The plugin automatically modifies the model to include chambers of microspheres, and a custom slicer generates the appropriate gcode for the 3D printer.
<center><div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/unmakingswtool.gif" title="unmaking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Unmaking software tool.
</div>
</center>

With other materials -- such as those that dissolve in water, rust, or can be consumed by organic matter -- and other fabrication strategies -- such as intentionally printing weak layers or building in internal structures that allow two chemical reagents to combine when the object is handled in a certain way -- many more unmaking effects are possible.
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_unmaking_horizontal.png" title="example image" class="img-fluid" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/bakingsoda.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    More unmaking effects with different materials and fabrication strategies.
</div>

<div class="publications">
  <h2>publications</h2>
  {% bibliography -f papers -q @*[category=unmaking]* %}
</div>
