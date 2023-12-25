---
layout: page
title: backyard-degradable electronics
description: research overview
img: /assets/img/overview.png
importance: 1
category:
---
<div class="row justify-content-sm-center">
        <img src="{{ '/assets/img/overview2.png' | relative_url }}" alt="" title="overview of my research" width="80%" height="80%"/>
</div>
<br><br>
<b>I am on the academic job market and am actively seeking tenure-track assistant professor positions starting in fall/winter 2024.</b> My research statement can be found <a href="https://drive.google.com/file/d/1inlR6yJGJy8FjMkLhBZnQh4snbGi6FjU/view?usp=sharing" target="_blank">here</a>.

To summarize, I envision a class of future sustainable electronics whose entire lifecycle – from initial material sourcing to end-of-life – is a creative, participatory process. My research in human-computer interaction aims to empower the everyday designer with the materials, fabrication methods, and software tools needed to make and unmake such systems, which I call <b>backyard-degradable interactive systems</b>. As the demand for material goods rages, waste is accumulating on our planet at an alarming rate. Electronics in particular present significant sustainability challenges due to the energy-intensive processes involved in their production and their dependence on nonrenewable resources. Unwanted and broken devices often end up in landfills, where they do not decompose. While maximizing durability is a suitable approach for certain electronics, like laptops and phones, there exist numerous other electronics that are temporary and low power in nature, such as seasonal wildfire sensors, fashion accessories, and smart packaging. For those, high-speed chips and high-capacity batteries are unnecessary and can, in fact, restrict design flexibility and creativity. What if, instead, we had the means to rapidly make, customize, and artistically dispose of our own sustainable electronics that are made with local or easily sourceable materials and are tailored to their actual lifetime and power requirements? My research agenda to build backyard-degradable interactive systems is situated at the intersection of interactive computing, electrical engineering, design, and materials science. I outline 3 thrusts:
<p>
<b>(1) Grow the toolbox of backyard-degradable components and systems.</b> Foundational to my vision is the development of backyard-degradable electrical components that can ultimately come together to form an interactive system. This is a hands-on, materials-centric endeavor, but it is one that is critical for HCI researchers and computer scientists to engage in and understand, as the components we develop form the technological backbone of future software and computer systems that will cater to the unique limitations and affordances of backyard-degradable hardware. Much of my PhD was spent laying this groundwork; by distilling key elements of materials science and electrical engineering research and porting them into more accessible fabrication environments, I developed backyard-degradable energy storage modules, wearable displays, and wirelessly activated heaters. The resulting backyard-degradable systems are aesthetically customizable and may be used for enabling self-expression, promoting self-care, and increasing the enjoyment or safety of food.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/vims.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/lotio.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/leaves.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fig_combolotiovims_horizontal.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<p>
<b>(2) Build tools to enable the unmaking of backyard-degradable systems.</b> Backyard-degradable materials are inherently transient, naturally degrading over the span of hours, days, or months, depending on the material. This property not only allows them to be easily and responsibly disposed of in garden soil but also affords new design opportunities for unmaking that are not shared by non-degradable materials. Recycling and composting, procedures typically conducted in industrial settings, have traditionally remained outside the purview of designers. However, I envision a future in which novel workflows and tools can transform these processes into creative playgrounds ripe for imaginative exploration and innovation. What if we saw “end-of-life” not as a destination but as a dynamic and artistic process? How might we intentionally engineer devices such that their functionality and aesthetics evolve as their various constituents break apart, are repaired, and eventually degrade?
<p>
<b>(3) Democratize the design of backyard-degradable systems through a series of participatory workshops + iterative software design tool development.</b> Widespread community involvement and participatory design are vital for unearthing novel and unexpected applications, guiding researchers interested in sustainable systems towards future directions, empowering individuals who have been traditionally excluded from advanced technology participation, and educating the public about new ways of thinking about sustainability, making, and consumption in society. To achieve the goal of equipping makers with the tools to make and unmake backyard-degradable systems, we first need to comprehend how makers with diverse backgrounds approach and grapple with backyard-degradable system design through participatory workshops that have the goals of identifying pain points in the fabrication and design of backyard-degradable electronics for diverse groups of makers, generating directions for future systems, and pinpointing the most salient elements to incorporate into future software tools and hardware starter kits. The insights gleaned from these qualitative studies will form the foundation for the development of software tools tailored to accommodate varying levels of experience. These tools will empower makers to conceptualize and bring to life their envisioned applications with backyard-degradable electronics. Additionally, these tools will serve as invaluable probes in future design workshops, deepening our understanding of how to support makers. These in turn will inspire more sophisticated tools that facilitate an even wider spectrum of creative applications. Software tools could manifest as plug-ins integrated into existing applications or stand-alone GUIs that abstract complex technical details. I will also explore the potential of LLMs and other emerging generative AI tools to craft innovative chatbot-based interfaces that intuitively guide novice designers throughout the design, debugging, and fabrication stages.


<div class="publications">
  <h2>publications</h2>
  {% bibliography -f papers -q @*[category=decomposable]* %}
</div>
