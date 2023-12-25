---
layout: page
title: Computational Photography and Computer Vision
description: Fall 2022 portfolio
img: /assets/img/compphoto.png
importance: 1
category: classes
---

<div class="row justify-content-sm-center">
        <img src="{{ '/assets/img/compphoto.png' | relative_url }}" alt="" title="computational photography" width="50%" height="50%"/>
</div>

During the Fall 2022 semester, I took CS294-26: Introduction to Computer Vision and Computational Photography. Projects included:
<br>(1) Colorizing the Prokudin-Gorskii Photo Collection (<a href="https://inst.eecs.berkeley.edu/~cs194-26/fa22/upload/files/proj1/cs194-26-acj/" target="_blank">link</a>)
<br>(2) Creating "hybrid" images with filters and frequency manipulation (<a href="https://inst.eecs.berkeley.edu/~cs194-26/fa22/upload/files/proj2/cs194-26-acj/" target="_blank">link</a>)
<br>(3) Face morphing (<a href="https://inst.eecs.berkeley.edu/~cs194-26/fa22/upload/files/proj3/cs194-26-acj/" target="_blank">link</a>)
<br>(4) Stitching and creating photo mosaics (<a href="https://inst.eecs.berkeley.edu/~cs194-26/fa22/upload/files/proj4A/cs194-26-acj/" target="_blank">part 1</a> and <a href="https://inst.eecs.berkeley.edu/~cs194-26/fa22/upload/files/proj4A/cs194-26-acj/" target="_blank">part 2</a>), and
<br>(5) Detecting facial keypoints with neural networks (<a href="https://inst.eecs.berkeley.edu/~cs194-26/fa22/upload/files/proj5/cs194-26-acj/" target="_blank">link</a>).
<p>
For my final project, I proposed and implemented a tool that allows parquetry, the art of tiling wood pieces to form decorative designs or images, to be easilycreated by designers with no domain expertise. It takes as input one or more images of wood pieces, which may be salvaged fromlaser-cutting or CNC milling, and a target image. Using a simple weighed intensity and edge matching algorithm, the tool determineshow the wood should be cut and arranged to resemble the target image. Finally, the tool outputs files that can be directly sent to alaser cutter to cut the wood into tiles and engrave each tile with its location and orientation. The user then rearranges the cut tiles as instructed by the engraved labels. The full write-up can be found <a href="https://inst.eecs.berkeley.edu/~cs194-26/fa22/" target="_blank">here</a>.
