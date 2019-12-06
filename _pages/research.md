---
layout: archive
title: ""
permalink: /research/
author_profile: true

---
CLICK ON THE TITLE FOR DETAILS!

## [VR-based 3D Tooth Operation Model System for Dental Surgery](https://renjie-woo.github.io/research/vr-tooth/)
* Calculated 3 axes, established single tooth coordinate systems, and calculated oriented bounding boxes (OBB) for each tooth using principal component analysis (PCA) to improve the accuracy of locating operating axes and points
* Developed 10 interaction modes for each tooth in both PC system and VR system:
    * rotation around X/Y/Z axis
    * rotation left/right/top/bottom side of the tooth
    * translation along X/Y/Z axis
* Established scenes for surgery simulation and data displaying (number, transformation matrix of the chosen tooth, etc.); Integrated all functions above in a VR application which could be used to simulate surgery vividly and calculate transformation matrix of each tooth during operation
<iframe width="560" height="315" src="https://www.youtube.com/embed/pglWMPHbTlk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## [Reconstructing Teeth from a CT scan](https://renjie-woo.github.io/research/reconstruction/)
* Designed and implemented a neural network based on SegNet to segment teeth parts from converted CT images; Constructed teeth dataset by annotating teeth using Photoshop after converting CT scans to PNG images; Optimized the performance of the network to high accuracy (99.5% in testing) using SELU
* Extracted edges of segmented teeth images using Canny Operator which is not susceptible to noise; Generated point clouds on extracted edges and reconstructed the 3D teeth mesh model using spatial characteristics of CT scans
* Proposed an optimized method which segmented teeth from CT scans using the network above but changed produced images into CT formats to utilize existing mature medical imaging technology for reconstruction

<img src="https://renjie-woo.github.io/images/reconstruction/SEG.png" width = "50%"/>

   <!-- [![poster for Reconstructing Teeth from a CT scan](https://renjie-woo.github.io/images/reconstruction/SEG.png)](https://renjie-woo.github.io/images/reconstruction/SEG.png)
   -->

## [VR-based Alpine Skiing project for 2022 Olympic Winter Games](https://renjie-woo.github.io/research/skiing/)
* Designed a real-time detection system based on relative angle and collision mechanism of predeﬁned tags to detect the orientation and swing range of player’s arms
* Established realistic scenes associated with snow mountains and skiing using Unity; Designed an interactive VR action game with 2 different modes (Prop Mode and Gate Mode)
<iframe width="560" height="315" src="https://www.youtube.com/embed/nFPyu8AAwVQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## [ChinaVis 2019 Data Visualization](https://renjie-woo.github.io/research/chinavis/)
* Predicted the conference agenda, possible potential types, and relationships of participants as well as emergency represented by outliers after analyzing data of sensors through clustering
* Designed and implemented an interactive visual analysis website to demonstrate ﬁndings about the relationship and outliers with 9 different kinds of charts(Personal Track Map, Radial Bar Chart, etc) and different interactive methods
<iframe width="560" height="315" src="https://www.youtube.com/embed/reXQfl-iBpo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>