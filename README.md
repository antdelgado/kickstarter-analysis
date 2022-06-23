# Kickstarting with Excel
## Overview of Project
Since its founding, Kickstarter has had over 500 thousand projects launched on its website. Out of those, less than 40% meet their funding goal. Given the vast number of projects and data available about these projects, it makes sense to use that data to extrapolate ways to make our project more likely to meet its goal.
### Purpose
We will be looking at projects based on their durations, categories, and other criterion to find the most likely path to a successful campaign.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Dates
Given the over 4 thousand Kickstarter projects in our data pool, I had to do some sifting to find any correlation that could lead to success. My first attempt was finding a relationship between the month the project was announced and how much of the goal was reached. I created a PivotChart that displayed the month (translated from Unix) on the x-axis and the percentage of the goal the projects had reached. This data can be used reliably since theater projects make up a large plurality of the Kickstarter campaigns (approximately 33%). 
![A line graph showing the status of Kickstarter projects based on the month they started](https://raw.githubusercontent.com/antdelgado/kickstarter-analysis/cebac0bf50c1716475ef86527358521d302b7d61/Theater%20Outcomes%20vs%20Launch.png)
The strongest month to start a theater campaign is May (with 111 successful campaigns) followed by June (100 campaigns). On the contrast, the weakest months are November and December, both with only 54 and 37 successful campaigns correspondingly. It should be noted that October does have the greatest number of failed campaigns at 50.
To put it in more general terms, the warmer months of May through July are more likely to spur successful campaigns than the colder months of October through December. One potential theory is how people spend their times during those months. Summer is usually the time that families are out and there’s a high chance those families are looking for a new excuse to go on about town. This is in opposition to winter when families (regardless of where they go for the holidays) are more likely to stay indoors rather than explore around town.
### Analysis of Outcomes Based on Goals
The next criteria I looked at was the goal of the campaigns. For this, I made a new chart separating all of the campaigns by their goals and their outcomes. As a note, I am maintaining the first filter and restricting the data to only theater projects. To make the graph digestible, I separated the goals into buckets of roughly 5 thousand dollars except for the first two buckets – the first bucket is only to 1 thousand since those were the most plentiful and the second bucket is only 4 thousand so the rest of them end at even units of 5 thousand.
![A line graph showing the status of Kickstarter projects based on their funding goal](https://user-images.githubusercontent.com/105655045/175187218-f52a08c0-9843-4556-ac3c-85f45907de9a.png)
The best campaigns are all below 5 thousand dollars; approximately 67 percent of all the projects whose goals were under that threshold met their goal. There is also another spike in successes between 35 thousand and 45 thousand dollars. However, there were very few campaigns in that range (a whopping 9 campaigns). Therefore, this range isn’t reliable enough to validate such a high goal.
### Challenged and Difficulties Encountered
There was a vastness to the data that made it tempting to nitpick. As I made more charts, I kept on theorizing new correlations to find. There was almost a surplus of variables that it made it incredibly difficult to not try and find more correlations. Even when I had found a variable I wanted to isolate, it was difficult to not succumb to confirmation bias and cherry pick the data that fit my own personal beliefs of how data should look.
On top of that, the general overflow of information is difficult to decipher if you’re not careful. Let’s take the above graph. One could assume that it was the percentage of projects that had met their goals. However, one could equally assume that it is the average percent of goals met (i.e., projects with goals less than 5 thousand dollars would only achieve approximately 70% of their goal on average).

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
- What can you conclude about the Outcomes based on Goals?
- What are some limitations of this dataset?
- What are some other possible tables and/or graphs that we could create?
