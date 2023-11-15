---
layout: post
title: "Kulturhus Orchestra"
description: "An orchestra to jam with interactive coffeetables and mobile devices."
permalink: /portfolio/kulturhus-orchestra
image:
    path: /images/kulturhus-orchestra-feature.jpg
    thumbnail: /images/kulturhus-orchestra-thumbnail.jpg
    caption: "An orchestra to jam with interactive coffeetables and mobile devices. Photo by Peter Kun"
collaborators: "Niels Swinkels, Laura Rebolo, Markus Jansson, Robert Fohlin"
---

<!-- ---
layout: post
title: "Kulturhus Orchestra"
description: "An orchestra to jam with interactive coffeetables and mobile devices."
category: portfolio
tags: [installation, interaction design, generative music]
image:
  feature: kulturhus-orchestra-feature.jpg
  homepage: kulturhus-orchestra-thumbnail.jpg
homepage: true
comments: false
collaborators: "Niels Swinkels, Laura Rebolo, Markus Jansson, Robert Fohlin"
--- -->

## Brief
To enable co-creation and cultural activities in the public space, of a new culture house in Gothenburg.

## Outcome
A stable, well-scaling prototype was built, which was an engaging part of the exhibition, inviting most of the visitors to join in the social experience of jamming while grabbing a coffee.

<iframe src="//player.vimeo.com/video/68182156" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

## Description
We designed and built a web-based music system, where people can participate via an interactive coffee table (Microsoft Surface) or via smartphones, tablets.

The system always generates harmonic music, so participation is enjoyable even for people without musical training.

<figure>
	<a href="/images/kulturhus-orchestra-story-sketch.jpg"><img src="/images/kulturhus-orchestra-story-sketch.jpg"></a><figcaption>Pitching the concept with a story during ideation.</figcaption>
</figure>

## Design rationale
Coffee breaks (*“fika”*) are perhaps the most important part of the Swedish culture – the time when a group socialize, but also a moment people invite others for. Scandinavian people, perceived typically as distant and shy, have this specific, slow-yet-warm way of socializing.

This project was an exploration to augment fika with “jamming”, a rather typical social get-together in the Mediterranean culture, the very activity when strangers meet and play music together on the street or at a bar.

<figure>
	<a href="/images/kulturhus-sketch.jpg"><img src="/images/kulturhus-sketch.jpg"></a><figcaption>Sketches from the ideation process. Credit: Laura Rebolo.</figcaption>
</figure>

<figure>
	<a href="/images/kulturhus-puredata.jpg"><img src="/images/kulturhus-puredata.jpg"></a><figcaption>Musical output generated through Pure Data code.</figcaption>
</figure>

## My role
I believe one of the most compelling type of user experience is to enable anyone to perform a complicated activity with ease and joyful involvement, without previous training. I find musical knowledge as a perfect case for this.

Thus, in this project my main involvement was to **design a generative system**, which makes sense of the user activity as an input, and outputs that as musical output. The realization was in Pure Data, utilizing MIDI for communication with Ableton Live as a sampler.

## Process
The beginning of the project was spent on analysing the brief and ideating within the given design space.
Throughout the design process, a completely modular system was created, whilst iterating several lo-fi prototypes to test out different devices as musical instruments.

We opted for web clients and Surface in the end, because of time limitations and robustness considerations for the installation.

<figure class="half">
	<a href="/images/kulturhus-surface.jpg"><img src="/images/kulturhus-surface.jpg"></a>
	<a href="/images/kulturhus-mobile.jpg"><img src="/images/kulturhus-mobile.jpg"></a>
	<figcaption>The different interfaces of the system.</figcaption>
</figure>
