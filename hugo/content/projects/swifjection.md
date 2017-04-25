+++
title = "Swifjection"
tags = ["Swift", "iOS", "Open Source"]
slug = ""
draft = false
date = "2017-03-01T15:29:44+01:00"
showpagemeta = true
categories = ["project"]
comments = false
showcomments = false

+++

### Overview

 [Swifjection(https://github.com/ApplauseOSS/Swifjection) -- lightweight and simplistic dependency injection framework written in Swift for Swift .

The main idea behind this project is to achieve DI for Swift objects that does not inherit from Objective-C classes.

### Technical details

We built **Swifjection** for our use in the first place. These are the key points what was our motivation:

* No need to inherit from `NSObject` in order to inject dependencies
* To inject *pure* `Swift` types you just need to conform to simple `Injectable` protocol
* No action required to inject `NSObject` sublcasses, or classes conforming to `Injectable` protocol
* Clear and simple binding system inspired by Objective-C framework [Objection](https://github.com/atomicobject/objection)
* Lightweight -- we wanted to avoid unnecessary clutter and made the APIs as simple as possible

---
<sup>
**Client:** AAC+ Player</br>
**Platform:** iOS Framework</br>
**Role:** Co-Author, Developer
</sup>