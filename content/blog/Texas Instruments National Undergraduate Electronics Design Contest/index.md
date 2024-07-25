---
title: Texas Instruments Cup Undergraduate Electronics Design Contest
summary: Auto-tracking Electromagnetic Cannon
date: 2019-12-01
authors:
  - admin
tags:
  - Bachelor
  - Robotics
image:
  caption: 'Contest Logo'
---

## Abstract

The system incorporates the NXP K60 chip as the control core, in conjunction with the RoboMaster GM6050 head motor, OpenMV camera, electromagnetic gun, laser ranging and feedback device, to create an electromagnetic bending gun system. The OpenMV camera is responsible for identifying the guide sign and transmitting its position to the microcontroller via UART. The microcontroller then receives this positional data and utilizes it to control the dual closed-loop motor head, enabling a rapid and precise aiming of the robot towards the target position via CAN bus. Subsequently, the microcontroller oversees the rapid targeting of the intended position via the CAN bus, utilizing the positional data it has received. Concurrently, the K60 microcontroller oversees the charging of the capacitor via the relay. Upon receipt of the signal indicating the completion of charging and aiming, the K60 initiates the discharge of the capacitor. Concurrently, the electromagnetic gun is discharged. In order to achieve the desired positioning of the electromagnetic cannon, the use of speed and position closed-loop control of the head is essential. This enables the electromagnetic cannon to achieve a suitable firing angle, thereby ensuring optimal performance and stability.

## Task

Design and build an electromagnetic cannon, with adjustable horizontal and vertical elevation of the barrel, which shoots the projectile by electromagnetic force and hits the target ring, with a firing period of no more than 30 seconds. The electromagnetic gun is powered by a DC regulated power supply, and capacitive energy storage elements are permitted in the electromagnetic gun system.

![](.\fig1.png)

![](.\fig2.png)

## Design



### Gimbal self-stabilizing

{{< video src="gimbal self-stabilising.mp4" controls="yes" >}}

### Target tracing

{{< video src="target tracing.mp4" controls="yes" >}}
