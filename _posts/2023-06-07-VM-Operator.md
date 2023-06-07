---
layout: post
title: Run Qemu in Kubernetes (VM-Operator)
excerpt: ''
---

It took me some time to get this started, but finally, I have some
[working code](https://github.com/mnlipp/VM-Operator) and a 
[web site](https://mnlipp.github.io/VM-Operator/) for the project.

The main "problem" is that the
[script based intermediate solution](https://github.com/mnlipp/kube-qemu-legacy)
does 95% of what I need (and 80% of what I want).