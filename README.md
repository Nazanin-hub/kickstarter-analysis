# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends

# Kickstarting with Excel

## Overview of Project

### Purpose

Using Pivot table and graph in excel to find outcome of different campaigns based on their launch dates and their funding goals

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Beased on following graph,in January, the number of successful projects is 56, while the number of failed projects is 33 and canceled projects is 7. The number of successful projects is rising up during Jan to May however it has one fluctuation between Jan to March.During March to May, it experienced a rapid surge to 111 and it reaches it's peak in May.Then, it dramatically declines to 37 in December.  The trend of failed projects shows a similar pattern. It is gradually rising up during Jan to May and it has one fluctuation in Feb. It reaches it's peak in May and then continued with a gradual decrease to 31 in Nov. However it has a big jump in Oct. Finally, in Dec, the number of successful and failed projects are close together.
https://github.com/Nazanin-hub/kickstarter-analysis/blob/master/Theater%20_outcomes%20_vs_launch.png

### Analysis of Outcomes Based on Goals

Beased on following graph, 75.8% of projects are successful with the lowest amount of goal. Then, it slightly dropped from 75.8% to 45%. Then, it significantly decreased to 20% and reached a lowpoint with amount of goal between 25000 to 30000. Then, it rised to 66.67% and remained steady between 35000 to 50000 goals. After that, it sharpley declined to the lowest point between 45000 to 50000. Then, it again increased to 12.5%. The trend for the number of failed projects is reverse. At first, it is in the lowest point with amount of goal less than 10000. Then, it rises up to 45% and then it gently rised to 80%. After that, it sharpley dropped to 33.3%.Again, it dramatically grows up to 100% and it reaches the highest percentage of failed projects.

https://github.com/Nazanin-hub/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png




### Challenges and Difficulties Encountered

#### My Challenges:

-part 2: 

      1.How to use COUNTIFS() function to populate the "number successful", "Number failed", and "number canceled" columns.

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
  
  2. As amount of goals increases, the percentage of success decreases.
  
  3. There isn't any canceled projects for plays subcategory.

- What are some limitations of this dataset?

  1. Varaiance of backers has not been considered in this dataset. It is very important because we should know hou much money each backer has invested.

  2. Percentage of pledged has not been considered in this dataset.
  
  3. State or city of each country has not been mentioned in this dataset. 

- What are some other possible tables and/or graphs that we could create?

  1. Creating one graph that shows outcomes based on parent category and subcategory.
  
  2. Creating one graph that shows outcomes based on country(location).

  3. Creating one graph that shows outcome based on donation.
  
  4. Creating one graph that shows outcome based on pledged.
