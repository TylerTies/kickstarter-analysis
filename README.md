# Kickstarting with Excel

## Overview of Project

### The purpose of this project is to explore kickstarter data and determine what factors might increase the chance of a successful campaign.  The analysis looks specifically at the theater category.  By looking at launch dates and funding goals of previous kickstarter campaigns we will be able to provide recommendations for Louise to proceed.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Launch Date](/Resources/Theater_Outcomes_vs_Launch.png)

Launch data was investigated first to determine what impact timing had on the success of a campaign.  The first chart shows the theater outcomes by the month launched. May has the largest number of successful campaigns but also the largest number of failed campaigns. Successful outcomes continue to trend downwards the remainder of the year.  This shows that there is more competition in early summer for funding but there are also more donations resulting in a higher percentage of successful campaigns.  One strategy would be to try to launch at the same time and take advantage of the increased funding available.  Another strategy would be to wait until after the busy months to have less competition.  However, there may also be less backers available.

### Analysis of Outcomes Based on Goals

![Goals](/Resources/Outcomes_vs_Goals.png)

Goal data was investigated next to determine how sizing of goals impacted success. This chart shows the percentages of successful, failed, and canceled campaigns.  There were no canceled campaigns in the plays subcategory.  This data shows that projects with smaller funding goals have a high rate of success with decreasing success rates up to $25,000.  The $35k to $45k range sees a higher success rate again before dropping off to almost no chance after $45k.  The data would suggest that keeping plays on a tight budget would increase the likelihood of success.  Another option would be to clearly define a large production and keep it within the $35 to $45k range.

### Challenges and Difficulties Encountered

I didn't run into any difficulties in the dataset but did check to make sure counts were matching as I filtered the dataset for portions of the analysis.  I wanted to make sure what I was filtering in pivots matched the original dataset.  I also did a sanity check on the charts to make sure there weren't any glaring errors.  Minor misspellings in the categories used as filters could lead to incomplete data.  There didn't appear to be any issues with the data.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?  The data would suggest that May is an ideal time to launch a theater campaign.  There appears to be a lot of buzz around the theater funding and riding that wave could prove beneficial.  The data would also suggest that seeking funding is very difficult during the winter months with December having the worst chance of success.  Going with the crowd appears to be the most beneficial.

- What can you conclude about the Outcomes based on Goals?  Funding goals seem vital to a successful campaign.  A small funding goal under $15k is the best bet.  More established players may be able to target the $35k to $45k range with larger productions once they are well known.  The recommendation for most would be to stay under $15k.

- What are some limitations of this dataset?  The dataset is limited by a number of factors.  There can be multiple economic factors that could impact the data.  There might be regional struggles in the economy that would cut into disposable incomes.  This data is unknown and could have a major impact on funding trends.  Also unknown is the success of individual plays.  Buzz around one big play could increase funding opportunities for others as people get more interested in the theater scene.

- What are some other possible tables and/or graphs that we could create?  It would be interesting to investigate the successful campaigns and determine whether they were mostly successful through smaller donations or if it was more often that a few larger donations put them over the finish line.  This would help inform how to successfully market a kickstarter campaign.  I'd also like to look at the individual years and see if there are any trends.  It would also help rule out any big years or anomolies in the data.
