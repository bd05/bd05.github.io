---
layout: post
title: Review - Wooden MeArm
excerpt_separator: <!--more-->
image: mearm.jpg 
date:   2015-12-01
---

I ordered a wooden Mearm a long time ago off of Ebay for fun. I forget which shop exactly I ordered it from on Ebay, but I after shipping and handling I think it came to about $50 CAD. The parts were laser cut wood, but unfortunately didn't come with any motors. <!--more--> [Mearm][mearm-hackaday] is a low cost DIY robot arm for hobbyists, created by Hackaday, I think. remember it being advertised as a "kit" so I wish they had mentioned that motors were not included...Oh well. I ordered 9g micro servos motors off of Ebay separately. 

After the motors arrived I assembled the robot parts right away, which was a pretty straightforward process. A CD with pdf instructions came with it, though you could always just Google Mearm instructions. 

![mearm]({{ site.url }}/img/mearm.jpg)

Adafruit has a nice servos motor library for Arduino. I tested a single micro servos with it first to get the hang of it, then modified the code to fit in four servoses, made sure they could be controlled with potentiometers, then hooked up ther servoses in the robot arm. 

Later I also bought an ADXL345 accelerometer, so I could control the servos motors was controlled by the tilt of the accelerometer.

The servos motors were pretty weak for the weight of the robot arm. It would move really slowly, or shake and struggle as it tried to lift its heavy head. Eventually one of the motors burned out, and I stopped trying to play around with it. I'm not sure if this was because I bought really cheap motors (they were like $2 each), or because the wood was too heavy... I saw a bunch of metal Mearms on Ebay... I wonder if those are mobile at all! 

Whether it be my cheap micro servos motors or the weight of the wood, I'd probably recommend either buying the acrylic Mearm parts from Hackaday, or 3D printing your own parts and setting the infill setting as low as possible. These parts don't need THAT much precision, so long as they can still fit together. (And if you're off they're a good size for simply sanding down anything too big.) 


[mearm-hackaday]:      https://hackaday.io/pdroject/181-mearm-your-robot