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
