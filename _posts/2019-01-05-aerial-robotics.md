---
title: "Aerial Robotics"
categories:
  - Extracurricular
tags:
  - Software
header:
  teaser: /assets/images/tarthb.png
  og_image: /assets/images/tarthb.png
---

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Joining the Texas Aerial Robotics team was a decision I made early into my collegiate career, and has had a great deal of influence over my
projected career path. As my first real experience working with an extensive code base, It was a very formative experience for me, exposing me to high level concepts like autonomous vehicle
architecture, computer vision, and API usage. This also came with learning some basic procedures necessary to operate in a large collaborative code base. Picking up common
best practices including using Git, abiding by formatting conventions, and participating in code reviews all built the foundations of my programming abilities. Although I have had a substaintial
amount of programming experience from homeworks and independent projects, these new collaborative programming skills but gave me the ability to easily manage my work and a better understanding of
writing readable code.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Building up a wealth of knowledge regarding the system architecture was a substaintial challenge for me, however, once I had a firm grasp of its operation
I was prepared to being working with the computations team to develop application layer programs that dictate the UAV's pending flight path. My inital project was building a two dimensional
simulation to mimic the operation of targets in the International Aerial Robotics Competition (IARC). These target __Roomba__ robots operated under a set of criteria based on their proximity to
other targets, contact with the UAV, and their positioning relative to the bounds of the area of operation. This simulation was written in C++, with a class created to store each target's current
state. The most challenging part of this simulation was managing the headings of each target. Each collision incident required an update to the heading, and the given reaction was dependent of the
pre-collision heading of the target. Being able to manage both of these conditions for multiple targets when colliding was burdening, but once completed, made the simulation much simpler to work with.
With the heading set, objects were free to progress along their path of trajectory. My astrodynamics coursework had exposed me to attitude dynamics, which eased much of the computational leg work
required for this model.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When this competition cycle concluded, I was granted another oppurtunity to work on a similar challenge. I was again working to build a simulation of the competition
enviroment, but with a new IARC rule set, many new intricacies were introduced.