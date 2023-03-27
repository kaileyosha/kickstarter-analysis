# Kickstarting with Excel

## Overview of Project
This project required an analysis of the success of kickstarter campaigns for plays based on two criteria, the launch date of the kickstarter and the goal each kickstarter set.

## Purpose
The goal was to better understand the relationships between time of year and campaign success, as well as how effective goal setting can bolster campaign success.

## Analysis and Challenges
The two deliverables required me to use the countifs and year function. The year function was intuitive enough for me to use to get the year from the conversion data. The countifs function is where I had the most difficulty. At first, I kept getting an error message telling me I had too many conditions for the statement. I went back and used the hint and watched the video to determine where I was going wrong, and I typed the code in exactly as I saw in the video but the same message still occurred. Eventually, I realized my issue with the code was that I had written countif instead of countifs. Once I fixed that it was rather straightforward. I was a little concerned as well when the "canceled" outcomes continuously showed up as zero, and I realized by checking the filters on the original worksheet that it was because there are no kickstarter campaign plays that were canceled, they're either successful, failures, or still live.

### Analysis of Outcomes Based on Launch Date Results
What are two conclusions you can draw about the Outcomes based on Launch Date? The first, most noticable conclusion I drew based on the line graph would be that the best month for kickstarter campaigns is the month of May. May had, by a substantial amount, the largest number of successful kickstarters. In contrast to that, I noticed campaigns that were launched in December had the lowest numbers of success. While more research would need to be done, I woud hypothesize that December's lowest success is because of the winter holidays. People spending more money on gifts, meals, et cetera in November-December means they have less surplus to spend on things they want. Thus, it would make sense to start a campaign in the summer, when people have had time to substantially recover their losses from the winter months. A third thing I noticed is that launch date has little to do with whether or not a campaign gets canceled, as that number remained relatively constant.

### Analysis of Outcomes Based on Goals Results

#### What can you conclude about the Outcomes based on Goals?
One can conclude that setting realistic goals is a critical factor of success for kickstarter campaigns. Any show that set a goal of greater than or equal to 50000 saw chances of success plummet. More research would need to be done on why exactly this is so critical, but some psychology lends to the idea that people enjoy gratification. If they give money to a campaign with such a high goal, they're taking a substantial risk that they will not get to see the subject of the campaign come to fruition. Those that are risk-averse would be less likely to donate to campaigns with high goals as a result.

## Results
### What are some limitations of this dataset?
The data set has a lot of information that isn't necessary to the analysis itself, which I think over-crowds and over-complicates things needlessly. I think it emphasized some variables and fleshed them out well, such as categories and the number of backers, but I think it lacked in other areas. For example, our client in this situation is a woman. If I were working on starting a kickstarter campaign, I would be curious how many of these campaigns started by women were successful. I would also want extra analysis of the shows determining if they went over budget in production, and by how much, so that I could really understand how much of my funding I could get from kickstarter and how much would need to come from alternate sources (such as getting local sponsors). How many of the items actually made it to production and, for plays specifically, how many made it to large stage productions? Starting foundationally with the bare-bones of a kickstarter campaign is important but there are other factors that would be highly relevant to the client and understanding what success on kickstarter actually means for her show.

### What are some other possible tables and/or graphs that we could create?
I would create a pie chart that for successful vs. failed plays based on their goals. A line chart is good for many options, but to emphasize the importance of effective goal setting we could use one of the mid-tier goal options and use the 50000 or more option to show the difference, as 50000 or more saw the most failed campaigns. I might also suggest using a histogram to visualize the number of contributors to campaigns based on the month, as that could give us a better idea of just how active people are during specific months.
