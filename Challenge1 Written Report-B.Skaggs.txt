# Project Overview

Purpose of this analysis is to help Louise with setting up a crowdfunding campaign to help fund her play, Fever. With an estimated budget of $12,000 this analysis is to help consider different factors that go into having a successful campaign.


#Analysis and Challenges 

First, I started by reviewing the data that was provided. This helped me get an idea of what I was working with. Next, I wanted to filter the data to make it as readable as possible. To start with, there are a few items that I will focus on, Goal, Pledged, Outcomes, Categories and Launch Dates. Louise is estimating her play will cost $12,000. To ensure I have more information I created three new columns percentage funded, avg donation and subcategory. 
*I found freezing panes on the top row will allow you to view data easily when working with multiple columns. *


## Analysis for Parent Category Outcomes
For our categories I separated this into Parent and Subcategories so we can get a better view of what is successful. Louise is interested in Great Britain’s market. We can see that out of 604 parent campaigns in Great Britain, theatre is the most successful. Theater is also the most successful in the United States with 525 campaigns. 

## Analysis for Theater Outcomes by Launch Date
Let’s view launch dates to determine if there is a certain month that is best to have a campaign. The data provided covers 2009-2017. During this timeframe we can clearly see that May and June are the best times to have a campaign. While May is one of the best times to have a successful campaign it is also the month of most failed campaigns. 

###Challenges
The Theater Outcomes pivot table ask that we only show months under categories. While creating this table I noticed that by selecting the date created conversion it filters into months, years, and quarters. I’m still learning pivot tables and trying to get this to work for me was trial and error. Once I was able to have my other fields correct, I could go in and work on the Axis section to ensure it showed months only. 


# Results

 ### What are two conclusions you can draw about the Theater Outcomes by Launch Date?
      1. We can see that May and June appear to be the best months overall to have a successful campaign. 
          Both months have the highest numbers compared to the rest of the year. 
2.  While May is a good month its also the highest when it comes to failed campaigns. 

### What can you conclude about the Outcomes based on Goals?
Plays that have a goal of less than 4999 are going to be more successful overall. As stated above Louise has a goal of 12000 and reviewing the data, we have it’s clear that out of 23 projects within the 10000-14999 goal range only 10 were successful. She will be better off lowering her goal closer to 5000.

### What are some limitations or recommendations of this dataset?
If we were given a bit more information, we could have been able to break down what Louise was looking for even more. There is a small overview of the plays, however, breaking down those plays into genre would have been helpful. Also, we have backers but what about the number of people that viewed these plays. We could easily create another Pivot Table to view this information and help Louise determine in her play would be a good fit. 

