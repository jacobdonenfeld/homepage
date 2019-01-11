---
layout: post
title:  "Raspberry Pi Facial Recognition Door Lock"
date:   2019-1-4
desc: "Design and building of a facial recognition door lock"
keywords: "Facial Recognition, OpenCV, Door, lock"
categories: [Blog]
tags: [Facial Recognition, OpenCV, Door, lock]
icon: fa-forward
---

## Overview
Facial recognition runs on the raspberry pi. When a face is detected, it sends a '1' through serial onto an arduino. The arduino opens the relay which delivers power to a steper motor driver. A stepper motor is wound up, then wound down, as to open a door handle then return it to a closed position. 

Future iterations will include an acceleromiter to detect when the door has been opened. 

I used the library https://github.com/ageitgey/face_recognition with my code derived from facerec_on_raspberry_pi.py 

Tuning the stepper driver requires a multimeter and a screwdriver. On the A4988 data sheet, it gives the equation **INSERTEQUHERE**. This requires knowing the R_sense pin. This will depend on every board and requires checking for the specific model. Check the resistance onf the resistor pictured here. 

It is important that the stepper is not plugged in so there is no additional current draw. I first set the multimeter to 20V, then attached a common ground. The voltage can be referenced off the pin used to adjust the current. From the equation previously stated, adjust the voltage to set the current at or below what the stepper motor is rated. 



