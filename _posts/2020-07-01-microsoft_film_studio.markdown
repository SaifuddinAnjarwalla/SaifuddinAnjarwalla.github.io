---
layout: post
title:      "Microsoft Film Studio"
date:       2020-07-01 15:25:10 +0000
permalink:  microsoft_film_studio
---


## Background

Following from the success of various tech business in the fuilm space Microsoft has decided that they are going to create a new Film studio and enter into this new market segment.

In typical Microsoft fashion they want to enter the industry in the smartest way possible, have a clear vision of what they want to achieve and have data driven results to support all their decisions.

As a result they have hired me as primary data scientist to help them better understand the industry itself and gain more insights into how they can make their studio as successfull as possible.

## Porject Outline 
### Clients Aims
Microsoft is a profit making company therefore they aim is to generate as much profit as possible. However when entering this new venture there are a few things for them to consider:
1. They are uncertain how successful they can make this studio be. They have experience in creating software not in creating movies therefore they do not want to take exuberantly high risks and thus do not have a massive budget for this project; therefore
2. Their aim will be to generate the highest Return On Investment (ROI) possible i.e the biggest bang for their buck!

#### What does this mean for us?
We will need to find out what affects Microsofts ROI the most what reasonable steps they can take in order to have the highest chance of increasing their ROI and thus making this studio a success.

## What variables affect ROI?
this list can be infinite however want to narrow it down to ones we can:
1. Get reliable data on to perfom an anlysis;
2. Affect ROI the most; and
3. Have reasonable and actionable responces for Microsoft to implement

After filtering down using this criteria we are left with a list of 5 variables.
1. Film Budget
2. Film release day 
3. Film release month
4. Film genre 
5. World GDP during the year of the film release

## Data anysis 
You might ask what effects do all these variables have on ROI?
Lets find out

### The effect of Film Budget on ROI

The data points to the fact that as the film budget increases the ROI tends to decrease. The highest ROI’s are seen between $0 and $50 million.

*Recommendation 1: Do not film movies which require very large budgets 
*

### The effect of the month when a film if released on ROI

We found that there are clearly months that do better than others. With the basic level of analysis done in this assignement we found that the months of April, January and July generate the highest ROI. However, it is not clear why this is the case. One reason coule be becuase they are all Holiday months April being Easter, January being the Christmas and new year break and July being Summer.

*Recommendation 2: Release movies in the months on January April or July
*

### The effect of the day when a film if released, on ROI

It is very clear from the data that movies released on thursdays tend to have the highest ROI's.

*Recommendation 3: Release movies on Thursdays 
*

### The effect of the world average GDP on ROI

We used data on world average GDP growth rates from the world bank. we used data on movies and GDP growth rates from 1980 to 2014. There is a clear positive trend between production budget and world GDP growth. However, there is a less significant negative trend between world GDP and ROI. This may be circular correlation of high GDP levels inducing higher movie budgets resulting in lower ROI’s

*Recommendation 4: Do not be tempted to raise budgets in booming economic periods
*

### The effect of movie genre on ROI

We found that out of the 13 genres tested some clearly performed better than other. We found that horro movies tended to have the highest average ROI's while Reality TV shows tended to have the lowest ROI's.

*Recommendation 5: Stay away from reality TV and news productions and produce Horror and Mystery films 



I found the process of this project fun. It was nice to see how far I have come since I started learning about data science. It also however made me realise how much more there is to learn and how easy it is to fall into the trap of beliving that the correlation you see between variables in your results are a result of causation. I look forward to carrying on learning more to improve my analysis.









