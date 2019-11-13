---
layout: post
title:  "Aluminum Longboard"
date:   2018-12-31
desc: "Design and building of an aluminum lonogboard"
keywords: "longboard, aluminum longboard, design, 7071, waterjet"
categories: [Blog]
tags: [Aluminum,longboard]
icon: fa-forward
---

There is a significant presence of wheels-skateboards, longboards, freelines-on Harvey Mudd's campus. While anyone could buy one, I saw this as an opportunity to make my own. 

Before I decided on aluminum, I had to consider material properties: weight, youngs modulus, yield point, and ease of manufactoring. Most longboards use plys of wood with fiberglass layers for a great strength to weight ratio. However, I do not have a deck press needed for making longboards from plys of wood. I went with 7071 T6 aluminum which would allow interesting designs. To mitigate the weight of the aluminum, some material could be taken off from the middle of the board.

### Materials and Resources Used
* 7075 T6 Aluminum 1'x4'x.5"
* Waterjet Cutter
* Prototyping Plywood 2'x4'x1"
* Solidworks

Research to find out the normal dimentions of a longboard showed most are 10 inches wide, ranging from 36 to 42 inches long. I decided to make mine 38 inches long. 

Thick 7075 aluminum allowed me to experiment with some unique shapes while not worrying about plastic deformation. I came up with the following designs:

<!-- ![edit]({{ site.img_path }}/aluminumlongboard/longboard1.jpg) -->
<img src="{{ site.img_path }}/aluminumlongboard/longboard1.jpg" width="50%">
<a href='http://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=996286'>Download</a>

<!-- ![edit]({{ site.img_path }}/aluminumlongboard/longboard2.jpg) -->
<img src="{{ site.img_path }}/aluminumlongboard/longboard2.jpg" width="50%">
<a href='http://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=996265'>Download</a>

I decided to use the second design for simplicity, eligance, and structural properties. The design was tested using solidworks FEA analysis for a load of two feet on the middle of the board. One side was fixed, the other was on a slider joint. All the cutouts were given a concave to prevent a high load of stress at those areas.

<!-- ![edit]({{ site.img_path }}/aluminumlongboard/longboardfea.jpg) -->
<img src="{{ site.img_path }}/aluminumlongboard/longboardfea.jpg" width="50%">

The prototype was cut out of plywood on a shopbot cnc router.

<!-- ![edit]({{ site.img_path }}/aluminumlongboard/woodlonboard.jpg) -->
<img src="{{ site.img_path }}/aluminumlongboard/woodlongboard.jpg" width="50%">

It was crucial to test for wheel bite at this stage. When turning, the wheels touched the side of the board and promped me to shave off a few inches from the area near the wheels.

For the final product, this was cut out of 7075 T6 aluminum. It was already heat treated which prevented me from giving it a concave shape, but the structural properties more than made up for this.

The aluminum was cut using a water jet cutter. This did not create any burs what would be a pain to remove afterwards. 

<!-- ![edit]({{ site.img_path }}/aluminumlongboard/metallongboardground.jpg) -->
<img src="{{ site.img_path }}/aluminumlongboard/metallongboardground.jpg" width="50%">

<!-- ![edit]({{ site.img_path }}/aluminumlongboard/metallongboardtrucks.jpg) -->
<img src="{{ site.img_path }}/aluminumlongboard/metallongboardtrucks.jpg" width="50%">


