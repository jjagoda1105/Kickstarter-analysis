# Kickstarting with Excel

## Overview and Purpose of Project

The kickstarter data provides us with historical campaign outcomes based on launch dates and fundraising amounts. Louise, a campaign manager, has come to us for help. She has already launched a fundraising play, and she wants to understand how her play did comparatively to other fundraisers in the same category. Our team will create images and data summaries to identify trends that will ultimately help Louis with her theater campaigning. 

This analysis was performed by focusing on the data within Louise’s category. The factors that play a role in campaign success include launch date and goal amount. 

### Analysis of Outcomes Based on Launch Date

To summarize and compare this data, I had to make a pivot table. The pivot table allowed me to quickly count the different type of outcomes based on the launch month. This will help Louis identify if her play occurred during a month when plays were successful.  With this pivot table, I created a line graph to visually understand what month had the highest volume of successful outcomes. See the image in the paragraph below.

#### Results and Conclusions Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/88689043/130372382-eed0967c-9ecb-40bb-854c-7aacf5b2b87f.png)

Louise launched her play in June, when there were 100 successful plays, with a 65% rate of success. As pictured in the graph, the most successful month to launch a play occurs in May with 111 successful plays and a 67% success rate. If Louise launched the play a month earlier, she would have had a better chance of having a successful play. After May, the line graph shows success trending downwards, meaning that there are typically less successful number of plays as the year goes on. The least successful month for plays occurs in December, so ideally Louise shouldn’t do her play in December, or for that matter, any time after May.

### Analysis of Outcomes Based on Goals

Another factor I looked at included the goal fundraising amount. I used a CountIF formula to count the outcomes (successful, failed, canceled, and live) based on their fundraising goal ranges. The countif formula helped to drill down on certain criteria that was relevant to comparing Louis’s play. I was able to see that the most successful number of plays had a fundraising goal between $1k and $4.99K. However, I can also see that this goal category had the most number of failed plays, so we need to look at the percentage success rate to truly understand what goal range leads to the most success. In order to do this, I took each outcome goal category, and divided that by the the total number of plays within that category. I then created a map to see if I could understand the relationship between the goal amount and success rate. See the image below.


#### Results and Conclusions Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/88689043/130372369-0023b89c-40b7-4fae-bf0c-1c41f039f135.png)

After creating the line graph, it is apparent that the most successful plays occur when the goal is under $1k. Louis’s goal was to fundraise $2,885k, so her play did not fall in the most successful fundraising goal range. If her goal was a smaller, potentially under $1k, it is more likely that her play would have been successful. For the most part, the goal amount of money raised has an indirect relationship with success. As the goal is higher, the percentage of successful plays becomes lower. It should be noted, this trend stops after the $30,000 and up range. Therefore, my suggestion for Louise, would be to stay under $1k for her goal. 

### Challenges 

I came across a challenge when trying to group the dates into months. The pivot table automatically grouped them into quarters. I was able to change the grouping by deleting the quarters and then I could see the months in each row. 

Another challenge occurred when I was trying to count the outcomes based on the dollar amount range. I didn’t realize that you have to put the less then or equal to in quotation. I fixed this by adding quotation marks to the formula.  

### Limitations

One of the limitations in this data would be to include more data for just the US. Our data was looking at all countries. To understand Louise’s play better, we would probably want to only look at the US because plays may not be popular all around the world. 

Another limitation of this data is that we didn’t take enough samples. 729 Plays is not very many plays when you take into consideration the entire population of fundraising plays. 

In addition, we didn’t look at enough factors to determine what else could have played a role on the different outcomes. Here are some other tables we could have made 
•	Number of backers vs outcome
•	Average pledged vs outcome
•	Outcomes by countries
•	Pledged amount vs success rate
