---
layout: project
type: project
image: img/maho/maho-square.png
title: "Maho"
date: 2024
published: true
labels:
  - Python
  - Multi-Processing
  - Inter Process Communication
summary: "A library for seamlessly connecting python processes across mutliple computers."
---

## Maho

Maho is a Python library designed to make inter-process communication between Python processes trivial. By focusing on Python-Python communication, it is able to have two significant strengths over multi-language IPC protocols. Firstly, because interfaces are defined by Python functions and shared from client to server, many existing Python functions can be exposed to other processes without modification. Secondly, because Python is interpreted, we can pass complex objects, like callbacks, across the IPC boundary. With Maho, writing code that runs across processes and machines is as easy as writing code that runs on one.

## Key Uses

Scientists often have to interface with a number of different hardware interfaces and a number of different computers. Maho trivially allows users to easily orchestrate and connect these processes running where they need to run. This significantly reduces the development time of multi-process code.
