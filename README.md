# Kickstarting with Excel

## Overview of Project

### Purpose
     To research how different Kickstarter campaigns fare in relation to their launch dates and their funding goals.
     [Kickstarter Campaign data used for this project](docs/Kickstarter_Challenge_copy.zip.md)

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
     
     First I created a Pivot Table filtering the Parent Category of the campaigns and the Year the campaigns were launched. The table displayed total outcomes for each month from 2009-2017.
     [Theater Outcomes Based on Launch Date](docs/Theater_Outcomes_vs_Launch.png.md)  

### Analysis of Outcomes Based on Goals
     
     First I created a table with the goal amounts broken into $5,000 increments, and the outcomes separated into separate columns for individual count and percentage. Then I created a function to filter the outcomes based on each goal amount increment. After that, I calculated outcome percentages of each goal increment, which I then made into a Line Chart.
     [Outcomes Based on Goals](docs/Outcomes_vs_Goals.png.md)

### Challenges and Difficulties Encountered

     A challenge that I faced at first was how to group and ungroup the launch dates on the pivot table. But I was able to learn what to do with the Microsoft links included in the assignment. I also had to figure out how to remove the PivotChart titles from the chart itself before I could save the image.

     I also had a small challenge as I was trying to check my work with the COUNTIFS function. Using the PivotChart for Subcategory analysis that I created at an earlier time, I knew what my totals should have been. However, I was off. After a little review, I realized that I had the wrong equality symbol on my first line and that was the solution.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

     1) The best month to launch a successful Kickstarter campaign is May, because between 2009-2017 May has the highest number of successful campaigns.
     2) Launching a Kickstarter campaign around the holiday season (November-January) is not the best time, possible because consumers are spending more money during this time of year. The amount of Successful campaigns are lower during this time, however there is no apparent trend among the failed Campaign launches.

- What can you conclude about the Outcomes based on Goals?

     1) Goal amounts between $0-$15,000 and $35,000-$39,999 have a higher chance of being successful.

- What are some limitations of this dataset?

     -There is not a lot of data for plays with goal amounts over $15,000 compared to the increments underneath that amount.
     -There is not a high correlation between goal amounts and outcome due to the reason I mentioned above. So it is difficult to draw a conclusion.

- What are some other possible tables and/or graphs that we could create?

     -We could examine the lengths of successful campaigns.
     -We could examine if the amount of successful campaigns have increased or decreased over the years as a whole.
     -We could examine the average donation amount from each backer and possible determine incentives for higher donations.

