---
layout: page
title: Implantable Electronics for Prosthetic Control
description: MIT Media Lab / Draper Laboratory, 2013-2014
img: /assets/img/uchannel.png
importance: 4
---

<div class="row justify-content-sm-center">
        <img src="{{ '/assets/img/uchannel.png' | relative_url }}" alt="" title="microchannel array" width="70%" height="70%"/>
</div>
<div class="caption">
    Distal target tissues (skin, muscle) are packed into the residual limb during amputation. Nerves regrow to the target tissues through silicon microchannel arrays, which can selectively stimulate and record from nerve fibers in each channel for closed-loop prosthetic control.
</div>

After completing my master's thesis at MIT on quantum dot LEDs in 2013, I switched labs and worked with Professor Hugh Herr and Dr. Ron Riso in the <a href="http://biomech.media.mit.edu" target="_blank">Biomechatronics Group</a> at MIT Media Lab.

While tremendous progress has been made in the neural control of prosthetic limbs, achieving intuitive, natural feelings of sensation (i.e. not just a buzzing/vibration pattern) and fine motor control remains elusive. This is partially due to the fact that peripheral nerves are mixed bundles of both motor and sensory nerve fibers, making selectively stimulating motor nerve fibers and selectively recording from sensory nerve fibers difficult. I worked on designing and micro-fabricating implantable electronics that we hoped would help tackle this challenge. Specifically, we designed a silicone microchannel array with platinum electrodes that could be implanted during an amputation surgery. As part of the surgery, a mixed motor/sensory nerve in the residual limb would be cut. The array, consisting of hundreds of channels, would be implanted in line with that nerve, whose fibers would regenerate through the microchannels, being forced to separate from one another in the process. Because each channel in our device was individually addressable, the device ideally would allow for selective stimulation of motor nerve fibers and selective recording from sensory nerve fibers, thus enabling much richer and natural schemes of closed-loop prosthetic control. This project was done in collaboration with <a href="https://www.draper.com" target="_blank">Draper Laboratory</a>, where I was also a Graduate Fellow.

In conjunction with Dr. Matthew Carty, MD at Brigham and Women's Hospital, we also wrote a patent describing amputation surgeries that would allow for novel peripheral neural interface schemes. I ultimately left the PhD program at MIT before I finished a PhD to climb mountains, travel, and work at Apple for a few years. Biomech has made tremendous progress in implementing some of these neural interfaces (and more) since my time there.

<div class="publications">
  <h2>related publications</h2>
  {% bibliography -f papers -q @*[category=prosthetics]* %}
</div>
