# Ideal Launch Dates and Goals for Kickstarter Plays

## Overview of Project
    Louise enjoys Theater and in particular plays.  After having been inspired by the Edinburgh Festival plays she has launched a kickstarter campaign for a play named Fever. The Fever campaign has done well in a short period of time.  Louise would like to know how other kickstarter campaigns for plays are doing.  
    
    In particular Louise would like to see how other plays have fared with selected launch dates and campaign goals.  Is there some goals that are just too much? Or are there times of the year that a campaign is more likely to succeed?  By using the Kickstarter dataset these questions are answered for Louise.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
May was chosen as a launch date for 111 campaigns with a 67% success rate making it the most popular and succesful launch month.  May is closely followed by June and July, however, most times of the year are at least around a 60% success rate excluding December.  December is a poor launch choice likley due to the holidays.  

![alt text](http://url/to/img.png)

### Analysis of Outcomes Based on Goals
The smaller the goal the more likely the campaign will succeed.  Campaigns keeping their goals under 5,000 had a success rate of around 75%.  While campaigns with goals between 5,000 and 15,000 had a 55% success rate.  Higher goals that 15,000 resulted in 50% failure rates or higher.

### Challenges and Difficulties Encountered
Using inequalities in the countif statement required a double quote due to the equal sign.  Also, the exercise actually skipped 50,000 in the table which I think is an error in the material.  To explain further the goal range last two rows was: 45000 to 49999 and Greater than 50000.  This actually skips 50000, so the table should read 45000 to 50000 and Greater than 50000.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?  The most popular and succesful launch month is May, and the worst launch month is December.

- What can you conclude about the Outcomes based on Goals? The lower the campaign goal the higher the success rate.  At a goal of 15,000 the percentage failing is the same as succeeding, but as the goal increase higher than 15,000 more kickstars are failing than succeeding.

- What are some limitations of this dataset? This dataset is a mix of countries with US and GB being the substantial makeup.  There are many points that are high goals creating statistical outliers.

- What are some other possible tables and/or graphs that we could create?  Statistical tables that include the mean, median, standard deviation, upper quartile, lower quartile, and IQR would give insights into the goal tendencies.  A box and whisker plot reveals the outlier data points with high goals.
