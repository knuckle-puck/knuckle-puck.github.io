---
layout: article
title: "The Increase in Scoring in the 2017-18 Season"
author: "KnucklePuck"
excerpt: "How much did scoring increase in the 2017-18 season and what was the cause?"
categories: 
date: 2018-10-01
modified:
comments: true
image:
  feature:
  teaser: Seats_300x200.jpg
  thumb:
---

## Introduction

Over the past few seasons NHL ownership has made an effort to increase goal scoring. Goalie equipment has changed, referees are calling penalties sooner, and players fly through the center of the ice with their head down. Have these strategies been effective in increasing the average goals scored per game? Are we seeing a decrease in goalie save percentage? Do we see more powerplay goals as a result of strict referees? This article will explore the recent upswing in goals scored in the NHL and will identify hypotheses for what caused in the increase.

## Historical Summary of Goals

The graph below shows the historical trend of the average goals per game in the NHL. The most relevant observation for this article is that yes, the average goals per game increased in 2017-18 when compared to the previous year. However, we are not seeing a very large increase and the increase is nowhere near the average goals per game from the 1980s.

![Historical summary of goals](/images/2018-10-01-increase-in-scoring/HistoricalGoals.png)<!-- -->

## Probability Distribution of Goals - All Situations

The graph below shows us the distribution of goals in the two most recent NHL seasons, 2016-17 and 2017-18 (for those with a statistics background, these are the probability density functions for each year). The graph is showing us the amount of players in the NHL at each amount of goals scored. For example, if you are an NHL player, the probability that you would score exactly 10 goals is about 3.8% in the 2016-17 seasons and about 4% in the 2017-18 season. 

With this graph we can some differences in the goals scored between the two seasons. There were fewer skaters that finished the season with less than 6 goals, or beweteen 16 and 22 goals. Based on this graph we can hypothesize that, on average, skaters were increasing their goals totals last year. One possible scenario is that the group that would have been in the range 0 - 6 goals have moved into a range of greater than 6 goals, and those skaters that were flirting with 20 goals have now crossed that plateau. 

![Distribution of goals in all situations](/images/2018-10-01-increase-in-scoring/GoalDensity_AllSituations.png)<!-- -->

## Goals - Split by even strength and powerplay

As we dive deeper into uncovering where these extra goals are coming from we will look at similar graphs for both even strength and powerplay situations. The two graphs below tell us one important thing: the overall increase in goals is from a combination of both powerplay and even strength goals. This helps us eliminate the possibility that maybe referees are calling more penalties which could lead to an increase in powerplay opportunities and powerplay goals. More likely scenarios are that either goalies were reduced in their save percentage (i.e. by a change to their equipment) and/or skaters are increasing their shot totals or shooting percentage (i.e. more talented skaters). 

<figure class="half">
	<a href="Distribution of goals even strength"><img src="/images/2018-10-01-increase-in-scoring/GoalDensity_EvenStrength.png"></a>
	<a href="Distribution of goals on the powerplay"><img src="/images/2018-10-01-increase-in-scoring/GoalDensity_PowerPlay.png"></a>
	<figcaption>Probability distribution of goals.</figcaption>
</figure>

## Shots Taken and Shooting Percentage

The graph below on the left shows us the distribution of shots taken by skaters who played at least 20 games in each of the past two seasons. We can see that there were fewer skaters that took less than 175 shots and more skaters that took more than 175 shots. The graph below on the right shows us the distribution of shooting percentage for the same population of NHL skaters. By definition an increase in goals would be caused by either an increase in shots, an increase in percentage, or both. We see that there is an increase in shots and a decrease in the shooting percentage. 

<figure class="half">
	<a href="Distribution of shots"><img src="/images/2018-10-01-increase-in-scoring/Shots_AllSituations.png"></a>
	<a href="Distribution of shooting percentage"><img src="/images/2018-10-01-increase-in-scoring/ShootingPercentage_AllSituations.png"></a>
	<figcaption>Probability distribution of shots and shooting percentage.</figcaption>
</figure>

## Conclusion

In the introduction we noted that the NHL has attempted to steer the league towards higher goal totals by changing goalie equipment and having referees call penalties faster. If the goalie equipment were having a significant impact then we probably would have seen an increase in player shooting percentage. It's likely that this has had a minimal impact, if any. It's difficult to determine whether the change in referee behaviour had a significant impact. On the one hand we are not seeing a drastic increase in powerplay goals, but if players in the defensive zone are not playing as physical it could be leading to more shot opportunities and goals. 

There are countless factors that impact the score of a hockey game. All stratgies implemented by the NHL will have some kind of impact on the average goals that are scored and it is difficult to quantify the exact impact. The analysis becomes more difficult when you consider than the level of talent in the NHL appears to be continuously increasing, and the increase in scoring could be simply due to players become bigger, faster, and stronger.




