---
title: "Project Rage DevBlog #3"
date: 2022-03-20T17:57:30-04:00
categories:
  - project rage
tags:
  - devblog
  - project rage
excerpt_separator: <!--more-->
---

Here is the breakdown of my work on Project Rage from 3/6/2022 to 3/20/2022.

## Sound Effects (5 hours)

I worked on 2 sound effects. The first one was the health refill effect corresponding to the sound that the health bar makes when the player revives after they lose a life. I first spend around one and a half hour listening to make different examples such as the [halo shield regen](https://www.youtube.com/watch?v=mTt2Rjpzpfc) and the [energy regen from metroid dread](https://youtu.be/7_YC7IW1zCU?t=2033). From both examples, I knew I needed a rise of some sort which I was able to quickly make. However, there were a lot of other layers of sound which made the regen examples sound great. In the next hour, based on the cyberpunk theme, I knew there needs to be some sort of machine like or very synthetic industrial sound, so I went onto freesound.org and found many great recordings of random blips and beeps. I included mechanical sounds that sounded like something winding down and gathering energy to tie it to the respawn flash release which was supposed to knockback all enemies and make a powerful pulse. I also wanted to hint at why the player was regening health so I took the sound of a office chair changing it's height and put it in my sound effect. It sounded like an injection. Here is the final result of the [health refill sound effect](https://studio.eecs.umich.edu/jira/secure/attachment/12084/HealthRefill.wav).

<img src="https://raw.githubusercontent.com/zwagaroo/zwagaroo.github.io/master/assets/images/ragedevblog3/healthrefill.png" alt="Health refill" >

The other sound effect I worked on was the respawn flash sound. For this I looked at references like the [super metroid power bomb](https://www.youtube.com/watch?t=382&v=8gtgUrUR57E&feature=youtu.be). For this I had a lot of trouble trying to figure out how flashes sound and it took quite a lot of experimentation for around 2 hours. In the end I put a low passed rise with a lot of noise for the flash. Additionally, I realized that since the enemies were knocked back by the flash, I wanted to hint about why. So I included electricity sounds at the end to make it sound like an electrical discharge. I found the sound of electrical discharge on freesound.org as well. After I turned in my work I realized that the flash may have ended too abruptly so I spent thirty minutes trying to fix the problem. I eventually settled on a lot of decay to smooth the release of the sound out. Here is the final result of the [respawn flash sound effect](https://studio.eecs.umich.edu/jira/secure/attachment/12096/Respawn.wav).

## Level 1 Downtown Music Polishing (4 hours)

After listening to the implmentation of the downtown level 1 music from an hour of experimenting and playtesting with the game, I realized that some parts of the melody didn't fit as well as I may liked, especially the breakdown portion. Additionally, some rythmns felt awkward and out of place in the music as well, especially in the breakdown where I had pulsing triplets at the end of each measure. I took an hour to figure out exactly what was wrong with the breakdown and took another hour to tune the rythms until they mixed nicely with the rest of the track. By doing so however, I also messed up a lot of the delay and reverb effects which made the texture interesting so I had to remake those as well. Then I took another hour on balancing the piece a bit better. One of the main things was that I noticed the bass was just too overwhelming in the breakdown. It was almost distracting from the gameplay. I fixed this in an hour by bringing up some of the background sounds and bringing down the drums and reequalized almost every track. This helped a lot to make the sound track blend more. Here is the final result of the [level 1 downtown music](https://studio.eecs.umich.edu/jira/secure/attachment/12097/Going%20Neon.mp3).

## Level 2 Downtown Music (3 hours)

I was also tasked with working on level 2 downtown music this week. However, I wasn't able to get much significant progress on this. I had a hard time trying to come up with "richer" but still cyberpunky sound for this wealthier part of the city. I talked with my team lead Morgan and we found a lot of different pieces to listen to as example such as this track [Final Frontier](https://www.youtube.com/watch?v=cbSsxJK0fNI), [Without A Sound by HOME](https://www.youtube.com/watch?v=Jp0mdYBkzKU), and various industrial mixes such as this one [here](https://www.youtube.com/watch?v=b9fUdJdlExU). I spent the majority of my time listening to these pieces but unfortunately I wasn't able to come up with any way to start in the end.

## WolverineSoft Studio Meetings and Playtest Sessions (5 hours)

I attended the studio meetings every sunday from 11 to 1 for the past two weeks where the audio team discussed current work and ways to improve. Currently for the next sprint I am assigned to work on more sound effects and various music for end screen and victory screens. I also attended Professor Yarger and Amber's playtest which helped me get a lot of insight into what needs work on the audio side of the project. 

## Time Breakdown

This week I spent a total of 17 hours working on the project. I took 5 hours to create two sound effects health refill and respawn flash. I took 4 hours to polish up level 1 downtown music. I took 3 hours to listen to and find examples of possible good level 2 downtown music. I also spent 5 hours in wolverinesoft studio meetings and playtesting sessions!

