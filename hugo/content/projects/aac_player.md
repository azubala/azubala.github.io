+++
title = "AAC+ Player"
tags = ["CoreAudio", "iOS", "Freelance"]
slug = ""
draft = false
date = "2011-03-01T15:29:44+01:00"
showpagemeta = true
categories = []
comments = false
showcomments = false

client = "AAC+ Player"
platform = "iOS Framework"
role = "Developer, Solution Architect, freelancing"

+++

### Overview

Fully featured player for audio streams encoded with AAC+. Framework provide mechanism for bufferning the stream and playback control. Library packaged in the way the systems frameworks are.

### Technical details

Inegrated Custom AAC+ decoder written in C, which delivered raw encoded audio samples, the iOS library was responsible for feeding raw data into cyclic `CoreAudio` buffers.

