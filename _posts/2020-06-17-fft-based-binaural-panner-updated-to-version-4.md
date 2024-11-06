---
title: "FFT-based binaural panner updated to version 4"
tags: 
  - "binaural-synthesis"
  - "fft-based-binaural-panner"
  - "max-msp"
---

The [FFT-based binaural panner](https://github.com/jakobhandersen/fft-based_binaural_panner/ "FFT-based Binaural Panner") is a small project that I initially released in 2011 as a part of my Master's thesis project on 'Realistic mediation of virtual sound sources'. It is a tool for [Max](https://cycling74.com/products/max "https://cycling74.com/products/max") that uses the impulse responses from [The CIPIC HRTF Database](https://www.ece.ucdavis.edu/cipic/wp-content/uploads/sites/12/2015/04/cipic_WASSAP_2001_143.pdf) in order to pan an audio source binaurally to a spherical direction.<!--more-->

![Screenshot from the help patcher for the binpan~ object](/assets/images/ScreenshotBinpanHelpPatcher.png)
*Screenshot from the help patcher for the binpan~ object*

To my surprise, I can see that it is still being downloaded quite often, and I also sometimes receive questions and feedback from users. So now I decided to update it a bit in order to reflect the changes made to Max since 2011, and in order to refine a couple of things that I now feel should be done a bit differently.

Recently I stumbled upon the project [3D Tune-In](http://www.3d-tune-in.eu/ "http://www.3d-tune-in.eu/") which is a big budget EU research project addressing, among other things, hearing loss and how digital games can help in that context. I recommend checking out the project site, where you will also find a link to the free binaural panner VST plugin that was developed as part of the project – even though it might render my binaural panner less relevant.
