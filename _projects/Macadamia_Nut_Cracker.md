---
title: Macadamia Nutcracker Design
layout: project
description: Designing a nutcracker using Force Multiplication via Lever Arm Moments.
image: /assets/images/Macademia Nut.png
---

## Find

Design a simple hand-operated lever nutcracker that can crack a macadamia nut. The design should be feasible for a person to use by hand, and then it should be modified to use a linear actuator instead of hand grip force. A typical in-shell macadamia is about 20 mm and above in diameter, and published testing on whole macadamia nuts reports cracking forces around 488.4 lb, so the nutcracker must provide substantial mechanical advantage.
---

## Given

Force to Crack: 488.4 lb

Human Grip Strength: 150 lb

Nut diameter: 20 mm

Nutcracker Type: two handel lever with one pivot

---

## Find

A feasable design of a nutcracker that can crack the nut.

---

## Approach

Free body diagram, moment balance:

F_in * L_in = F_out * L_out

Let L_in = 1m, then with some basic math we get that F_in only has to be 4.9 lbs to break the nut


---

## Nutcracker Design Diagram

<img src="{{ "/assets/images/Macademia Nutcracker.png" | relative_url }}" alt="System diagram" width="400">

## Usability Discussion

Having a 1m long nutcracker is immensly unweildy, but it means that even the smallest infants can break the nut. 

This design could be improved by shortening the length of the nutcracker, perhaps including more pivots to increase mechanical advantage further. 
---
