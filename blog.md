---
layout: default
---

<link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">

<a href="./"><i class='fa fa-arrow-left'></i> Back</a>

# Blog

Below, you will find some random articles about different topics.

## Overview

- [Online Teaching](#Online-Teaching)

## Online-Teaching  

### Changelog

- Updated on 04/01/2021

Due to the ongoing COVID-19 situation, most universities (I guess) have essentially switched to a distance learning format. This has been a challenge for all of us, and especially for me it took some time to figure out the right setup. Particularly, (1) what type of lectures to provide (videos, live, or hybrid), (2) what equipment to use and (3) how to handle exercise-heavy courses (submission system questions, etc.). As I went through many changes to my initial setup from 2020, I decided to share the setup that I eventually converged to.

### Different lecture types, different requirements

I typically teach several course types, from standard lectures, to exercises and seminars. 

For **standard lectures**, the ultimate question is how to get quality content to students. Some people do *live* lectures, possibly with recording, others provide lecture videos, or anything hybrid in between. Lets say, I am not the biggest fan of live online lectures. Due to relatively little interaction with students in this format, you tend to go very fast through the material (especially with slides). Also, even if there are questions, there is little time to answer them with adequate depth. Hence, I decided to provide pre-recorded lecture videos. This is basically me explaining the material (slides, code, theory, etc.). Additionally, I then offer, on a regular basis, **live Q&A sessions** (about an 1h) where students can ask questions. As there is no pressure on my side to make progress regarding the material, there is plenty of room for good discussions.
As a side note, I do not see any point in including a video of myself for the pre-recorded lectures. To me, it seems incredibly boring to watch a guy for 1 1/2 hours staring at his iPAD.

Handling **exercise-heavy courses** is more tricky. First of all, you need to provide some type of feedback to students, either in the form of **example solutions**, or by **annotating submissions**. I typically try to provide both: For each exercise sheet I put online, I also provide a short solution video once the submission deadline has passed. Further, I try to annotate each exercise. Technically, the challenge is to make it easy for students to hand-in exercises (either single-person, or group) and to later provide annotated submissions back to them. I will discuss the technicalities later, but literally every system I tried early on during COVID-19 (Blackboard, GitHub classroom, etc.) had it's flaws, could not be customized to my needs easily and, most importantly, required **a lot of clicking around** in some web interface. 

### Equipment

In terms of **hardware**, I use:

- iMac / MacBook Air
- iPAD Pro (12.9) + Pencil
- [Lewitt LCT 440 PURE](https://www.lewitt-audio.com/microphones/lct-recording/lct-440-pure) (a condenser studio mic)
- [Pre­sonus Studio 26c](https://www.presonus.com/products/studio-26c) (audio interface)

In terms of **software**, I use:

- OBS Studio (on iMac)
- Goodnotes 5 (on iPAD)

### Producing lecture videos

First of all, it takes some time to produce lecture videos, typically much more time than to actually do a live lecture. The problem is that videos are less forgiving in terms of errors that you make. And yes, I do make errors quite often; most of the time I capture them later on during a live lecture and can correct them, but there is no going back when recording (unless you really wanna go down the rabbit hole of heavily using video editing software). Two things that I've learned: **(1) good preparation is key** and **(2) you need a way to easily and quickly pause recording**. 

My initial setup was to record everything on my iPAD Pro. I use Goodnotes for taking hand-written notes and also to import all my PDF slides, as I tend to annotate them as well during a lecture. Basically, this works fine, if you do not make mistakes, or have to think a little from time to time. The reason is that the Apple developers thought it's a good idea not to be able to simply pause a screen recording (aside from the stupidity of muting the mic by default). So, this is essentially a one way street once you started. You can obviously simply stop the recording, but then you end up with, say 15 pieces of video that need to be put together later on. Maybe some wise UI person will tell them that this is a really stupid design choice.

So, while I did like the idea of recording my stuff wherever I am, I switched to OBS studio for recording. Overall, it's the professional way to go anyway, but requires, in addition to your iPAD, access to an actual computer (an iMac in my case). Once the iPAD is connected to the iMac, it's straightforward to import the iPAD screen by first adding a `Scene` and then a `Video capture device`. The latter lets you select the iPAD. Sometimes not the full iPAD screen is visible then, but switching back and forth from high to low-resolution in OBS did the trick. Additionally, you can then add a `Window Capture` and also show your slides. OBS lets you switch seamlessly between the sources while you are recording and, most importantly, you can just pause whenever you want. 

As a side remark, recording on your iPAD only, can cause some funny things. First, the `Do not disturb` mode seems to not work in all cases. E.g., you record your iPAD screen and suddenly a Slack message pops up; if you do no want your students to see this, you have to cut it out. Second, they will see your local time, i.e., if you are recording at 11pm, this might reveal some unwanted details about your time management. I do not care, but some people definitely will. Last but not least, if you are recording in your office, there will almost certainly be someone who comes in while you take a 1 1/2 hour video in one piece. If you are unlucky, you will hear the *knocking on the door* in the video, or even some initial conversation before they realize you are recording. Having said that, there is a reason why a recording studio has strict rules. My advice: put up a sign on your door!






### Handling exercise-heavy courses


