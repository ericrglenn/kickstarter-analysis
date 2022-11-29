# An Analysis of Kickstarter Campaigns.
Analysis regarding various Kickstarter campaigns specific to Theatre. 

# Kickstarting with Excel

## Overview of Project

The overview of the project was to analyze prior Kickstarter campaigns, and compile data in order to provide information to Louise who is interested in knowing how the other campaigns fared against hers with respect to their launch dates and funding goals. Louise recently ran a Kickstarter campaign to fund a play, and came close to reaching the goal. 
 
### Purpose

The purpose of the project is to compile and analyze data from prior Kickstarter campaigns to show Louise how her campaign fared against others with relation to launch date and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The analysis was conducted by creating a pivot table based on the dataset of prior campaigns, and then using the pivot to create a line chart to see the outcomes visually. The outcomes were aggregated for each particular month regarding success, failed and canceled campaigns. From the aggregated data a line chart was created to depict a visual representation of the results.

Pivot Table:

![image](https://user-images.githubusercontent.com/118394620/204378962-792b7767-cb43-4f17-8188-ff67b7d95d44.png)

Line Chart:

![image](https://user-images.githubusercontent.com/118394620/204373635-07ad712f-6417-40dd-b015-3b5b5f25eaee.png)


### Analysis of Outcomes Based on Goals
The analysis was performed by creating a table by utilizing the sumifs function in excel. Based on the Goal amount, the campaigns were counted with regard to successful, failed and cancelled. The percentages of each outcome were then calculated and used to create the line chart to depict a visual representation of the results.

Outcomes based on goals table:

![image](https://user-images.githubusercontent.com/118394620/204381270-6ee3dd1c-cd2f-43ad-84bf-6bc5e3ead598.png)

Line Chart:

![image](https://user-images.githubusercontent.com/118394620/204376101-15b32f87-b284-4b54-aa68-8f88d3a2315f.png)

### Challenges and Difficulties Encountered

There were a few challenges that could come up during the process of compiling and analyzing the data. Selecting the correct type of line chart in excel, particularly regarding the stacked line chart, is critical to getting an accurate visualization. The stacked line chart will result in a line chart that does not accurately depict the data. Having the correct cell references was critical when compiling the Outcomes Based on Goals table. By using absolute references, the table was easy to update when populating the formulas between columns.
 

## Results

•	What are two conclusions you can draw about the Outcomes based on Launch Date?

1.	Most campaigns are launched in May, which had the highest rate of success and failure.
2.	The rate at which campaigns failed or succeeded were relatively stable, so that as the successful rate increased or decreased so did the failed rate.

•	What can you conclude about the Outcomes based on Goals?

The highest percentage of successful campaigns had a goal amount less than 1,000. As the goal amount increased the rate of success decreased, until the amount hit 25,000 to 29,999, at which the rate increased and held steady through 40,000 to 44,999. At 45,000 to 49,999 there were 0 successful campaigns, but the amount increased to a 10% success rate at a 50,000 or more goal amount.

•	What are some limitations of this dataset?

The dataset does not include how much experience the person running the campaign has, which would directly affect the rate of success. Also, there could be influences during certain years (recession/Covid/etc.) that would impact the amount of success or failure.

•	What are some other possible tables and/or graphs that we could create?

A table that includes a breakdown by country to see what countries are most successful when launching a campaign. The rate of success for a given month of the year, which would show the best possible day of the week to launch a campaign.

