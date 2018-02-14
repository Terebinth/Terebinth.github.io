---
layout: post
title:  "announcing peregrine"
date:   2018-02-14 00:00:48 +0200
categories: peregrine
---

PEREGRINE is to be a tribute to the 1980s Spectrum Holobyte classic "Falcon", a semi-serious flight simulator for the civilian consumer.  

I'm using Vulkan for the graphics, and plan main development program to be desktop native with Rust as the core language.  I may produce simple versions on other platforms with other languages; Android with Kotlin, iOS with Swift, but mainly want to orient design to powerful laptops running a Unix-based system.

We will not be using a graphics framework, I want to do the GL stuff from the ground up, more or less, and to wind up 'rolling own' framework is the plan. Overall I'm not at all interested in the kind of flashy graphics that a commercial game company would be.  I'll be focused more exploring the challenges getting decent physical dynamics happening, and then frame rate with exact lines for the geometry of the aircraft in perspective over distance.  

If Peregrine is successful, it could serve as the basis for a more general class of simulation and modeling software solutions.  There are both artistic/cultural and technical/scientific trajectories such a project can take.  One direction includes cinematic, gaming, educational applications, and I consider to be culturally valuable.  The other direction includes scientific and technical research software of obvious value, but also includes substantial overlap with realtime operational equipment and sensor managment solutions.  
