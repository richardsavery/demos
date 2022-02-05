---
redirect_from: "/emotionalmusicalprosody"
title: 'Emotional Musical Prosody'
subtitle: 'Using Musical Prosody for Robotic Interaction'
date: 2020-02-30 00:00:00
description: This page is a demo that shows everything you can do inside portfolio and blog posts.
featured_image: '/images/shimi.jpg'
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/mDAmApNw5wo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

###### About:
My work with Emotional Musical Prosody started with the broad question of what voice a robot should use to communicate. I focused on generating a new non-speech voice, aiming to avoid uncanny valley, and allow a robot to talk like a robot. This was done using prosodic audio generated through deep learning on an embedded Nvidia Jetson TX2. After creating the voice I was able to show increased levels of trust in users when collaborating with Shimi. These metrics then led to the development of a successful NSF grant with my advisor Gil Weinberg, which commenced in November 2019.

After being awarded the NSF grant, the main portion of my PhD reserach focused on expanding Emotional Musical Prosody to robotic arms and groups of robots, eventually becoming my dissertation: [Machine Learning Driven Emotional Musical Prosody for Human-Robot Interaction](https://smartech.gatech.edu/handle/1853/66096)



### Grants
###### National Science Foundation, National Robotics Initiative - $803,892.00
In 2019 I was the primary author with my advisor Gil Weinberg for an NSF grant [Creating Trust Between Groups of Humans and Robots Using a Novel Music Driven Robotic Emotion Generator](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1925178&HistoricalAwards=false)

### Press:
[Shimi Will Now Sing to You in an Adorable Robot Voice](https://spectrum.ieee.org/automaton/robotics/artificial-intelligence/shimi-will-now-sing-to-you-in-an-adorable-robot-voice)
IEEE Spectrum - 05 Mar 2019


### Publications:
[Machine Learning Driven Emotional Musical Prosody for Human-Robot Interaction](https://smartech.gatech.edu/handle/1853/66096)

Georgia Tech, PhD Dissertation

Committee:
- Dr Gil Weinberg (Advisor)
- Dr Claire Arthur
- Dr Jason Freeman
- Dr Ayanna Howard


*Abstract:*
This dissertation presents a method for non-anthropomorphic human-robot interaction using a newly developed concept entitled Emotional Musical Prosody (EMP). EMP consists of short expressive musical phrases capable of conveying emotions, which can be embedded in robots to accompany mechanical gestures. The main objective of EMP is to improve human engagement with, and trust in robots while avoiding the uncanny valley. We contend that music - one of the most emotionally meaningful human experiences - can serve as an effective medium to support human-robot engagement and trust. EMP allows for the development of personable, emotion-driven agents, capable of giving subtle cues to collaborators while presenting a sense of autonomy. We present four research areas aimed at developing and understanding the potential role of EMP in human-robot interaction. The first research area focuses on collecting and labeling a new EMP dataset from vocalists, and using this dataset to generate prosodic emotional phrases through deep learning methods. Through extensive listening tests, the collected dataset and generated phrases were validated with a high level of accuracy by a large subject pool. The second research effort focuses on understanding the effect of EMP in human-robot interaction with industrial and humanoid robots. Here, significant results were found for improved trust, perceived intelligence, and likeability of EMP enabled robotic arms, but not for humanoid robots. We also found significant results for improved trust in a social robot, as well as perceived intelligence, creativity and likeability in a robotic musician. The third and fourth research areas shift to broader use cases and potential methods to use EMP in HRI. The third research area explores the effect of robotic EMP on different personality types focusing on extraversion and neuroticism. For robots, personality traits offer a unique way to implement custom responses, individualized to human collaborators. We discovered that humans prefer robots with emotional responses based on high extraversion and low neuroticism, with some correlation between the humans collaborator’s own personality traits. The fourth and final research question focused on scaling up EMP to support interaction between groups of robots and humans. Here, we found that improvements in trust and likeability carried across from single robots to groups of industrial arms. Overall, the thesis suggests EMP is useful for improving trust and likeability for industrial, social and robot musicians but not in humanoid robots. The thesis bears future implications for HRI designers, showing the extensive potential of careful audio design, and the wide range of outcomes audio can have on HRI.







[Establishing  Human-Robot  Trust  through  Music-Driven  Robotic Emotion  Prosody  and  Gesture](https://arxiv.org/pdf/2001.05863.pdf)

28th IEEE International Conference on Robot & Human Interactive Communication 2019

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

[Finding Shimi's Voice: Fostering Human-Robot Communication With Music And a NVIDIA Jetson TX2](http://lac.linuxaudio.org/2019/doc/savery.pdf)

Linux Audio Conference 2019

R Savery, R Rose, G Weinberg

*Abstract:*
We present a novel robotic implementation of an embedded linux
system in Shimi, a musical robot companion. We discuss the challenges and benefits of this transition as well as a system and technical overview. We also present a unique approach to robotic gesture
generation and a new voice generation system designed for robot audio vocalization of any MIDI file. Our interactive system combines
NLP, audio capture and processing, and emotion and contour analysis from human speech input. Shimi ultimately acts as an exploration
into how a robot can use music as a driver for human engagement.
