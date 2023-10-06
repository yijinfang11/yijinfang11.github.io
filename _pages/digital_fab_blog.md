---
layout: archive
title: "MetaMaterial Blogs"
permalink: /digitfab/
author_profile: true
redirect_from:
---

{% include base_path %}

This blog illustrates my progress with building a plier with metamaterial cells.

# Table of Contents

1. [MetaMaterial Design (Plier)](#metamaterial-design-plier)
2. [License](#license)
3. [End of Page](#thank-you)


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


## Growing hairs

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

## Curved Pattern with Fusion 360

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

## Thank you!