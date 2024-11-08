---
title: "Realistic mediation of virtual sound sources"
tags: 
  - "3d-sound"
  - "binaural-synthesis"
  - "fft-based-binaural-panner"
  - "head-tracking"
  - "max-msp"
---

Since the first systems for storing and playing back sound were invented in the second half of the 19th century, we have become increasingly better at reproducing sound, resulting in an increasing degree of fidelity. However, we still have difficulties reproducing the spatial properties of a sound phenomenon – the experience of the exact spatial location of the individual sound sources.

In connection with my Master's thesis, in 2011-12, I developed a system that aims at doing exactly this.<!--more--> It uses binaural synthesis, head tracking and acoustics simulation in an attempt to create a realistic sense of the spatiality of sound played though headphones – this, within an experience-oriented context.

It is not the first system of its kind. These technologies have been combined before in different systems for reproducing 3D sound for different purposes. The system is based on the knowledge and experiences gained in the development of such similar systems. However, I also hope to be able to present solutions and experiences that might be a help to any future work in this area.

Below is a video (in Danish) where I present the system and its functionality

{% include youtube.html id='kH4mVUgk9Do' %}
<br/>

The system is developed in [Max (Max/Msp)](https://cycling74.com/products/max).

One of the central parts of the system is the binaural panning / binaural synthesis. I have made this functionality publically available for other Max users, and it can be found here: [FFT-based Binaural Panner](https://github.com/jakobhandersen/fft-based_binaural_panner)

Below, you find my Master's thesis report. It is in Danish, but with an English summary on pages 57-59:

[![Link to download of Master's thesis](/assets/images/speciale-thumb.png)](/assets/downloads/Speciale.pdf)
