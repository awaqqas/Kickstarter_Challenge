# Kickstarter_Challenge

# Purpose
The purpose of this assignment was to examine how different campaigns fared in relation to their launch dates and their funding goals. Kickstarter dataset was utilizied to visualize campaign outcomes based on their launch dates and their funding goals.

# Analysis and Challenges

One of the biggest challenges with the dataset was that the dates were not in normal date time format but rather in a UNIX format. These had to be converted prior to any form of analysis. In addition, parent category and subcategory were one column and as such were separated into two columns for the analysis to be successful via the pivot table. Lastly, creating a ine graph based on multiple y-axis columns was challenging as well. 

Analysis based on outcomes by launch date

<img width="700" alt="Screen Shot 2022-02-23 at 2 09 48 AM" src="https://user-images.githubusercontent.com/90429568/155274955-749009bc-614e-4fdd-813f-f734c2854ff8.png">

From the chart above, it can be safely denoted that the two most succesful months were May and June, since majoirty of the successful kickstarters occured in this month. This could be due to the fact these months are also warm and as such everyone is out and about. This notion is further supported by the fact that the month of December was the worst month to perfom a fundraiser specifically with category of theatre.

<img width="960" alt="Screen Shot 2022-02-23 at 2 16 27 AM" src="https://user-images.githubusercontent.com/90429568/155275643-c3951701-d181-49a9-9d39-c2fff061dd3b.png">

Additionally, the higher the goal the higher the chances of failing. In fact, it is interesting to note that goals greater 44999, had a high probability of failing versus lower goals. This is supported by the graph above. 

# Results
As already mentioned, theatre outcomes by launch date shows summer months are better than winter months. Additionally, one may think this could be true for some years versus others, however since the dataset was not filtered for any specific year, this holds true for all years. 

Outcomes based on goals definitely shows that higher you go, the higher the probability of failing. It's better to start off low and then build up in order to be successful.

The dataset was definitely missing reviews. Was the high success rates also due to reviews? This is left to the analysts' imagination!

A correlation analysis between summer months and goal amounts would be interesting to view. This would tell the analysts; if aiming for higher goals in summer months is safer than aiming for higher goals in winter. 
