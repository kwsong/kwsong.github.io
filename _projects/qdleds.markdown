---
layout: page
title: Quantum Dot LEDs
description: MIT ONE Lab, 2011-2013
img: /assets/img/qdleds.png
importance: 5
category: micro/nano electronics
---

<div class="row justify-content-sm-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/qdleds.jpg' | relative_url }}" alt="" title="QD-LEDs"/>
</div>
<br><br>
Between 2011 and 2013, I conducted research as a PhD student with Professor Vladimir Bulović in the <a href="http://onelab.mit.edu" target="_blank">Organic and Nanostructured Laboratory</a> at MIT. While I also dabbled in various project such as fabricating OLEDs on paper and plastic substrates, my research focus was on quantum dot light emitting devices (QD-LEDs). I summarize two related projects here.

<h2>Electrophoretic deposition of quantum dots for light emitting devices</h2>

<div class="row justify-content-sm-center">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/epd.png' | relative_url }}" alt="" title="EPD of QDs"/>
</div>
<div class="caption">
    (a) Schematic depiction of the electrophoretic deposition process. A voltage applied between two parallel, conducting electrodes spaced 0.4 cm apart drives the deposition of the particles (QDs). (b) AFM topography image of the surface of an electrophoretically deposited QD film with RMS roughness of 2.3 nm.
</div>

QD-LEDs are promising options for the next generation of solid state lighting, color displays, and other optoelectronic applications. Overcoating quantum dots (QDs) – semiconducting nanocrystals of CdSe, PbS, or another similar compound – with a wide band-gap "shell" has recently been shown to significantly boost QD-LED performance and yield the most efficient QD-LEDs to date. In this project, I, in collaboration with Dr. Ronny Costi, a post-doc in the lab, invented a technique to electrophoretically deposit (EPD) CdSe/ZnS core-shell QDs to make bright, efficient QD-LEDs. QD-LEDs conventionally utilize a QD ﬁlm that is deposited via spin-casting, a reliable but highly unscalable technique for the deposition of thin, smooth films of QDs for QD-LED applications. Potential advantages of EPD include the ability for deposition onto a variety of substrate shapes and more energetically favorable QD packing. We were able to create devices made with EPD QD films that exhibit peak efficiencies comparable to those of devices with a spun-cast QD layer and turn-on voltages surprisingly lower than the optical band-gap of the QDs. These results suggest that EPD is a viable alternative to spin-casting for the processing of QD-LEDs.


<h2>Near-infrared quantum dot LEDs</h2>

<div class="row justify-content-sm-center">
        <img src="{{ '/assets/img/irqdleds.png' | relative_url }}" alt="" title="near-IR QD-LEDs" width="90%" height="90%"/>
</div>

In collaboration with a fellow graduate student, Geoffrey Supran, I next explored the role of core-shell QDs in creating bright, efficient LEDs in the near-infrared (λ > 1 µm) regime. We designed and fabricated infrared QD-LEDs with record brightness and efficiencies by using QDs in which lead sulfide (PbS) cores were overcoated with a cadmium sulfide (CdS) shell. In-situ photoluminescence quantum yield measurements confirmed that the QD shell plays a significant role in shielding the emissive QD core from external quenching mechanisms.


<div class="publications">
  <h2>publications</h2>
  {% bibliography -f papers -q @*[category=qdleds]* %}
</div>
