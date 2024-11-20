---
layout: project
type: project
image: img/teleoperation-test/teleoperation-test.png
title: "Teleoperation Performance"
date: 2024
published: true
labels:
  - Robotics
  - C#
  - Rust
  - WebXR
  - Unity
  - WebAssembly
summary: "A framework for evaluating performance in teleoperation tasks while varying control parameters and view perspective."
---


<p align="center">
<img src="/img/teleoperation-test/teleoperation.png" width="50%">
</p>

# Teleoperation Performance

For people that haven't attempted to teleoperate a robot it might seem like a trivial task, as long as you have the right interface. However, it turns out to be much harder than people expect. This project was developed in Unity to allow researchers to compare the performance of teleoperation users given different configurations. It comes with a few scenes that replicate human dexterity tests used during rehabilitation as well as a few system variables. Experiments can evaluate the performance across task, system reponsiveness, latency, robot kinematics, view perspective, and input device. 

Using this interface, some key insights into teleoperation performance were gained; namely that the performance of users drops of significantly as the experience becomes less and less like using your real hands to do the task. If users are required to use a gamepad, look through a single monitor at the scene, look from slightly further away, or use a system with high latency, their task performance drops off quickly and significantly.
