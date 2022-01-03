# Kickstarting with Excel

## Overview of Project
    Louises play, Fever came close to its fundraising goal in a short amount of time. I want to give Louise more insight into theater fundraising campaigns, by analyzing the data collected for many different theather campaigns across the world. Using the kickstarter data, I can show Louise how different campaigns faired in relation to their launch dates and their funding goals.
### Purpose
    I want to show Louise how different campaigns faired in relation to their launch date and their funding goals. This can help Louise have more insight for her own play Fever, or for any future campaigns. 
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
    First to compare the outcomes vs the launch date, I needed to create a box plot with the date created data set and the outcomes data set. ADD WORKSHEET?? For this box plot, I put the year created in the x axis and then the outcomes on the y axis. The variable I am using is the count of the outcomes, so I can see the number of successful/failed/canceled campaigns at different points in time.
    Another important part of this box plot, was to add filters, for year and parent category. The data set includes campaigns for all types of art productions (television, film etc.), but I am only interested in the theater sub category.
    From there I could create a box chart, in the form of a line graph. This is to help visualize the trends between the outcome of a campaign compared to when the campaign was launched. Here is the chart I created  ![This is an image](/resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
    Next, I want to compare the outcomes of the campaigns vs the goal of the campaign. To do this, I first needed to use COUNTIFS function to filter the data I was looking at. ADD WORkSHEET?? I wanted to compare outcomes relative to different ranges of goals. I created 12 different ranges of goals, starting at less than $1000, all the way to greater than $50,000. Then I was able to use the COUNTIFS functions to get the number of successful, failed and canceled campaigns, in all the different goal ranges. Then I created a percentage of each outcome category by diving the numbers in each goal range by the total number of projects in each goal range. 
    Using this table, I could create a line chart with the goal ranges as our x-axis and our percentage outcomes for the y-axis. At this point, there was a small challenge, as I was only wanting to see the visual of the last three columns in our table (percentages), not the first three. To do this, I had to create a chart using the whole table and then go into 'select data' to filter out the sets of data I didn't want represented on the graph. Here is the chart we created from this analysis ![This is an image](/resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
    The first challenge occured in the launch date analysis. I needed to show a timeline by month, instead of the year. Showing the year that the campaign was created is not as useful in the analysis, so I had to filter the row label to months, to show the trends across a one year cycle. This helps give Louise more insight into the best timing of when to launch a campaign.

    The second small challenge was during the goal based analysis. I only needed to see the visual of the last three columns in the table (percentages), not the first three. To do this, I had to create a chart using the whole table and then go into 'select data' to filter out the sets of data I didn't want represented on the graph.

## Results

### Conclusions for Outcomes based on Launch Date 
    My first conclusion is that you would have the best chance of having a successful campaign if you launched your campaign between the months of May and June. As seen on the chart, ![This is an image](/resources/Theater_Outcomes_vs_Launch.png) there is a sharp increase in successful campaigns during these months.
    My second conclusion is that at the end of the year, there is a very equal chance of having a successful or a failed campaign. A large decrease in funding happens at the end of the year, after the month of June, and from the graph you can see that in December, the number of successful campaigns converges with the failed campaigns. This means the end of the year is the best time to launch a campaign, according to this data.
    Overall, both the successful and failed shows follow a similar pattern, where as the canceled shows, are consistently low and show no real increases, this means there is no real correlation between launch date and campaigns being canceled.  

### Conclusions for Outcomes based on Goals
    Looking at ![This is an image](/resources/Outcomes_vs_Goals.png), overall you can see an inverse relationship between the failed campaigns and the successful campaigns. 
    If we follow the successful campaigns, we see that lower end goals produced the highest amount of successful campaigns. After $5000, the percentage of successful campaigns decreases, however we can see around the 35000-44999 goal range, we get another rise in successful campaigns, reaching 66.7%. There is also a very sharp decrease, to 0 percent success when we hit $45000.
    From this, I can conclude that if you are looking to meet your fundraising goals, it seems you have the highest chance of success with a low goal (0-5000), however if you have a more expensive project that you need to fund, the optimal goal range according to this data would be from 35,000-45,000. 
    We can also conclude that, similar to the launch date analysis, there is no major significance in goal amount with canceled campaigns. 

### Limitations 
    This data set gives us values to describe which campaigns were successful based on monetary values but there are no values that give any insight into WHY certain campaigns were successful or not. There could be more data around how the campaigns were marketed, what type of advertising was used, what demographic was targeted for fundraising, etc. More details into the fundraising data would give more insight for someone like Louise to understand how to fundraise more successfully. For example, as we saw in our goal based analysis, it looks like there is high success in the $35,000-$45,000 range, relative to other higher end ranges, however from the data given, it is not clear why that is. More data sets as I described earlier, could give us a better picture. 

### Other possible tables/graphs 
    We could show the length of campaign vs. the outcome. This could give more insight into how long a campaign should be run for. 
    You could look at the successful outcomes vs countries, to see where the best place to start a fundraising campaign would be. This could be in the situation where you have fleibility to produce your show in different places.
    You could look deeper into the avg. donation and percentage funded data sets. 
    You could compare them to different regions or lengths of campaign to see if there are corelations. 
    For example, in the percentage funded data that there are a lot of projects that surpass their goals but some surpass them by almost 300%. You could compare the percentage funded to the length of campaign, and see if there are correlations there as to why some campaigns get so much more than their initial goal. 