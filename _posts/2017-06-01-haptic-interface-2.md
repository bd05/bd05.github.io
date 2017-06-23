---
layout: post
title:  "Haptic Interface - Part 2"
date:   2017-06-01
image: pcb.jpg
---

This is just a quick summary of what we ended up doing for our Haptic Interface project for ELEC 391. I won't get into the details of how all the hardware was done. 

We started out with an unclear idea of what the criteria of the project was supposed to be, I guess. All we understood is that we had to build something with linear motors that provided tactile feedback. Throughout the duration of the semester the professor clarified what he expected, and standards rose based on what others in the class were implementing (part way through the semester we were told we would be marked comparitively, not objectively based on a rubric).

In the end the baseline requirements were:


- Linear motors had to be gearless and as frictionless as possible. Our motors were essentially just a copper coil with cylindrical magnets in them, in fact. Applying a current through the coil would induce a magnetic field, pushing the magnets in one direction. This way the user felt almost no friction as they moved around the effector, which was ultimately attached to both motor's rotors.
- Machine had to be both a haptic interface and be capable of autonomous movement. We achieved this by having different "modes", selectable in our web user interface. Some of these modes would draw different shapes autonomously, some of these modes would provide different forms of haptic feedback. For example, one mode would only let you move in a certain area within the workspace, as if there were walls within the workspace. Another mode tried to mimick the feel of pushing on a spring. Using PID the force with which the effector pushed back on the user as he/she tried to push in one direction would increase, as if pressing down on a spring.
- Most of the circuiting had to be done on a custom made PCB. I can't really take credit for this, as I didn't do most of the PCB design. My partner really carried the weight for that one.

![pcb]({{ site.url }}/img/pcb.jpg){: .center-image }