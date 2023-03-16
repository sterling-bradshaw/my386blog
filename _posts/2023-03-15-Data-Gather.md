---
layout: post
title:  "Data Collection"
author: Sterling Bradshaw
description: A brief guide on how to gather data via APIs
image: /assets/images/markus-spiske-iar-afB0QQw-unsplash.jpg
---

## *Why use an API?*
I'll be completely honest. The first time I heard about APIs and how they are often used, I thought to myself, "Why not use Kaggle, webscraping, or any other method rather than sifting through hard-to-read JSON files?" It didn't make sense to me why we couldn't use simpler methods. And then I had a realization.

## *APIs are key (get it? like keys in a dictionary in python?) to answering real world questions*
In statistics classes at a university, the teaching and learning process often goes something like this: we learn a coding concept (ie. ggplot, vectorization, scraping tables from the web), either the professor or student finds a dataset that is suitable for the particular concept, the student applies the concept to the dataset, THEN finds which question to ask.

In the real world, this isn't the case. We can't use hindsight to base all of our developments moving forward. Otherwise we would never learn anything. A more realistic scenario would be to create a question and then find a dataset to put a hypothesis to the test. This is where APIs come in. Many companies allow data access to any user that jumps through the proper hoops. We will be exploring one particular (and might I add a very user-friendly) API today and how to extract the data from it.

Before starting, it is important to make sure you have the right packages installed and imported. In the example below, I import three python packages: requests (used to call data from the API), json (to help sift through the data call and make it python-ized), and numpy (used later for vector operations). Identify which packages are needed for your case and install and import them very first!

![](Import)



## *Which API should I choose?*
APIs have quite a range of barrier-to-entry. For example, the APIs offered by tech behemoths such as Twitter have an approval process for each level of access. While this may not seem worth it at first if you are just working on a school project, you may want to reconsider. APIs with lots of users and big companies to back them up are almost sure to have better documentation and forums available. I ran into this issue myself.

I searched and searched for a free and no barrier-to-entry API for NBA statistics, I found one called Free NBA. However, as I started using it, I discovered much of the example code was not up to date. There were practically no resources found to help with my specific problems in the documentation. I found another API that required more from me, and in return I found more helpful resources. It's a toss up, but if you are just getting into the API world, strongly consider prioritizing good documentation!

## *API-NBA*
I found a NBA API on rapidapi.com[] which I would highly recommend as a beginner. For each API, you can choose the programming language you are using to give you example code as shown in the picture:

![CodeExample](https://raw.githubusercontent.com/sterling-bradshaw/my386blog/main/assets/images/CodeExample.png)

This code can be easily copied and pasted into a Jupyter Notebook (or an IDE of your choosing) for simple 