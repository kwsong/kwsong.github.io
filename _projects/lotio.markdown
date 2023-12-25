---
layout: page
title: lotio
description: lotion-mediated interaction with an electronic skin-worn display
img: /assets/img/lotio_teaser.png
importance: 2
category: HCI
---
<div class="row justify-content-sm-center">
        <img src="{{ '/assets/img/lotio.png' | relative_url }}" alt="" title="lotio" width="750px"/>
</div>
<br><br>
Skin-based electronics are an emerging genre of interactive technologies. We propose a class of "Lotion Interfaces" that leverage the natural uses of lotions and propose them as mediators for driving novel, low-power, quasi-bistable, and bio-degradable interactions on the skin and other surfaces. Lotion Interfaces may provide positive feedback to the user when lotion is applied through the form of playful aesthetic experiences, reinforcing healthy skin routines. They might also provide an opportunity to give the user additional control over an otherwise overwhelming swarm of electronic communications, activating notifications only during the few windows in a day that a lotion or cream is applied.

Lotio is one such Lotion Interface that simply comprises a paper surgical tape substrate and an bio-degradable, electrochromic ink that is conductive and changes color under an applied voltage.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_ecgeometries.png" title="unmaking" width="500" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Lotio's structure is a greatly simplified version of the "co-planar" architecture of a conventional electrochromic display pixel.
</div>
</center>

Lotio functions as a static display in the dormant state, similar to a traditional temporary tattoo. When lotion and a voltage differential are applied, the lotion behaves as an electrolyte, allowing electrons to move between portions of the design. One portion of the design is oxidized and becomes lighter in appearance; the other is reduced and becomes darker. After the lotion has been absorbed, the new coloring is maintained for over 15 minutes even after power has been removed.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lotio_interaction.png" title="unmaking" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Lotio interaction model.
</div>
</center>

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lotiodemo.gif" title="Lotio demo" class="img-fluid" width="600px" %}
    </div>
</div>
<div class="caption">
    Demonstration of Lotio's visual changes mediated by lotion application.
</div>
</center>

Lotio is easy and affordable to produce using commercially available materials and a DIY methodology. Furthermore, Lotio is highly customizable and can be tailored to fit the wearer's personal style.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lotiofab.gif" title="Lotio fabrication" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Fabrication of Lotio.
</div>
</center>

Once fabricated, Lotio can simply be wired to input or output pins on a microcontroller using copper tape as a connector and may be used as a dynamic display.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lotiodynamic.gif" title="Lotio fabrication" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Lotio connected to an ATtiny85 and used as a dynamic display.
</div>
</center>


Lotio may even be powered by decomposable supercapacitors (see the <a href="/projects/vims/">Vims page</a>), to create a wearable that is degradable in backyard soil in its entirety.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lotiovims.gif" title="Lotio-Vims combo" width="600px" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Lotio powered by Vims.
</div>
</center>


Lotio is highly customizable and aesthetic. In addition to spatial layout, a designer may modulate different parameters that affect interactions with Lotio. Namely, layer thickness. applied voltage, and different lotion types all affect the visual contrast of the design as well as the rate at which a design element changes color.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_thickness.png" title="unmaking" width="500" class="img-fluid" %}
    </div>
</div>
<div class="caption">
Visual clarity of Lotio varies with varying thicknesses of
PEDOT:PSS ink. Lotio exhibits quasi-bistability, retaining its state even after the removal of voltage for over 12 minutes.
</div>
</center>

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_voltages.png" width="600px" title="unmaking" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Visual clarity may be modulated by the application of different voltages.
</div>
</center>

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_difflotions.png" title="unmaking" width="300" class="img-fluid" %}
    </div>
</div>
<div class="caption">
    Different lotions and creams induce different visual signatures that can also be detected electrically.
</div>
</center>

Lotio’s visual transformations are visible and comfortable on different skin tones and on different parts of the body. Lotio can also extend the functionality of various electronics, such as smartwatches.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_mockups.png" title="unmaking" class="img-fluid rounded z-depth-1"  %}
    </div>
</div>
<div class="caption">
Mock-ups of Lotio designs applied to different body parts and integrated with different accessories.
</div>
</center>

We conducted a preliminary user study with 9 participants to understand perceptions of lotion-mediated interaction and how Lotion Interfaces might differ and also share characteristics with existing on-skin technologies. Participants wore Lotio on their hands, wrists, and forearms. All participants found these locations to be ideal for skin-worn technology, echoing prior work. In addition, 4 participants envisioned wearing Lotio on the face or neck. In deciding appropriate locations for Lotion Interfaces, participants were concerned with visibility, accessibility, and existing cosmetic practices. Some participants considered Lotio’s audience, determining where to wear the interface to facilitate different types of interactions.

Seven participants envisioned using Lotio for health monitoring and medical applications: measuring sweat (P5), body temperature (P3, P5), and UV exposure (P2). Participants also imagined using Lotio to display health data sensed on other devices: blood sugar levels (P3, P9), heart rate (P3, P5, P9), and hydration level (P6). P6 thought that a Lotion Interface would be particularly well suited to "surfacing relevant body data" because "the act of applying lotion itself could be seen as a self-care activity."" Participants also envisioned using Lotio for aesthetics, notifications, and as an input to other devices. Two participants wanted to use Lotio as a form of nonverbal communication, "reflecting emotions" and behaving as a "subtle social cue." Participants liked that the interface attached directly to the skin and likened it to an extension of self.

> It's fundamentally different because it feels like it’s sort of becoming one with your body instead of just an external device that is registering things about your body (P2).

Lotio is admittedly a rather simple visual embodiment of Lotion Interfaces, but similar principles could be extended to make more complex displays. For instance, with a few more fabrication steps, Lotio may be adapted from its present co-planar geometry to be a multi-layer stacked structure, which would allow for the creation of generic 2D displays that can display arbitrary information on the fly. The below figure shows a preliminary 2x2 pixel prototype of this that uses 2 layers of electrochromic ink-coated surgical tape separated by a single layer of uncoated surgical tape as an insulator. When lotion is applied, it is absorbed through the surgical tape layers, and selective pixels may be activated by addressing (i.e., applying a voltage differential across) specific rows and columns, similar to how a conventional passive matrix display works.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_2x2.png" title="unmaking" width="300" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
A multi-layer 2x2 pixel Lotio prototype.
</div>
</center>

Beyond Lotion Interfaces that are based on visual changes, embodiments that utilize other materials that create textural, haptic, or even olfactory changes could expand the richness of our interactions with lotions. Lotion might rehydrate integrated hydrogel beads to create shape changes that are both visible to others and perceivable by the wearer, or it might chemically react to a Lotion Interface to produce heat. We hope that future designers will be inspired by our work and consider the affordances of lotion in interaction design. Furthermore, we hope that our approach can be influential beyond the skin, inspiring future designers to examine existing practices to find new embodied interaction modalities.

<div class="publications">
  <h2>publications</h2>
  {% bibliography -f papers -q @*[category=lotio]* %}
</div>
