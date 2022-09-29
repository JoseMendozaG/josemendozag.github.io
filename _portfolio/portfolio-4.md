---
title: "Very Small Size Soccer"
excerpt: "Three robots compete in a soccer match using robotic vision (2020). <br/><img src='/images/vsss.png'>"
collection: portfolio
---

With aim for the Mexican Robotics Tournament, I designed a robot's template that would be used for the three two-wheeled robots. Using computer vision and control systems we developed autonomous soccer-playing small robots. Sadly we were not able to participate in the tournament due to the covid pandemic. 

## The Robot
=====
<p style='text-align: justify;'>
In a space no grater than 7.5x7.5x7.5 cm (as limited by the tournament rules), I designed three robots that had a 3D printed structure held together with brass spacers, two motors, lipo batery, dual H-bridge and a esp32 microcontroller. Using wifi, we comunicated with each robot through the computer which had the image processing algorithms.
</p>

## The Vision
=====

<p style='text-align: justify;'>
As the robots need to be autonomous, we used a hd camera mounted on top of the field to get a clear image of the match. Each frame was processed with a only-white-filter to calibrate the position of the field limits and sections; at the same time, the original image is processed with a color-filter to locate our robots and the ball. 
</p>