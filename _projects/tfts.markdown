---
layout: page
title: Flexible Large-Area Electronics
description: Princeton University, 2009-2011
img: /assets/img/flexTFTs.png
importance: 6
category: micro/nano electronics
---
As an undergraduate at Princeton University, I conducted research in the domain of large-area electronics under the guidance of Professors Sigurd Wagner and, in my senior year, Naveen Verma.

Starting in the spring of my sophomore year, my first project was to characterize the mechanical flexibility of hydrogenated amorphous silicon (a-Si:H) thin-film transistors (TFTs) that were fabricated with a new gate dielectric material that had previously been developed in the lab as an encapsulation layer for organic light-emitting diodes (OLEDs). a-Si:H TFTs are conventionally made with a silicon nitride (SiN<sub>x</sub>) gate dielectric, and while this material is generally electrically impermeable, it is also very stiff and thus limits the overall flexibility of the devices and subsequent applications (e.g. flat panel displays). The new gate dielectric is a silicon dioxide (SiO<sub>2</sub>)-silicone "hybrid" insulator that had recently been found to possess both the electrical insulation properties characteristic of inorganic materials and the mechanical flexibility of organic materials. TFTs made with the new dielectric exhibit electron mobilities of 2 cm<sup>2</sup> / V-s - roughly twice that of conventional a-Si:H/SiN<sub>x</sub> TFTs. I found the resulting TFTs to be very flexible, recovering from tensile strains of up to 2.5% (corresponding to bending around a radius of 1 mm).

<div class="row justify-content-sm-center">
  <img src="{{ '/assets/img/bending.jpg' | relative_url }}" alt="flexible TFTs" title="flexible TFTs" width="60%" height="60%" class="rounded z-depth-1"/>
</div>

<div class="caption">
    Flexible TFTs bent around a drill bit
</div>

I then fabricated and characterized TFTs made with the new dielectric in a top-gate staggered geometry. The bottom-gate staggered geometry is conventional in a-Si:H TFT research because it yields the highest electron mobility. However, the top-gate staggered geometry is of interest because it is less complex to fabricate (fewer required photolithography masks and easier to integrate into display circuitry. Furthermore, we were interested in the effect of layer growth sequence on the performance of TFTs with our new gate dielectric material. The resulting top-gate TFTs exhibited an effective electron mobility of ~0.5 cm<sup>2</sup> / V-s, a threshold voltage of ~1.5 V, and an on-off current ratio of ~106, values that are comparable to typical average-performance a-Si:H/SiN<sub>x</sub> TFTs.


  <div class="row justify-content-sm-center">
      <div class="col-sm-8 mt-3 mt-md-0">
          <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/scanning2.png' | relative_url }}" alt="scanning circuit" title="scanning circuit"/>
      </div>
      <div class="col-sm-4 mt-3 mt-md-0">
          <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/laes.jpg' | relative_url }}" alt="fabricated scanning circuit" title="fabricated scanning circuit"/>
      </div>
  </div>
  <div class="caption">
      Scanning circuit schematic (left) and fabricated large-area circuits on glass
  </div>

For my senior thesis, I worked with Professors Wagner and Verma to design and fabricate an a-Si:H TFT "scanning" circuit to interface between arrays of thin-film sensors and nanoscale integrated circuit chips for a system to monitor the formation and propagation of cracks on a bridge.

<div class="publications">
  <h2>publications</h2>
  {% bibliography -f papers -q @*[category=TFTs]* %}
</div>
