---
layout: post
title: "Let's get started"
date: 2013-06-15 03:00
comments: true
categories: gsoc
author: Parav 
---

<p> This blog is dedicated to document the implementation of Arduino Libraries for Userspace on the Beaglebone. It is part of two <a href="http://www.google-melange.com/gsoc/project/google/gsoc2013/anujdeshpande92/51001">GSOC</a> <a href="https://www.google-melange.com/gsoc/project/google/gsoc2013/hatguy/24001">projects</a> at <a href="http://beagleboard.org/">Beagleboard.org</a>.</p>

<p> This project will be worked upon by two students, Parav and Anuj; David Anders, Matt Porter and Andrew Bradford have been assigned as the mentors. </p> <!-- more -->

<p> The Arduino hardware and libraries are ubiquitous. A similar set of libraries for the Beaglebone would considerably ease the learning curve for folks from the Arduino community, not accustomed to the linux environment. The Beaglebone can also run other userspace applications side-by-side, something which would become too demanding for the Arduino hardware. This combination would be helpful to hackers and tinkerers who need to get a project up and running in a short amount of time. </p>

<p> This project is forked out of the <a href="https://github.com/energia/Energia">Energia</a> project, a popular Arduino derivative for MSP430 and Stellaris microcontrollers. Dave Anders has already laid foundations for a userspace implementation at https://github.com/prpplague/Energia/tree/userspace. </p>

<p> Owing to the scale of this project, we plan to divide the work between the two of us. We will keep documenting our progress on this blog throughout the duration of this program. Currently, we have following two items on our priority list: 

<ul>
<li>Coding the basic libraries like digital, serial, analog</li>
<li>Getting the IDE to talk with the Beaglebone Black, using USB and ethernet</li>
</ul>

I will post more about this and a list of objectives for both of us in a few days. </p>

<p> If you would like to contribute, a discussion channel exists on freednode: #userspace-arduino </p>
