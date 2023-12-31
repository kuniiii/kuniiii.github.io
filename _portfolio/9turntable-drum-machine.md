---
layout: post
title: "Turntable Drum Machine"
description: "Remixing a turntable with a drum machine."
# collaborators: false
permalink: /portfolio/turntable-drum-machine
# category: portfolio-old
# tags: [arduino, interaction design, generative music]
image:
    path: /images/turntable-feature2.jpg
    thumbnail: /images/turntable-thumbnail.jpg
    caption: "Photo by Peter Kun"
classification: Proof of concept, 2011  
---

Culturally *turntables, drum beats, and remixing* are very related, yet rarely combined with each other. In this project I literally remixed a turntable with a drum machine, creating such an instrument, which combines the benefits of both of its inspirations.

Novel musical interfaces can easily fall into the trap of novelty overwriting usefulness and usability. Novelty "just for the sake" can disregard how different instruments are used, what are their stories and cultural roles.

<iframe src="//player.vimeo.com/video/30322545" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

## Design rationale
Drum patterns are often referred to as *"drum loops"*. They are programmed in a step-sequencer, which follows how music sheets are written: notations in linear lines, divided up into e.g. 16 bars. Considering that they represent a *looping* dynamic, I found the radial movement of turntables a much better representation of drum loops. 

Realizing a drum machine on the turntable, the provided interaction enables the musician maintain the drum beat as a constantly changing flow, and also to scratch the beat, which is a very turntable-specific ability, enabled for drum beats.

<figure>
	<a href="/images/turntable-feature.jpg"><img src="/images/turntable-feature.jpg"></a><figcaption>Proof-of-concept version of a standalone instrument.</figcaption>
</figure>

<figure>
	<a href="/images/turntable-sensors.jpg"><img src="/images/turntable-sensors.jpg"></a><figcaption>Light sensors embedded in styrofoam.</figcaption>
</figure>

## Realization
The proof-of-concept prototype was built from a broken turntable, which was augmented with light sensors embedded into a styrofoam bar. The signal from the sensors are inputted into an Arduino board, which communicates with a Processing sketch to translate the sensor signal into MIDI. Afterwards the MIDI can be picked up by any sampler software, such as Garageband. 

This proof-of-concept prototype was developed in 3 days, and received appreciation by musicians, indicating that this it could be further developed into a more robust product. Being a standalone MIDI instrument, the turntable drum machine could be easily used as a controller for any electronic instrument.

<figure class="half">
	<a href="/images/turntable-sketch.jpg"><img src="/images/turntable-sketch.jpg"></a>
	<a href="/images/turntable-topview.jpg"><img src="/images/turntable-topview.jpg"></a>
	<figcaption>Initial sketch of the hardware, and the proof-of-concept realization.</figcaption>
</figure>
