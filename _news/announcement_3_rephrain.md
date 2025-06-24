---
layout: post
title: PassengXR Motion Platform & UIST Paper
date: 2022-11-18 15:59:00 -0400
inline: false
related_posts: false
description: Led by Mark McGill, the Viajero project has produced an open-source and off-the-shelf hardware and software motion platform for creating vehicular XR experiences: PassengXR. Published at ACM UIST 2022 [1], the motion platform uses ESP32 Arduino sensors to detect the orientation (IMU), velocity (OBD-II) and location (GNSS) of the vehicle and wirelessly broadcast these to a Unity software platform running on standalone XR headsets. This allows practitioners to create passenger XR experiences that make use of, or counteract, the motion of the vehicle.PassengXR supports multiple concurrent users in both individual and shared experiences and includes a number of ways to correct the alignment of vehicle and headset IMUs, which are inherently prone to drifting when in-motion. All code for the motion platform will be made available through GitHub, and more information can be found on the Motion Platform page and in the UIST paper [1].
---

### Reference
[1] G. Wilson, K. M. T. Pohlmann, D. Al Baiaty Suarez, M. Mcgill, and S. A. Brewster, “The spin doctor: leveraging insensitivity to passive rotational & translational gain for unbounded motion-based vr experiences,” in Proceedings of the 2025 chi conference on human factors in computing systems, New York, NY, USA, 2025.