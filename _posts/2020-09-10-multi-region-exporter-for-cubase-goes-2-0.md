---
title: "Multi-region Exporter - for Cubase goes 2.0!"
tags: 
  - "multi-region-exporter-for-cubase"
  - "cubase"
---

I recently found out that the [Multi-region Exporter - for Cubase](https://github.com/jakobhandersen/multi-region_exporter_for_cubase) has had a serious bug from the beginning: it could not handle tempos (tempi?) other than the default 120 bpm unless the track was set to 'linear mode' (as opposed to the default 'musical mode').<!--more--> I don't know why I hadn't considered testing with different tempos back in the day, but luckily user Anthony Paiano contacted me about some strange behaviour of the program.

Fixing the bug involved brushing up my high school calculus and a good bit of research before finally, and partly by accident/luck, arriving at the formulas below surrounded by double boxes:

![Picture of my scribbles trying to fix the bug](/assets/images/IMG_3479-scaled.jpg)
*Don't ask!*

Besides the fixing of the tempo bug, version 2.0 also contains some other improvements, for example the ability to convert into many different audio formats (previously only mp3).

So feel free to grab the new(est) version [from here](https://github.com/jakobhandersen/multi-region_exporter_for_cubase/releases/latest), preferably before your neighbour.  
Come on, it's 2.0!

And also, please let me know, if you find any new/old bugs in this version.
