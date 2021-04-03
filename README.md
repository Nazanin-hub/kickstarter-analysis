# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends

# Kickstarting with Excel

## Overview of Project

Helping an up-and-coming playwright,Louise, who wants to start a crowdfunding campaign to help fund her play,Fever. She wants to know how different campaigns fared in relation to their launch dates and their funding goals. So, I used Kickstarter dataset to help Louise with her project by creating Pivot table, charts and graphs.

### Purpose

Using Pivot tables and graphing in excel to visualize outcomes of different campaigns based on their launch dates and their funding goals.

## Resources

  - Data Source: Kickstarter dataset.xlsx
  - Software: Excel

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Based on the following graph,in January, the number of successful projects is 56, while the number of failed projects is 33 and canceled projects is 7. The number of successful projects is rising up from Jan to May. However, it has one fluctuation between Jan to March. During March to May, it experienced a rapid surge to 111 and it reaches its peak in May. Then, it dramatically declines to 37 in December. The trend of failed projects shows a similar pattern. It is gradually rising up from Jan to May and it has one fluctuation in Feb. It reaches its peak in May and then continued with a gradual decrease to 31 in Nov. However, it has a big jump in Oct. Finally, in Dec, the number of successful and failed projects are close together.

![](https://github.com/Nazanin-hub/kickstarter-analysis/blob/master/Theater%20_outcomes%20_vs_launch.png)

### Analysis of Outcomes Based on Goals

Based on the following graph, 75.8% of projects are successful with the lowest amount of goal. Then, it slightly drops from 75.8% to 45%. Then, it significantly decreases to 20% and reaches a low point with the amount of goal between $25000 to $30000. Then, it rises to 66.67% and remained steady between $35000 to $50000 goals. After that, it sharply declines to zero between $45000 to $50000. Then, it again increases to 12.5%. The trend for the number of failed projects is exactly reversed. At first, it is at the lowest point with the amount of goal less than $1000. Then, it rises up to 45% and then it gently rises to 80%. After that, it sharply drops to 33.3%. Again, it dramatically grows up to 100% and it reaches the highest percentage of failed projects before it decreases again.

![](https://github.com/Nazanin-hub/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)




### Challenges and Difficulties Encountered

#### My Challenges:

      -part 2:
      
            Challenges:

                        How to use COUNTIFS() function to calculate the "number successful", "Number failed", and "number canceled" columns.
      
            Solutions:
      
                        I chose collumns F, P and D from the KickStarter worksheet and calculated the numbers for the three desired criteria as follows:
            
                        Number successful:
                                          =COUNTIFS(KickStarter!F2:F4115,"successful",KickStarter!P2:P4115,"plays",KickStarter!D2:D4115,"$$desired interval")
                        Number failed:
                                          =COUNTIFS(KickStarter!F2:F4115,"failed",KickStarter!P2:P4115,"plays",KickStarter!D2:D4115,"$$desired interval")
                        Number canceled:
                                          =COUNTIFS(KickStarter!F2:F4115,"canceled",KickStarter!P2:P4115,"plays",KickStarter!D2:D4115,"$$desired interval")
      
      

#### Possible Challenges:

      -Part1: 

            1.How to use YEAR() function to extract the year from the " Date Created Conversion" coloumn.
      
            2.How to group the column to show just the months of the year in Pivot table.
      
      
      -Part2:

            1.How to use COUNTIFS() function with considering some criteria at the same time
      
            2.How to calculate the percentage of successful and canceled projects and create a line chart
      
      
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  1. The number of successful projects has been consistently higher than the number of failed and canceled projects.
  
  2. The maximum number of successful projects occurred in May.
  
  3. The number of successful projects during the spring and summer seasons are more than other seasons.

- What can you conclude about the Outcomes based on Goals?

  1. With minimum amount of goal, there is a highest percentage of successful plays.
  
  2. As the amount of goals increases, the percentage of success decreases.
  
  3. There isn't any canceled projects for Plays subcategory.

- What are some limitations of this dataset?

  1. Variance of backers' donations has not been considered in this dataset. It gives us a sort of understanding of the distribution of donations.

  2. Percentage of pledged has not been considered in this dataset.
  
  3. State or city of each country has not been mentioned in this dataset.

- What are some other possible tables and/or graphs that we could create?

  1. Creating one graph that shows outcomes based on the parent category and subcategory.
  
  2. Creating one graph that shows outcomes based on country(location).

  3. Creating one graph that shows outcomes based on average donation.
  
  4. Creating one graph that shows outcomes based on pledged.
