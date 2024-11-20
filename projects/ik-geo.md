---
layout: project
type: project
image: img/ik-geo/ik-geo-square.png
title: "IK-Geo"
date: 2024
published: true
labels:
  - Robotics
  - Rust
  - Python
  - C++
summary: "Packaging and distributing a state of the art analytic inverse kinematics solver. Algorithms and core code attirbuted to the IK-Geo paper: https://arxiv.org/abs/2211.05737"
---

# IK-Geo

The IK-Geo algorithm found in [this paper](https://arxiv.org/abs/2211.05737) is designed to yield analytic solutions to inverse kinematics problems for 6 axis robot arms with extremely good performance and precision. Our IK-Geo packages take an uncompromising approach to introducing usability to these algorithms. Written in Rust and optimized for performance, the Rust, C++ and Python packages all use the same backend to provide all possible solutions to the IK equations with the convenience of installing a Python package.

## Key Points

In the field of academic computer science, there is a huge value to having people use your code and build off of it. One challenge, though, is that those doing the research are not necessarily experts in distributing and making the software easy to use. With a lower barrier to access, research algorithms have the potential to have much broader engagement and interaction with both the academic and industrial computer science community.
