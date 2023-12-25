---
layout: page
title: vims
description: customizable, decomposable electrical energy storage
img: /assets/img/vims_teaser.png
importance: 1
category: HCI
---
<div class="row justify-content-sm-center">
        <img src="{{ '/assets/img/vims.png' | relative_url }}" alt="" title="unmaking" width="760"/>
</div>
<br><br>
Providing electrical power is essential for nearly all interactive technologies, yet it often remains an afterthought. Some designs handwave power altogether as an "exercise for later." Others hastily string together batteries to meet the system's electrical requirements, enclosing them in whatever box fits. Vim is a new approach -- it elevates power as a first-class design element; it frees power from being a series of discrete elements, instead catering to exact requirements; it enables power to take on new, flexible forms; it is fabricated using low-cost, accessible materials and technologies; finally, it advances sustainability by being rechargeable, non-toxic, edible, and compostable. Vims are decomposable battery alternatives that rapidly charge and can power small applications for hours.

Vims are functionally electrical double layer supercapacitors (EDLCs) that store energy at two layer interfaces within a multi-layer stack. A regular capacitor comprises two conductive electrodes separated by a solid insulator. In comparison, a supercapacitor comprises two conductive electrodes separated from one another by a liquid or gelatinous electrolyte that is abundant with mobile ions. The electrode material in a supercapacitor is selected to be very porous in order to maximize surface area contact with the electrolyte, and thus charge storage ability in comparison to a regular capacitor, but this comes at a slight conductivity cost. Therefore, additional non-porous conductive current collector layers are usually needed to contact the electrodes and connect the supercapacitor to any external circuitry. Layers may be stacked in a parallel-plate structure, laid out in a co-planar geometry, or even formed axially.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vimsgeometries.png" title="unmaking" class="img-fluid" width="500" %}
    </div>
</div>
<div class="caption">
    Supercapacitor geometries.
</div>
</center>

When a voltage is applied between the two electrodes, ions within the electrolyte migrate towards the two electrode interfaces, causing the buildup of opposing electrostatic charge layers at each interface. Unlike the charging and discharging processes of batteries, which utilize semi-irreversible reactions that involve ions moving across layer boundaries and changing the chemistry of those layers, the charging and discharging processes of supercapacitors are completely reversible and do not involve chemical reactions. Thus, supercapacitors can theoretically be charged and discharged a virtually limitless number of times. While they are generally capable of storing less energy than batteries and tend not to be suitable for applications requiring continuous operation over long periods of time, commercial supercapacitors have very high power density for their size due to the porous nature and high specific surface area of the electrodes. In addition, they can both charge quickly and discharge large amounts of current quickly, unlike batteries.

Noting the key properties of each layer in conventional supercapacitors, we create Vims with materials that were readily accessible (purchased on Amazon.com), kitchen-safe, and even edible. Several materials, such as CMC and guar gum, can be used interchangeably. The materials we explored can also be made flexible and thin to allow them to conform to arbitrary surfaces and be easily shaped by hand or hand tools.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vimsmaterials.png" title="unmaking" class="img-fluid rounded z-depth-1" width="600" %}
    </div>
</div>
<div class="caption">
    Materials for making Vims.
</div>
</center>

For our exemplar Vims, we utilize rolled foils of 127µm-thick graphite, a naturally-occurring form of carbon that can be used as plant food, as our current collector and substrate. Graphite is cheap, abundant, conductive, and available in flexible sheets that serve as both a substrate and a current collector. As in commercial supercapacitors, we use activated charcoal as our electrode. We extract powdered activated charcoal from dietary supplement capsules. We select CMC as our binder, as it forms electrode and electrolyte inks that are easily spreadable (unlike less viscous choices like sports drinks) and odor-free (unlike other choices like eggs, cheese, or chitosan). CMC is a cellulose gum that is a common thickener and emulsifier used in ice cream, biscuits, and candy. It also yields the highest performance Vims by a small margin when compared to guar gum and chitosan. For our electrolyte, we mix table salt with glycerin and our CMC binder. The cost of materials to make a Vim ~11cm<sup>2</sup> in area is approximately $0.13 (USD), with $0.12 of that being the cost of graphite.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vimsfab.gif" title="unmaking" width="600px" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fabrication of Vims.
</div>
</center>

