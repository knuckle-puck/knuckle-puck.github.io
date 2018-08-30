---
layout: article
title:  "Does Size Matter?"
author: "KnucklePuck"
excerpt: "An statistical introduction to the height and weight of NHL players."
categories: 
date: 2018-08-29
modified:
image:
  feature:
  teaser: Measure_300x200.jpg
  thumb:
---

## Introduction

If you've ever been fortunate enough to watch an NHL game from the lower bowl, perhaps even right up against the glass, you've noticed that NHL players are much bigger than they appear on TV. But its worth asking ourselves, has the league always been like this? And is measuring over 6 feet tall and weighing over 200 lbs an asset, or a necessity?

If you were to ask me, I'd predict that the smaller player is playing a bigger role in today's NHL than he did 10-15 years ago. Patrick Kane, Jonny Gaudreau, Mitch Marner, and Mats Zuccarello to name a few forwards, and Erik Karlsson, Torey Krug and Ryan Ellis on defence, are all putting up a lot of points. In this article we will test whether this phenomenon is supported by the data and whether the best players in the NHL today are smaller or bigger than the rest of the league.

## Average Height and Weight in the NHL since inception

The average height in the NHL was consistently trending upwards until around the year 2000. It has since plateaued around 73 inches (6'3"). 

The average weight in the NHL was also consistently trending upwards until a ceiling of 206.3 lbs was reached in the 2005-06 season. The average weight has come back down to around the league average that we saw in the early 1990s. 

![Height and Weight Trend](/images/2018-08-28-does-size-matter/HeightWeightTrend.png)<!-- -->

* Note the the scales on the y-axis of each graph. Differences are smaller than they appear. 

## Comparing the League to the 2017-18 Top 15 Point Scorers

The table below shows the height and weight for the top 15 players in the NHL for the 2017-18 season (ranked by Points Per Game). At first glance we are not seeing a distinct trend among the top 15 hockey players. The larger players, Alex Ovechkin (6'3", 235 lbs.) and Blake Wheeler (6'5", 225 lbs.), are cancelled out by the smaller players, Nikita Kucherov (5'11", 178 lbs.) and Brad Marchand (5'9", 181 lbs.).

The average height of the top 15 players is 73.27 inches and the median is 73 inches. This mirrors the league average of 73 inches. The average weight of the top 15 players is 204.2 lbs and the median is 202 lbs, slightly higher than the league average of 199.7 lbs. The top 15 point producers are more or less the average height and weight of the league. 

| First Name | Last Name | Points  | Points per Game | Height  | Weight  |
|:-----------|:---------:|--------:|:----------------|:-------:|--------:|
| Connor     | McDavid   | 108     | 1.317           | 73      | 192     |
| Nathan     | MacKinnon | 97      | 1.311           | 72      | 205     |
| Evgeni     | Malkin    | 98      | 1.256           | 75      | 195     |
| Brad       | Marchand  | 85      | 1.250           | 69      | 181     |
| Nikita     | Kucherov  | 100     | 1.250           | 71      | 178     |
| Claude     | Giroux    | 102     | 1.244           | 71      | 185     |
| Taylor     | Hall      | 93      | 1.224           | 73      | 205     |
| Blake      | Wheeler   | 91      | 1.123           | 77      | 225     |
| Phil       | Kessel    | 92      | 1.122           | 72      | 202     |
| Anze       | Kopitar   | 92      | 1.122           | 75      | 224     |
| Steven     | Stamkos   | 86      | 1.103           | 73      | 194     |
| Ryan       | Getzlaf   | 61      | 1.089           | 76      | 223     |
| Sidney     | Crosby    | 89      | 1.085           | 71      | 200     |
| Mark       | Stone     | 62      | 1.069           | 76      | 219     |
| Alex       | Ovechkin  | 87      | 1.061           | 75      | 235     |

## The Relationship between the Size and Production of All Skaters in 2017-2018

If the top 15 point producers are reflective of the league average weight and height, is there at least an observable correlation between the production and size when looking at the league as a whole? 

The graph below shows a dot for every single skater that had more than 20 games played in the 2017-18 season. We also plot (as the line in the graphs) the linear relationship between the two variables.

![Height and Weight Scatterplots](/images/2018-08-28-does-size-matter/HeightWeightScatter.png)<!-- -->

** Note the outlier that is Zdeno Chara

The lines in each graph show a small negative correlation between Height/Weight and Points, but if we account for the statistical "error" (the shaded portion of the lines) the relationship is less pronounced. We can acknowledge that the line does have a downward slope, but you must also consider the entire shaded area to account for statistical significance. There are areas at 65 inches and at 80 inches (in the shaded area) that are at nearly the same level of points. 

## Conclusion

The analysis above shows that there is not a significant relationship between the size of a hockey player and how many points they will score in a season. Interestingly, you could draw the conclusion that the highest scoring hockey players tend to be of average weight and height (6"1', 202 lbs). 









