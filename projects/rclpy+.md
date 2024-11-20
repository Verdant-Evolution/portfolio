---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "Cotton"
date: 2014
published: true
labels:
  - Lisp
  - GitHub
summary: "An extension to the Python ROS Client Library to accelerate ROS2 development."
---

# RCLPY+

ROS2 is a useful communication layer and framework for robotics projects, however, it suffers from a couple of notable limitations when using the ROS Python Client Library (RCLPY) that RCLPY+ aims to address. Firstly, RCLPY only supports AsyncIO based concurrency and RCLPY+ addresses this by adding support for Gevent, which results in a better developer experience. Secondly, there is a significant amount of boilerplate that is required with RCLPY that is automatically handled with RCLPY+, allowing users to focus on what they want to do and not how they do it. Lastly, RCLPY+ maps natural Python language semantics to ROS concepts of Publishers, Services, and Actions, allowing users to interface with the ROS networked ecosystem just like they would read variables, call functions, and use co-routines / generators. 

## Key Points

By removing boilerplate and mapping ROS concepts to natural Python concepts, RCLPY+ makes it much faster to create and iterate on ROS based multi-process programming and leverage existing ROS based tools.