One benefit of supercapacitors in comparison to batteries is that they may be safely and very quickly charged to full capacity -- on the order of seconds, in the case of commercial supercapacitors. Because fires and other permanent damage from over-heating are not concerns, Vims may be charged with practically no limit on charging current. A Vim 11cm<sup>2</sup> in area can be charged to >2V within 5 minutes.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vimstest.gif" width="600px" width="600" title="unmaking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Basic demo of Vims.
</div>
</center>

Because Vims can take on arbitrary shape and, to some extent, color and texture, they may be double as decorative design elements and power sources. For example, edible gold foil may simultaneously serve as a Vim current collector and as a material for creating a gilded appearance. Vims built on this gold foil can be extremely thin and conformable, wrapping around otherwise awkward corners or curves of a design. Additionally, Vims eliminate the need for battery-related enclosures, such as spring clips or protective casings.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vimsclock.gif" title="unmaking" width="600" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Vims doubling as decorative elements and electrical power.
</div>
</center>

Coupled with other sustainable materials, Vims allow us to design electronic wearables that do not result in any landfill. Lotio (project page <a href="../lotio/">here</a>) is a 100% decomposable on-skin display that can be powered by 4 co-planar Vims connected in series. Vims are mounted on a surgical paper tape bracelet with pine resin, a natural sticky substance that can be used as an adhesive. Operationally, the system is a 2-state display whose transformation is triggered by the application of a lotion, cream, or other electrolytic gel. Initially, the system is in an open circuit configuration, with no power consumption. When lotion or another activating conductive gel or cream is applied, it acts as an electrolyte, closing the circuit and allowing free ions to migrate towards the electrodes. A color-changing reduction reaction at the negative electrode and an oxidation reaction at the positive electrode occur. The power consumption associated with this change is very low, with ~60µA of current being consumed when 5V is applied. The on-skin display is quasi-bistable and can hold its color-changed state for over 10 minutes or until the lotion is wiped off or absorbed by the skin, at which point it slowly reverts to its original state. A chain of 4 Vims holds more than enough charge to power this wearable over the course of a whole day with multiple lotion applications.

<center><div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vimslotioschematic.png" title="Vims-Lotio combo" class="img-fluid" width="400" %}
    </div>
</div>
<div class="caption">
    Schematic of fully decomposable electrochromic bracelet.
</div>
</center>

<center>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lotiovims.gif" title="Vims-Lotio combo" class="img-fluid rounded z-depth-1" width="600" %}
    </div>
  <div class="caption">
      Fully decomposable wearable with Vims and Lotio.
  </div>
</center>

Even though Vims are reusable and rechargeable, they are also designed to be disposable and decomposable in a very short period of time without specialized industrial conditions. In fact, our exemplar Vims may be beneficial additions for garden soil health. Activated charcoal and graphite are immediately usable as soil conditioner. Glycerin is also known to be a degradable soil additive that can promote soil nutrient retention and healthy microbial growth. CMC has been reported to decompose under normal environmental conditions within 14 days. As a sanity check, we buried a Vim in our yard to observe decomposition for ourselves. Only 30% of the Vim's mass remained after 60 days. Plants near the burial site appeared to remain healthy. This is unsurprising, since we intentionally selected components that are known to be decomposable.
<center>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_decompvims.png" title="Vims decomposing" class="img-fluid" width="600" %}
    </div>
  <div class="caption">
      Vims decomposes easily in garden soil.
  </div>
</center>

<div class="publications">
  <h2>publications</h2>
  {% bibliography -f papers -q @*[category=vims]* %}
</div>
