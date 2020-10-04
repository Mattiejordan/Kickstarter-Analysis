# Kickstarter-Analysis
## Performing analysis on Kickstarter data to uncover trends
### Louise would like to start a crowdfunding campaign for her play, *Fever*. The budget for her project is $10,000. Through my analysis of the following kickstarter campaigns I can provide Louise with specific factors for success for her play. 
_ _ For Louise' *Fever*, she'll need a strategy other than More Cowbell. _ _
##### The expansive Kickstarter data covers several criteria including monetary goals and funding support details across multiple categories, countries, and timeframes. 
(https://github.com/Mattiejordan/Kickstarter-Analysis/blob/main/Parent%20Category%20Outcomes%20Chart.png)

![Parent_Category_Outcomes_Chart.png]


To assist Louise I focused on criteria similar to her goals for her play, *Fever*. Categories outside of theater plays including film, photography, music etc are filtered out and disregarded. A few factors for success are associated with the time the campaign is created, and the initial monetary goals set. The data presenting time was compiled in unix timestamp which I made a conversion to standard time/date format.

### Outcomes Based on Launch Date Success

The greatest success of theater kickstarters can be seen in the summer months, specifically the month of May. Be it the warm summer days, end of spring semester, loosening of pocketbooks etc. there is something statistically relevant affiliated with a spike in theater support. Through the fall and winter this support is seen to decline. **I suggest Louise consider launching her campaign during the month of May to increase her chances of success.** Another note with this display of data is that the rate of failure is relatively consistent throughout the year. From this point we can lean towards correlation with launch date for success, but other factors are involved for causation of success. More data must be collected for factors that promote successful campaigns. 

(https://github.com/Mattiejordan/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

![Outcomes Based on Date] (Resources/Theater_Outcomes_vs_Launch.png)

### Outcomes Based on Goals

Louise has her goal set at $10,000 for her play, *Fever*. By looking through comparable Kickstarter data, monetary goals can be distinguished by percentage success rates. By taking a look at goals in increments we can stepwise glean a pattern from the rates of success or failures at each additional goal increase. We will focus on the trend seen in goals of less than $15,000 to be proportionate to *Fever*. In this comparison we see success rates are greatest at the lowest goal amount then steadily decrease. Accordingly the inverse is seen for failure rates increasing as the goal increases. The goal range beyound $15,000 to $30,000 is quite dismal with rates of failures exceeding successes. If Louise, however, decides to quadruple her *Fever* budget and go full broadway there is an increase in potential success. **At her current $10,000 goal budget there is the timid 54% success rate, but at a $40,000 goal she could have a 67% rate of success! Break a leg Louise!**


(https://github.com/Mattiejordan/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png)

![Resources/Outcomes_vs_Goals.png]



