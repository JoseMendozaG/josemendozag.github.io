---
title: "MR WAS"
excerpt: "Creation of an Automated Guided Vehicle (AGV) to do collaborative work in an Industrial Warehouse (2019). <br/><img src='/images/MrWAS1.JPG'>"
collection: portfolio
---

Part of a semester project we design, manufactured and developed an AGV that can lift 20kg with its 14kg of weight. Also awarded third place on the Engineering Expo of the campus. 

## Application

MR WAS was a challenge proposed by my college (Tecnológico de Monterrey) and the automatization company "Fluxing Engineering" with the objective of creating an AGV that could work in an industrial warehouse delivering materials and components from the storage facility to the operators stations autonomously. 

The main requirements for the robot were:
* Size should not exced 1x1.5 m.
* Must be capable of carrying a load of 20 kg max, on a top plate of at least 0.4x0.4 m without having the load 0.6 m above the ground.
* Must be capable of lifting the load to 1.2 m above the ground.
* Must have a securty system to avoid frontal colissions. 
* Must follow a white line with black/gray background and detect intersections by color. 
* Should have a mobile app to control it.

As a team formed by 5 mechatronics engineers I was selected to be the project manager and we asigned roles to the other team members as Mechanical, Electronics and Software lead respectively. We were competing against other 5 teams. 

## Chasis

At the beggining of the project all the team members shown a design proposal to which mine was selected because its low cost and easy manufacturability without compromising the structure. In fact, at the end our robot was the lightest, strongest and with more load-lifting capacity. 

The robot's structure were four 1/4" aluminum plates oriented vertical and held together with several 5/8" hexagonal spacers. Thanks to this model we used the faces of the hexagonal spacers to support all the components and also an easy cabling routing. It is worth mentioning that all the manufacture was done by our team inside the Univeristy's laboratories.

## Lift Mechanism

On top of the robot we designed an easy-to-remove nylamid plate so we could access the inside of the robot quickly and, if the user wanted another mechanism/technology on top, you could change it with only unscrewing four bolts. The nylamid plate we used held a scisors lifting mechanism powered by a linear actuator. 

Based on calculations and average efficiency rates, our design was capable of lifting more than 20kg with ease to the height specified for the challenge. 

## Electronics

For the power system we were given two motors for the movement and also a 3000 mha battery that we conected through a power-pcb that also had the emergency stop circuit and the avoid-front-collisions system using IR sensors and a bumper. For the movement we used a H-bridge for each motor controlled by an NXP microcontroller. Also, we isolated the logics circuit from the power one. 

In order to follow the line we had an array of 8 IR sensors facing the floor with a RGB sensor behind, what we did not expect was how close those sensors needed to be to the ground, so we encontered several issues when the floor wasn't enterely flat. We solved those issues by changing the rigid brackets that held the sensor to flexible ones that allowed the sensor to move instead of collide with the floor. 

## Software

We programed the emergency, power and logic system to work al all times while being conected to the mobile app that we designed bia Wi-fi. The robot had three modes: 
* Manual 
* Pre-charged routes
* Back to charging station
And also we installed LEDs that shown the status of the robot. Ex, yellow for charging, red for emergency status, blue for conection sucessfull, etc. 

By the end of the semester the robot was capable to move around a warehouse following a line and taking decitions based on the color of the intersections, also capable of carrying and lifting a load of 20 kg and had the confidence that it was ready to prevent any frontal colissions but even if a collision was innevitable, the impact would be cushion by the bumper. On the other had, we provided a friendly app for the user to monitor and control the robot. 

<br/><img src='/images/MrWAS1.JPG'>