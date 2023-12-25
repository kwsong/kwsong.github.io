---
layout: page
title: leaf heaters
description: design of a backyard-degradable wireless heating interface
img: /assets/img/leafheater_icon.png
importance: 3
category: HCI
---
<div class="row justify-content-sm-center">
        <img src="{{ '/assets/img/leafheater.png' | relative_url }}" alt="" title="unmaking" width="600"/>
</div>
<br><br>
Sustainability is critical to our planet and thus our designs. Within HCI, there is a tension between the desire to create interactive electronic systems and sustainability. In a CHI2022 paper, in collabration with Accenture Labs in San Francisco, CA, we presented the design of an interactive system comprising components that are entirely decomposable. We leverage the inherent material properties of natural materials, such as paper, leaf skeletons, and chitosan, along with silver nanowires to create a new system capable of being electrically controlled as a portable heater.

To do this, take advantage of the branching fractal pattern of leaf veins and turn leaf skeletons into large-area Joule heaters. Silver nanowires are used to make the skeletons conductive, and chitosan, an extract from crustacean shells, is used to mechanically stabilize the leaves.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/leaf_schematic.png" title="unmaking" width="300" %}
    </div>
</div>
<div class="caption">
    Electrical schematic of wireless leaf heater system
</div>
</center>

The fabrication process is straightforward and can be done entirely with hand tools. Leaf skeletons are dipped in chitosan and a water-based silver nanowire solution.
<center>
<div class="row justify-content-sm-center">
        {% include figure.html path="assets/img/leaffab.gif" title="unmaking" class="img-fluid rounded z-depth-1" %}
        </div>
<div class="caption">
    Fabrication of leaf skeleton heating patches.
</div>
</center>

Envelopes are assembled by laminating the leaf skeletons on paper tape with a natural rubber adhesive and connecting them in parallel with water-based silver ink. The silver ink can be used to create a coil that can couple with inductive wireless chargers (copper coil used for prototyping below). The tape can then be mounted onto a Kraft paper bag.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/leafassembly.gif" title="unmaking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Assembly of decomposable packaging.
</div>
</center>

This decomposable system is capable of wirelessly heating to >70°C when placed on a wireless charger. It is flexible, lightweight, low-cost, and reusable, and it maintains its functionality over long periods of heating and multiple power cycles.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/leafheating.gif" title="unmaking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
</center>
<div class="caption">
    Heating functionality is activated by a wireless charger.
</div>

Food is a basic necessity for all as well as a subject of delight for many. Access to health-safe food is limited by the regional availability of processing, packaging, and storage technology. Pasteurization is one important but simple technique relied on worldwide that uses mild heat to destroy harmful microbes in liquid foods without changing the nutritional content or taste. This process is critical for treating products such as milk and juices. The pasteurization of milk requires a sustained temperature of 63<sup>o</sup>C for 15 minutes or 72<sup>o</sup>C for 15 seconds to sufficient to destroy all yeasts, molds, and gram-negative bacteria \cite{pasteurization}. These parameters are easily achievable by our leaf heaters, positioning them as an attractive solution for food safety in environments and locales where specialized equipment is unavailable.

Our packaging may also be used as a reusable receptacle for heating food for more optimal enjoyment. To demonstrate this, we took a store-bought chocolate chip cookie, placed it in our packaging, and placed the packaging on our wireless charger (input voltage = 12V) for 2 minutes. After removing it from the packaging, the cookie was soft, and the chocolate chunks had been melted. Similar scenarios could be useful for other snacks or beverages in various settings, such as outdoors on a hike or in an airport, where microwaves and other kitchen appliances are not readily available, or in situations in which it might not be desirable to share such equipment. With a few basic modifications, instead of taking the shape of a rectangular bag, our packaging could be a sheet with pre-creased origami folds (or pre-scored kirigami cuts) so that it may be transported and stored flat but be easily assembled into aesthetically interesting and/or functional 3D shapes, such as bowls for soup.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/leafcookie.gif" title="unmaking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Increasing the enjoyment of food.
</div>
</center>

Shape-changing elements could be also integrated into a packaging form factor to indicate prior usage, perhaps as a safety feature or perhaps as a decoration. These objects could be adhered to the outside of packaging, with a shape changing indicating if the package has been heated before. This could help a user determine if the packaging's inner contents are safe or valid. Depending on aesthetic preferences, these features could be designed to be spartan and purely functional, or they may be intentionally designed to be playful and whimsical. Heat-activated shape-changing materials such as expanding foams, made from silicone and thermally-expanding microspheres, can also be incorporated into our packaging to protect arbitrarily-shaped contents. The unexpanded foam can be packed flat into the walls of the packaging to allow for easy transport when the packaging is empty. Once the packaging is filled, the expanding foam can be easily activated to inflate and conform to the contents by placing the packaging on a charging mat.

<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/leafshapechange.gif" title="unmaking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Activating nitinol, a shape-changing materials.
</div>
</center>

At end of life, the packaging may be disposed of in garden soil, where it decomposes in 60 days.
<center>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/leafbury.gif" title="unmaking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Decomposition of packaging.
</div>
</center>

<div class="publications">
  <h2>publications</h2>
  {% bibliography -f papers -q @*[category=leafheaters]* %}
</div>
