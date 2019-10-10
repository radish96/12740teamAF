---
layout: post
title:  "TA Meeting"
date:   2019-10-01 16:44:00 -0400
categories: [Weekly-Progress]
---

We met with the TA and got a lot of good ideas for how to move forward with the project. Mainly, Jingxiao introduced the idea
of using the vibration sensor to find some sort of threshold between the vibrations of a car and the vibrations of a person. 
Once we find that we will be able to distinguish between cars and pedestrians using only one sensor. This would then help us to
understand when the pedestrian signal should be on and eliminate the error cases that the motion and sound sensors might have
where they pick up on motion or sound from a car rather than a pedestrian. In our discussion, we highlighted the importance
of safety and ensuring that it is imperative that our project not have any error cases since lives are at stake in this particular
situation. 

In addition, we discussed how we would be able to test our pedestrian signal without actually placing our device on a traffic
signal outside. We decided that we need to make our own toy traffic signal using the LEDs given to us in the Raspberry Pi. We 
would just simulate a traffic signal where it is red for thirty seconds and then green for thirty seconds (for example). Given 
the fact that we have now decided to detect both cars and pedestrians, we have two binary variables in addition to the traffic 
signal binary variable. Thus, we have three binary variables, which means we have exactly eight cases to consider. The cases 
are shown in the table below. We believe that it is important to consider all three of these variables because we are maximizing
safety. Although it may be feasible to only use the traffic signal binary variable, this means we are assuming that all cars 
are obeying traffic rules. We deemed this assumption to be invalid. 

<img src="/12740teamAF/assets/eight_cases2.png" alt="eight cases" width="600" height="370">
