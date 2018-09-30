---
layout: blog
title: Bot fight regenesis
date: 2018-04-21 22:00:55
tags:
- bot-fight
---
It's late and I'll probably run out of steam before I write this all up but I want to do a little description of a feature I'd like to add to this site. 

Bot Fight will be a bunch of code that simulates an encounter between bots (algorithms) in an environment (area/grid at first) to see who comes out on top. 

The bots will have properties, strategies, and other capabilities which will influence the outcome. Bot fights will be run on a schedule and the results posted on the site. Ideally, visitors to the site would be able to interact with the bots by helping them (providing or boosting capabilities) or  suggesting changes to strategies.

Bot fights will be essentially a coin flip at first but will mature over time as more code is added.

Program flow:

- load in bot defs
- load in environment
- load in visitor supplied modifications and apply them
- place bots in environment
- BOT FIGHT!
- record results
- repeat

I don't have time for this but I can spend a few minutes at the end of each day on it, I guess (after work, before dinner and getting the boy from daycare).

Next: make github repo