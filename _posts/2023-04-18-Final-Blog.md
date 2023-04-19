---
layout: post
title:  Is the "Three-Point Revolution" An Accurate NBA Story?
author: Sterling Bradshaw
description: Exploring the biggest conclusions from the NBA data project
image: /assets/images/Dunk.jpg
---

![Decades](https://raw.githubusercontent.com/sterling-bradshaw/my386blog/main/assets/images/decades.jpg)

## Introduction
The whole motivation behind this project was to fact check the announcers and analysts that cast the majority of today's NBA games. Almost all of the analysts (at least from what I have heard in my limited exposure) is that the NBA league is not the same as it used to be. Steph Curry transformed the way teams operate by becoming a lights-out shooter from beyond the arc. Teams often space the floor more to decongest the interior of the court next to the basket (see [this article](https://www.thehoopsgeek.com/history-three-pointer/) for the history of the three pointer).

![Steph](https://raw.githubusercontent.com/sterling-bradshaw/my386blog/main/assets/images/Steph.jpg)

We hear about how league-wide teams are taking more three pointers on average each game, but could that be attributed simply to the fact that teams have more possession than before on average? This increase in pace to allow more possessions definitely accounts for part of the increase, however, as we look at the ratio of three-point attempts to two-point attempts, that has also increased. Conclusion: the league has changed they way basketball is played. In other words, the ["three-point revolution"](https://www.nba.com/news/3-point-era-nba-75) has begun.



## Data Story
Starting with the explanation of how to use an API, we determined how beneficial an API can be in trying to find answers to real world questions in the [first part](https://sterling-bradshaw.github.io/my386blog/2023/03/15/Data-Gather.html) of this project. Then we explored different trends of interest in the gathered data in [this post](https://sterling-bradshaw.github.io/my386blog/2023/03/31/EDA.html) focused on EDA.

With the data cleaned and patterns displayed, I returned to my initial question: Are teams really scoring more points than before because of the utilization of the three-pointer?

As we look at the following visualization, it is important to keep in mind some key transitions that occurred in the league, namely the adoption of the three-point line in 1979 and Steph Curry's draft date in 2009.

<iframe
  src="{{site.url}}/{{site.baseurl}}/assets/images/Final.html"
  style="width:100%; height:500px;"
></iframe>

The conclusions we can pull from this graphic are quite interesting. From what we can tell, the analysts are at least somewhat correct. Just a few years after Steph Curry joined the league, we start to see a dramatic shift upward in average game scores across the league. The only 