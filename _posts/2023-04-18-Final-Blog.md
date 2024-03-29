---
layout: post
title:  Is the "Three-Point Revolution" An Accurate NBA Story?
author: Sterling Bradshaw
description: Exploring the biggest conclusions from the NBA data project
image: /assets/images/Dunk.jpg
---

## Introduction
The whole motivation behind this project was to fact check the announcers and analysts that cast the majority of today's NBA games. Almost all of the analysts (at least from what I have heard in my limited exposure) is that the NBA league is not the same as it used to be. Steph Curry transformed the way teams operate by becoming a lights-out shooter from beyond the arc. Teams often space the floor more to decongest the interior of the court next to the basket (see [this article](https://www.thehoopsgeek.com/history-three-pointer/) for the history of the three pointer).

![Steph](https://raw.githubusercontent.com/sterling-bradshaw/my386blog/main/assets/images/Steph.jpg)

We hear about how league-wide teams are taking more three pointers on average each game, but could that be attributed simply to the fact that teams have more possession than before on average? This increase in pace to allow more possessions definitely accounts for part of the increase, however, as we look at the ratio of three-point attempts to two-point attempts, that has also increased. Conclusion: the league has changed they way basketball is played. In other words, the ["three-point revolution"](https://www.nba.com/news/3-point-era-nba-75) has begun!



## Data Story
Starting with the explanation of how to use an API, we determined how beneficial an API can be in trying to find answers to real world questions in the [first part](https://sterling-bradshaw.github.io/my386blog/2023/03/15/Data-Gather.html) of this project. Then we explored different trends of interest in the gathered data in [this post](https://sterling-bradshaw.github.io/my386blog/2023/03/31/EDA.html) focused on EDA.

With the data cleaned and patterns displayed, I returned to my initial question: Are teams really scoring more points than before because of the utilization of the three-pointer?

As we look at the following visualization, it is important to keep in mind some key transitions that occurred in the league, namely the adoption of the three-point line in 1979 and Steph Curry's draft date in 2009.

<iframe
  src="{{site.url}}/{{site.baseurl}}/assets/images/Final.html"
  style="width:100%; height:500px;"
></iframe>

The conclusions we can pull from this graphic are quite interesting. From what we can tell, the analysts are at least somewhat correct. Just a few years after Steph Curry joined the league, we start to see a dramatic shift upward in average game scores across the league. The only caviat to the sports analysts' claims is that this phenomenon of scoring such high scoring games is new. One common quip amongst analysts is that the level of scoring isn't like it used to be in the 80s. Taking averages across the league, we see that league scoring is actually at the same level as the 80s.

The other piece that might play a factor in the steady decrease of average scoring was the introduction of the three point line in 1979. Without a three point line, there was no incentive to gain muscle memory for outside shooting. Closer to basket = easier points = win more games. It was that simple. 

My guess is that for a few years, teams stuck to their old ways of trying to shoot more shots closer to the basket. However, once teams realized the three point shot could be a viable strategy, more threes were taken... except no one was good at shooting them quite yet. The decrease from 1984-1998 most likely display the growing pains the NBA had to go through to learn how to successfully implement more three point attempts into each game strategy.

## Final Thoughts
Whether it be new rule changes, new players with groundbreaking game strategies, or some other factor, we can see scoring averages across the league goes through phases. It would take some extra digging to find out exactly what has caused these big shifts in scoring, but we know one thing for sure. The NBA is dynamic!

You can find all the code used and the dataframe for this project here on my [Github Repo](https://github.com/sterling-bradshaw/386Project)