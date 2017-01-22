+++
title = "Applause iOS SDK"
showpagemeta = true
tags = ["iOS", "Applause", "SDK", "MBM"]
showcomments = false
date = "2015-09-01T19:36:49+01:00"
categories = []
slug = ""
comments = false
draft = false

+++

### Overview

Applause iOS SDK is a framework for [Mobie Beta Management service](https://www.applause.com/mobile-beta-management/). It's a library that customer integrates with his application in order to receive users feedback and bug reports about his product. In addition Beta Management also includes participant session information as well as automatic crash reporting. To make sense of all the incoming data, the dashboard filters and neatly organizes bugs, feedback, session logs and crash reports in real time to maximize your efficiency.

### Technical details

The core code base was built in early 2010 so the most crucial task is to keep code clean and robust. We use TDD aproach and focus on test coverage, in addition we use heavily DI framework called [Objection](https://github.com/atomicobject/objection).

Framework has three channels of distributions:

- manual integration -- using `.framework` package (before it was official supported in Xcode we had to built it from static library and package accordingly)
- Cocoapods integration
- auto instrumentation -- it's an Applause inveted *magic* which allows us to integrate our library to already built apps!

---
<sup>
**Client:**	Applause Inc.</br>
**Platform:**	iOS Framework</br>
**Role:**		Team Leader
</sup>