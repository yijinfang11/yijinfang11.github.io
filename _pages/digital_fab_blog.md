---
layout: archive
title: "MetaMaterial Blogs"
permalink: /digitfab/
author_profile: true
redirect_from:
---

{% include base_path %}


This blog illustrates my progress in CSCE-689 Digital Fabrication of Fall 2023, taught by [Dr. Jeeeun Kim](http://www.jeeeunkim.com/).

# Table of Contents

1. [MetaMaterial Design (Plier)](#metamaterial-design-plier)
2. [Growing Hairs](#growing-hairs)
3. [Kerf Pattern with Fusion 360](#kerf-pattern-with-fusion-360)
4. [X-bridge Replication](#x-bridge-replication)
5. [Resin Printing](#resin-printing)
6. [End of Page](#thank-you)

## MetaMaterial Design (Plier)

Designing a plier with meta material!

![final_plier](<../images/digitfab/final_view.png>)

### Designing cells

Building and adjusting rigid and shear cells

![design_cell](<../images/digitfab/design_cell.png>)

### Building the Plier

Setting stiffness to 50%, we started building plier's main body

![building_block](<../images/digitfab/Building blocks.png>)

### Touching up edges

I noticed that the edges of the plier are not smooth, so we designed triangular cells to smooth the edges

![touch_up_edge](<../images/digitfab/touch_up_edge.png>)

### Slicing and Examing

Due to unknown issue, the edging and interior cells are not connected. I tried to fix the issue by slicing the model in different ways, but the issue still persists.

![sliced_plier](<../images/digitfab/sliced_plier.png>)

### 3D Printed Product

Regardless, the printed plier is able to convert the force and firmly grip small objects

![printed_plier](<../images/digitfab/printed_plier.jpg>)
![plier_gripping](<../images/digitfab/printed_plier_2.jpg>)

## Growing Hairs

### Slicing an existing STL file into g-code file

![Slicing Benchy](<../images/digitfab/hair_1.png>)

### After identifying a good position, modifying G-code file to add hairs

![Adding Hair](<../images/digitfab/hair_2.png>)

### Visually examining whether the hair is propoerly added

![Visual Examine](<../images/digitfab/hair_3.png>)

### Verifying the hair in G-Code

![G-code Examine](<../images/digitfab/hair_4.png>)

### Confirming the setup with 3D Cura (due to excused absence, I did not get to print out the hairs)

![Final Product](<../images/digitfab/hair_5.png>)

## Kerf Pattern with Fusion 360

### Loading the provided triangular kerf template

![triangle template](<../images/digitfab/kerf_1.png>)

### Adding the connection circle sketch

![circle sketch](<../images/digitfab/kerf_2.png>)

### Extruding a triangular kerf and a circle

![Visual Examine](<../images/digitfab/kerf_3.png>)

### Extending the sketch design to 4 triangular kerfs

![final sketch](<../images/digitfab/kerf_4.png>)

### Extruding the sketch to create the stl file

![final extrusion](<../images/digitfab/kerf_5.png>)

### Final printed product

![final product](<../images/digitfab/kerf_6.png>)

## X-Bridge Replication

Replicating bridges was a collaborative effort, please click here for [X-Bridge Replication](https://people.tamu.edu/~yijinfang/csce689/Xbridge.html)

## Resin Printing

### Configuring ChituBox

We downloaded and installed chitubox from official website
Then we followed Emory's recommendation to configure the settings

![chitubox_config](<../images/digitfab/resin_print/chitubox_config.jpg>)

### Finding a sample STL file (Electro Gnosis from Genshin Impact)

We identified a "electro gnosis" chess piece from [thingiverse](https://www.thingiverse.com/thing:5662266)

![chess_piece](<../images/digitfab/resin_print/gnosis_thingiverse.png>)

### Modifying and Exporting the Electro Gnosis

We first scale the gnosis

![scaling_gnosis](<../images/digitfab/resin_print/scaling_gnosis.png>)

Then we added a base and support to the gnosis

![adding_support](<../images/digitfab/resin_print/adding_support.png>)

Finally, we slice and export the LCD-printer ready file

![slicing_exporting](<../images/digitfab/resin_print/slicing_exporting.png>)

### Printing the Gnosis

We first prepare the LCD printer and load the file into the printer

![loading_print](<../images/digitfab/resin_print/loading_print.jpg>)

Our First Attempt failed, we suspect it was due to small size

![first_attempt](<../images/digitfab/resin_print/first_attempt.jpg>)

However, with re-scaled size, the same problem occured

![second_attempt](<../images/digitfab/resin_print/second_attempt.jpg>)

Seems like the base was not properly formed, we will try to fix the issue by not lifting the gnosis at all

![examine_fail](<../images/digitfab/resin_print/examine_fail.jpg>)

### Third Attempt

We not only made the gnosis stick to the ground, but also doubled both base layer and exposure time

![final_print](<../images/digitfab/resin_print/final_print.jpg>)

## Thank you!
