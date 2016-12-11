---
layout: post
title: org.jdrupes.httpcodec
excerpt: ''
---

During the development of [JGrapes](http://mnlipp.github.io/jgrapes/) the
need for an HTTP codec arose that could convert data from and to
`java.nio.Buffer`s. As the solution has no dependencies on the JGrapes
framework, it was factored out in 
[this project](https://github.com/mnlipp/org.jdrupes.httpcodec) as an
independently usable component.
