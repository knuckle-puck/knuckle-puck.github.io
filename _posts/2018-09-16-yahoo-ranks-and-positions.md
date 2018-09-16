---
layout: article
title: "Yahoo ranks and positions for 2018-19"
author: "KnucklePuck"
excerpt: "The ranks provided by Yahoo fantasy hockey converted into an easy-to-use format."
categories: 
date: 2018-09-16
modified:
comments: true
image:
  feature:
  teaser: lightbulbs_300x200.png
  thumb:
---

## Introduction

With the fantasy hockey season upon us it is time to review the top 250 players. One of the more reliable and widely used fantasy hockey websites is Yahoo.com. Unfortunately, Yahoo's rankings are not always provided in the easiest to use format. To make the rankings easier to use and analyze, we've written a script that converts this top-250 list into Excel.

The Excel file and the code that we used to build the Excel file are available for free at our [GitHub repository](https://github.com/knuckle-puck/hockey-data).

The Excel file contains the Yahoo Rank (compiled from a number of their own experts), Player Name, Player Position (according to Yahoo eligibility), the Player's Team, and whether the player is currently a pending UFA/RFA at the end of this coming season.

## Position Summary

We have created a few graphs that show some interesting statistics about the 250 players that were chosen for this list. There are 156 forwards, 62 defensemen, and 32 goaltenders that made the cut. The 156 forwards consist of a larger portion of centers compared to left-wingers and right-wingers. Interestingly, there is only one single player with triple eligibility to start the season (Tomas Hertl).

![Position Summary](/images/2018-09-16-web-scraping-for-yahoo-rank-and-position/PlayersByPosition.png)<!-- -->

## Team Summary

There are a few minor surprises when you take a look at the teams with the most players in the 250 according to Yahoo fantasy rankings. Interesting to note that the lowest ranked playoff team is New Jersey; but this still feels reasonable given that the majority of their production came from one player, Taylor Hall. We also are noticing that there are some teams at the bottom of the list who are in the conversation for playoff contention (Edmonton, New York Rangers, Washington, and Buffalo among others).

![Team Summary](/images/2018-09-16-web-scraping-for-yahoo-rank-and-position/PlayersByTeam.png)<!-- -->






