---
layout: post
title:  "Progress Report"
date:   2019-09-28 17:16:00 -0400
categories: [Weekly-Progress]
---

Motivation
- This research has been motivated by the humble and pure minds of Team AF in pursuit of truth and knowledge to make the world and tomorrow better
- Pedestrians, when crossing the street, need to be vigilant (using both eyesight and hearing), which is not inclusive towards elderly pedestrians or blind or deaf pedestrians
- Pedestrians are not always crossing the street - waste of light and energy
- In an effort to reduce energy costs and make crossing streets easier for disabled or elderly pedestrians, we aim to improve pedestrian crossing lights by developing a new data acquisition system that will detect motion, sound, and light and transmit information to the pedestrian light.

Current Progress
- We have started to connect the circuitry for the motion sensor, photosensitive sensor, and sound sensor module
- We have understood preliminarily what type of data is outputted from each sensor
- The motion sensor gives a binary value: whether or not motion has been detected
- We have understood how to adjust sensitivity for motion and how to use the motion detector successfully
- The photosensitive sensor gives more continuous values for voltage or it can give binary values
- The sound sensor module gives binary values for whether or not sound is detected
 
Problems Encountered
- Before we got any of the sensors to work, we had a lot of problems with installing the adafruit packages, which obstructed us from successfully completing any of the tutorials that we went through in class.
- We needed to learn how to better navigate the permissions component of installing packages on the Raspberry Pi, which took us about a day to understand.
- It was quite hard to understand how exactly the motion sensor works and how to see whether or not the sensor was working.
- In order to use the sensor successfully, it took us several attempts in which we figured out how to adjust sensitivity and empirically figured out the range of distance that the sensor detects motion in. 
- Adjusting the sensitivity also needed to be done empirically since we did not have any conception quantitatively for how sensitivity works. This needed to be done manually, so we were just performing a sort of trial and error process to finally get the optimal sensitivity level for the motion sensor. 
- We have two Raspberry Pi kits and one of our kits does not have the right analog to digital converter, which has made things more difficult. The converter in that kit has a different type of converter, which will require some soldering. We will have to evaluate going forward how to overcome this challenge either by obtaining a new converter or by finding a place to solder. 
- Some of the sensors give binary values and some give continuous values. Specifically, the sound and motion sensors give binary values while the photosensitive sensor gives more continuous values. Working with binary values for things like motion and sound will not be as informative as working with continuous values. This is one of the primary reasons for why sensitivity was so difficult and will continue to be extremely important throughout this project. 
 
Future Plan
- We have connected all three of our sensors and understood how to collect data from all three. 
- The next step will be to connect some sort of visual indicator that will turn on at some threshold or binary value for each sensor. This visual indicator will most likely be an LED lighting up. 
- Once we have successfully connected those components in a robust fashion, we will have to develop a testing area where we can collect data and implement our device.

<img src="/12740teamAF/assets/motion_sound.jpg" alt="group in CEE lounge" width="500" height="370">
