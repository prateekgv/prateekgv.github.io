---
layout: single
author_profile: true
comments: false
title: false
---

#### Data Fusion of Foot-Mounted Inertial Navigation System
##### Background
<div class="align-justify">There has been an increasing demand for a robust and accurate positioning system that works in indoor and outdoor environments. GPS provides a whole range of navigation accuracies at very low cost and low power consumption. The devices that use GPS are portable and are well suited for integration with other sensors, communication links, and databases. The need for alternative positioning system arises because GPS does not work in all environments, especially indoor environments. This is a major problem in certain situations, such as military and disaster relief operations, where one has to track the first responders who arrive at the scene to carry out their mission.</div>

##### Our Research
In our work, we developed novel algorithms to fuse inertial sensor data from dual foot-mounted inertial navigation systems to reduce the systematic heading drift. In particular, we proposed two range constraint methods to fuse the information from the navigation systems.

<p align="center"><img src="/research/indoorpos/animate/cm_slm_uc_smaller_size.gif" width="400" height="270"/></p>
<p align="center">3D trajectory plot of a dual foot-mounted INS with sphere limit method (SLM), centroid method (CM), and unconstrained method (UC).</p>

##### Publications
1. K. V. S. Hari, J.O. Nilsson, I. Skog, P. Händel, J. Rantakokko, and **G. V. Prateek**, "A prototype of a first-responder indoor localization system," _Journal of the Indian Institute of Science_, vol. no. 93(3), pp. 511-520, 2013. [[**PDF**]](/research/indoorpos/pdfs/[JofIISc]Hari_et_al-2013-A_prototype_of_a_first_responder_localization_system.pdf)
2. R. Girisha, **G. V. Prateek**, K. V. S. Hari, and P. Händel, "Fusing the navigation information of dual foot-mounted zero-velocity-update-aided inertial navigation systems," _International Conference on Signal Processing and Communications (SPCOM)_, Bangalore, 2014, pp. 1-6. [[**PDF**]](/research/indoorpos/pdfs/[IEEESPCOM]Girisha_et_al-2013-Fusing_the_navigation_information_of_dual_foot-mounted_ZUPT-aided_INS.pdf) [[**CODE**]](https://github.com/prateekgv/openshoe-centroid_method)
3. **G. V. Prateek**, R. Girisha, K. V. S. Hari, and P. Händel, "Data Fusion of dual foot-mounted INS to reduce the systematic heading drift," _4th International Conference on Intelligent Systems, Modelling and Simulation_, Bangkok, 2013, pp. 208-213. [[**PDF**]](/research/indoorpos/pdfs/[IEEEISMS]Prateek_et_al-2013-Data_fusion_of_dual_foot-mounted_INS_to_reduce_systematic_heading_drift.pdf) [[**CODE**]](https://github.com/prateekgv/openshoe-sphere_limit)
