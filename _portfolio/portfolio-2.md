---
title: "A Torque+Vision-Based Algorithm to Hnadle Robot to Human Object Handover Tasks"

excerpt: "<br/><img src='/images/portfolio-1.png'><br/>"

collection: portfolio
---

Robot-to-human object handover is a complex task that requires accurate perception and planning. Sensor fusion approaches, which integrate data from multiple sensors, have been proposed to improve the accuracy and robustness of the handover process. Our algorithm relies on two complementary sensor modalities: joint torque sensors on the arm and an eye-in-hand RGB-D camera for sensor feedback. While the torque sensor network detects the human receiver's ``intention'' such as: pull, hold, or bump, the vision sensor network detects if the receiver's fingers have wrapped around the object. Networks' outputs are then fused, based on which a decision is made to either release the object or not.
I developed an AI-based robot-to-human object handover algorithm using a 7-DOF Kinova arm and a 3-finger SDH hand, significantly improving human action detection precision from 95% to 98%. Under my supervisor's guidance and collaborating with two teammates, we proposed and implemented a novel method for classifying multiple human actions during object grasping and integrated a vision module for fingertip and contact detection, increasing the handover success rate from 70% to 98%. Additionally, we created a human action classification system using Convolutional Neural Networks (CNN) with joint-level torque sensors and developed grasp detection with a Single Shot MultiBox Detector (SSD) network utilizing an eye-in-hand RGB-D camera.

excerpt: "<br/><img src='/images/portfolio-1.png'><br/>"
excerpt: "<br/><img src='/images/r2h.gif'><br/>"