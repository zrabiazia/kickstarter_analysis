# kickstarter Analysis

## Overview:
This project is to help Louise to understand how different campaigns fared in relation to their launch dates and funding goals. The main purpose is to analyze data and create visualization for Kickstarter data to read the outcomes of campaign with help of filters and charts.

## Analysis and challenges:
### Outcomes based on launch date:

•	Created 5 new columns Date created conversion, date ended conversions, years, parent category and subcategory to expand and simplify data.

•	Created Year column to get years out of launch date by using formula

=Year (Date ended conversion) 

Applied to rest of the column

![columns](https://user-images.githubusercontent.com/67460581/105126611-64f35a00-5a9c-11eb-9280-8bfe6f1c1c93.png)


•	Created a pivot table for theatre outcomes based on launch dates(month)

![pivot](https://user-images.githubusercontent.com/67460581/105127382-08913a00-5a9e-11eb-968b-769c3f16c7c7.PNG)
		


•	A line chart based on outcomes

![Theater_outcomes_vs_Launch](https://user-images.githubusercontent.com/67460581/105126267-9586c400-5a9b-11eb-86e6-27728e138ec4.png)
 

The difficulties were to extract months from the launch date data to determine the successful, failed and canceled outcomes.







## Outcomes Based on Goals:

•	Created a table 

![table](https://user-images.githubusercontent.com/67460581/105126615-658bf080-5a9c-11eb-996c-e6d0dab54a3b.png)
 

 
•	A line chart Outcome based on Goals

![outcomes_vs_goals](https://user-images.githubusercontent.com/67460581/105126259-93246a00-5a9b-11eb-8641-6e38ed46786e.png)


•	The difficulties were to calculate the successful, failed and canceled numbers based on goals with Formula: = COUNTIFS (). The goal criteria needed to be adjusted with every column. 
•	Also Canceled Percentage calculation had error because 0 cannot be dividend.

![error](https://user-images.githubusercontent.com/67460581/105126613-658bf080-5a9c-11eb-8c5d-82075a2a25bb.png)

 

•	To fix the error used the formula =IFERROR(D2/E2,0)

## Results:

Conclusion 1:  May is the month where if you calculate the successful numbers percentage and canceled numbers percentage shows the more promising outcome of launching the play Fever.
Conclusion 2: Louise also can consider the month of June to launch the play as well because of successful outcomes greater than the failed outcomes.

The limitations of this data set are for specific tv shows, films or theater. 

We can use the bar charts to show the outcomes based on launch date and goals for comparison between the successful, failed and canceled numbers.














