---
layout: post
title:  "Final Report"
date:   2019-10-17 22:10:00 -0400
categories: [Weekly-Progress]
---
INTRODUCTION
This research has been motivated by the humble and pure minds of Team AF in pursuit of the truth and knowledge to make the world and tomorrow better. Pedestrians, when crossing the street, need to be vigilant (using both eyesight and hearing), which is not inclusive towards elderly pedestrians or blind or deaf pedestrians. Pedestrian signals are always on even when pedestrians are not in the vicinity, which is a waste of energy. In an effort to reduce energy costs and make crossing streets easier for disabled or elderly pedestrians, we aim to improve pedestrian crossing lights by developing a new data acquisition system that will detect motion, sound, and light and transmit information to the pedestrian light.

PROBLEM STATEMENT
The aim of this project is to create an assistive sensor-based pedestrian signal that utilizes a combination of sound, PIR, photosensitive and vibration sensors to detect pedestrian motion and sounds and also passing cars so that the pedestrian signal gives the appropriate signal to either cross the road or wait. During times when no pedestrians are detected, the signal is off in order to save energy. 

REVIEW OF SENSORS BEING UTILIZED
Sound Detection Sensor Module
Physical Principles
The Sound Detection sensor module has a built-in capacitive electret microphone which is highly sensitive to sound. Sound waves cause the thin film of the electret to vibrate and then the capacitance changes, thus producing the corresponding changed voltage, so it can detect the sound intensity in ambient environment. Since the change is extremely weak, it needs to be amplified. We use a LM393 as the power amplifier here. You can adjust the sensitivity by adjusting the Potentiometer. When the sound level exceeds the set point, an LED on the sensor module is illuminated and the output is sent low.
Note: This sound sensor is used to detect whether there’s sound surround or not; it cannot recognize the frequency or volume.

Sensor Characteristics
Specifications of sound detection sensor module:
Working voltage: DC 3.3-5V
 Adjustable Sensitivity
Dimensions: 32 x 17 mm
Output in the form of digital switching outputs (0 and 1 high and low)
The image and table below detail the controls, pin outs, and other key components.

<img src="/12740teamAF/assets/figure_1.png" alt="figure 1" width="250" height="150">
Figure 1. Sound sensor module
GND, is connected to ground, then VCC is connected to +5V

<img src="/12740teamAF/assets/figure_2.png" alt="figure 2" width="300" height="400">

<img src="/12740teamAF/assets/figure_3.png" alt="figure 3" width="400" height="200">

<img src="/12740teamAF/assets/figure_4.jpg" alt="figure 4" width="350" height="200">

<img src="/12740teamAF/assets/figure_5.jpg" alt="figure 5" width="450" height="200">

<img src="/12740teamAF/assets/figure_6.jpg" alt="figure 6" width="450" height="200">

<img src="/12740teamAF/assets/figure_7.png" alt="figure 7" width="150" height="100">

<img src="/12740teamAF/assets/figure_8.jpg" alt="figure 8" width="200" height="100">

<img src="/12740teamAF/assets/figure_9.png" alt="figure 9" width="700" height="400">

<img src="/12740teamAF/assets/figure_10.png" alt="figure 10" width="500" height="350">

<img src="/12740teamAF/assets/figure_11.png" alt="figure 11" width="700" height="300">

<img src="/12740teamAF/assets/figure_12.png" alt="figure 12" width="700" height="250">

<img src="/12740teamAF/assets/figure_13.png" alt="figure 13" width="600" height="250">

<img src="/12740teamAF/assets/figure_14.png" alt="figure 14" width="550" height="300">

<img src="/12740teamAF/assets/figure_15.png" alt="figure 15" width="600" height="200">

<img src="/12740teamAF/assets/figure_16.png" alt="figure 16" width="600" height="450">

<img src="/12740teamAF/assets/figure_17.png" alt="figure 17" width="700" height="500">

<img src="/12740teamAF/assets/figure_18.png" alt="figure 18" width="550" height="200">

<img src="/12740teamAF/assets/figure_19.png" alt="figure 19" width="650" height="200">
