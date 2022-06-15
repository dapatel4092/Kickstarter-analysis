
# Analysis of Kickstarter Campaign  

## Overview and Purpose
After Louise's play came close to its fundraising goal, she is now curious how her play "Fever" fared in comparison to other plays and if there are specific variables or trends that lead campaigns to become more successful than others such as launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date 

First, we started off by sorting our data by theater outcomes by launch dates. We did this by using the =YEAR function based on the date the dataset was created. After finding they're dates created and date ended we then create a pivot table by having the filters be parent category (theater) and years, our outcomes in the column section, and rows as date created conversion and finally "count of outcomes" in the values section. This table now shows us Theater outcomes based on launch dates over a years time. 
 
Pic of pivotable 







After, we created a line chart to help visualize the percentage rate of successful , failed , and canceled kickstarters over a one year period of time. 





Pic of chart 




From this chart we can see that the month of May had the highest success rate while also having the highest rate of failure.


### Analysis of Outcomes Based on Goals
Next, we analyzed our dataset by looking at outcomes based on their goal's dollar-amount range. To determine this we used the =COUNTIF function to detect the number of successful, failed, and canceled at each goal dollar-amount range. After we grabbed the data for our data set, we then grabbed the average percentage for successful, failed and canceled at each dollar-amount range.


Pic pivot table 


We then use this data to create a line chart. This line chart helps us visualize the percentage of outcome rate based on goal dollar-amount ranges. 


Pic line graph 




We can now see Kickstarters with goals of 1,000 or less were 76% successful which the highest amount, while Kickstarters with  goals 50,000 or more tend to failed with a whooping 83% failure rate.






\### Challenges and Difficulties Encountered
Some challenges that were faced while making this analysis were mostly user errors typing in formulas and accidentally hitting wrong formatting. Another issue I ran into was with making sure you turn off previous filters before making a new pivot table.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The month of may had both the highest number of successful campaigns as well highest number of failed, while December had the lowest number of successful and failed.

- What can you conclude about the Outcomes based on Goals?

Campaigns that tend to have lower dollar amount goal ranges tend to have a higher rate of success than those with higher goal dollar amount ranges that tend to have higher rate of failure  

- What are some limitations of this dataset?

A limitation to this dataset could be that its outdated. Having access to datasets from recent years can help make sure the data overall is more accurate as well even uncover new trends

- What are some other possible tables and/or graphs that we could create?

We can create a table and chart using the parent category and subcategory and comparing their pledged and goal amounts to see which category and sub category is most successful.
