# Kickstarting with Excel

## Overview of Project

### Purpose

This project was to help Louise determine the best location, time and type of kickstart to invest in. 

## Analysis and Challenges
- One of the first challenges we came across was how to clean up the data to it most usuable state. 
- This cleanup required changing date formate, splitting cells, reorgainzing columm, and moving data around.
- First we reviewed and sort the data (clean up) for analysis. Some of the challenges when sorting the date was wwrong data types and too uch data in the columns to sort deep enough. We identified wrong data types for the launch and ..... date so we used a date conversion function to format the date into a standard view. For the categories of kickstarts we separated parent and sub category so we are able to drill down deeper for our analysis.

- Once the date cleanup was complete we moved on to analizing the data. We utilized a variety of excel functions like count, vslookup, and sum to gather our numbers and calculate things like success rate, percetage successful, total pledge, and other key totals that can be usesd to identify our goals.

Through the use of pivot tables and pivot graphs we were able to tell the story to support our findings by using basic tables and graphs to visually represent our data.

[Kickstart_Challenge](https://github.com/austink24/kickstarter-analysis/blob/master/Kickstarter_Challenge.xlsx)

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://github.com/austink24/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://github.com/austink24/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

 - I didn't really come across and difficult or challenging tasks. It was all very straight forward as far as Excel.
 - GitHub was the most difficult for me. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

    - Launching a Theater Kickstart during the summer months greatly increases the chances of being successful!
    - The Graph also shows that if we stick with Theater we are twice as likely to successed than fail!
    
- What can you conclude about the Outcomes based on Goals?

  - Lines graphed for Success and Failure are opposite mirrored images of each other throughout ranges of Goals. They move in syncranicity but in opposite directions.
  - Making it clear there are ranges to avoid when determining the goal mount. 
  
- What are some limitations of this dataset?

  - It didn't include audience demographics.
  - While the data tracked country it didn't let us dig any deeper, filtering by states or the equivalant for each country. 
  
- What are some other possible tables and/or graphs that we could create?

  - We could have graphed the percentage successful against the parent category to see if one was more successful than others.
