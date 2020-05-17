---
title: 'Shimi and Prosody'
subtitle: 'Using Musical Prosody for Robotic Interaction'
date: 2020-01-30 00:00:00
description: This page is a demo that shows everything you can do inside portfolio and blog posts.
featured_image: '/images/shimi.jpg'
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/mDAmApNw5wo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

###### About:
My work with Shimi focuses on generating a new non-speech voice while avoiding uncanny valley and developing better human-robot interaction. This was done using prosodic audio generated through deep learning on an embedded Nvidia Jetson TX2. I was able to show that using this new voice created a more trustworthy version of Shimi than using a human voice.

### Grants
###### National Science Foundation, National Robotics Initiative - $669,912.00
In 2019 I was the primary author with my advisor Gil Weinberg for an NSF grant [Creating Trust Between Groups of Humans and Robots Using a Novel Music Driven Robotic Emotion Generator](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1925178&HistoricalAwards=false)

### Press:
[Shimi Will Now Sing to You in an Adorable Robot Voice](https://spectrum.ieee.org/automaton/robotics/artificial-intelligence/shimi-will-now-sing-to-you-in-an-adorable-robot-voice)
IEEE Spectrum - 05 Mar 2019


### Publications:
[Establishing  Human-Robot  Trust  through  Music-Driven  Robotic Emotion  Prosody  and  Gesture](https://arxiv.org/pdf/2001.05863.pdf)


28th IEEE International Conference on Robot & Human Interactive Communication

Richard Savery, Ryan Rose and Gil Weinberg

*Abstract:*
As human-robot collaboration opportunities continue to expand, trust becomes ever more important for full
engagement and utilization of robots. Affective trust, built on
emotional relationship and interpersonal bonds is particularly
critical as it is more resilient to mistakes and increases the
willingness to collaborate. In this paper we present a novel
model built on music-driven emotional prosody and gestures
that encourages the perception of a robotic identity, designed to
avoid uncanny valley. Symbolic musical phrases were generated
and tagged with emotional information by human musicians.
These phrases controlled a synthesis engine playing back prerendered audio samples generated through interpolation of
phonemes and electronic instruments. Gestures were also driven
by the symbolic phrases, encoding the emotion from the musical
phrase to low degree-of-freedom movements. Through a user
study we showed that our system was able to accurately
portray a range of emotions to the user. We also showed with
a significant result that our non-linguistic audio generation
achieved an 8% higher mean of average trust than using a
state-of-the-art text-to-speech system.

[Finding Shimi's Voice: Fostering Human-Robot Communication With Music And a NVIDIA Jetson TX2](http://lac.linuxaudio.org/2019/doc/savery.pdf) //

Linux Audio Conference 2019

R Savery, R Rose, G Weinberg

*Abstract:*
We present a novel robotic implementation of an embedded linux
system in Shimi, a musical robot companion. We discuss the challenges and benefits of this transition as well as a system and technical overview. We also present a unique approach to robotic gesture
generation and a new voice generation system designed for robot audio vocalization of any MIDI file. Our interactive system combines
NLP, audio capture and processing, and emotion and contour analysis from human speech input. Shimi ultimately acts as an exploration
into how a robot can use music as a driver for human engagement.
