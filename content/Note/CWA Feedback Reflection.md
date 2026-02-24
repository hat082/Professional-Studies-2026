---
title: CWA Feedback Reflection - Manufacturing Perspective
draft: false
tags:
---
We got the feedback for Coursework A and it confirms we're going with a cyclist-based LiDAR system. [[Meeting 3]] already covered the name change - we've moved away from "RoadSense" to avoid trademark issues. Im thinking Cycloptix, 

## Reflection on Feedback

**Design (compactness)** - This directly impacts my section. Making the device compact for cyclists means we need miniature components, flexible PCBs, and miniaturized sensors. This we should use high-density PCBs, potentially multi-layer boards, and enclosure design. Manufacturing tolerances become tighter, which affects our supplier selection and quality control processes.

**Market (personal cyclists vs e-bike companies)**   This is crucial for manufacturing. Selling to e-bike manufacturers means larger batch sizes, OEM/ODM relationships, and possibly modular design so the sensor package can integrate into different bike frames. Selling to personal cyclists means smaller batches, retail packaging, and potentially a consumer facing warranty and support chain. These are very different supply chains.

Also I am completely unsure of what our pitch will be to the bikers? ( #MR why would someone want to install our stuff? #clarify )

**Branding** - Not relevant to manufacturing section, skipping.

## Product-Specific Manufacturing Implications

Our product uses LiDAR, camera fusion, and 360 radar arrays. This means we need to source: LiDAR modules (Velodyne, RoboSense, or cheaper alternatives like Benewake), camera modules (MIPI CSI interfaces, potentially night vision), radar sensors mayber (77GHz for surrounding detection), IMU/gyroscope for motion sensing ( #PD i thought we might add this? #propose ) , and a compact processing unit. All these need to be integrated into a weatherproof, vibration-resistant enclosure suitable for bicycle mounting.

Distribution will focus on the Netherlands initially - this means we need to consider EU regulatory compliance (CE marking), potentially VAT/shipping logistics for Dutch customers, and possibly partnerships with Dutch cycling organisations or bike shops.
