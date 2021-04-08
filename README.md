# An analysis of Kickstarter Campaigns

   #### This analysis contains the following:
   ##### - Contents
   ##### - Overview
   ##### - Analysis and Chanllenges
   ##### - Results
   ##### - tables, charts, plots, images, descriptive statistics
   ##### - comparative analysis
   ##### - Recommendations

### Overview of Project
This project analyzes data from Kickstarter Campaigns to help identify trends that lead to the success or failures of campaigns. The analysis was done to help an artist (client) gauge the potential success of her kickstarter campaign. Subcategories, color-coding, pictures, and other items were used to help easily identify trends in this data.

An overview of this data is displayed below:
    ![kickstarter-overview](kickstarter-overview.png)
 
### Analysis and Challenges
#### Pre-Analysis
I started with downloading the raw data, which included information from 4,113 Kickstarter campaigns. I then assessed the data from a categorical perspective -- isolating just the "theatre" catagory's outcomes (parent category), as shown below: 
    ![Theatre_Outcomes](Theatre_Outcomes.png)
Looking at this chart, we can see that the majority of theatre campaigns were successful, while the number of failed theatre campaigns followed closely after. There were few canceled and fewer live.

#### Analysis
My client requested a chart on outcomes based on launch date for the theatre category. To fulfill this request, I created another sheet in the workbook titled "Theatre Outcomes by Launch Date" and applied the following conditions (see image below) to compare the successful, failed, and canceled outcomes:
    ![theatre-outcomes-overview](theatre-outcomes-overview.png)
    I then plotted these results:
    ![Theater_Outcomes_vs_Launch](Theater_Outcomes_vs_Launch.png)
    As we can see, the most successful theatre campaigns were launched between April and May. We take special note that the theatre campaigns launched in Decemeber appear to have tied for the outcomes of success or failure.
    
Taking this analysis even further, I created another sheet in the workbook titled "Outcomes Based on Goals" and used the COUNTIFS function to visualize these same 3 outcomes, filtering for just the "plays" subcategory, as displayed in the image below:
    ![goals-plays-overview](goals-plays-overview.png)
    Looking at the 3 outcomes percentages, I created the following chart:
    ![Outcomes_vs_Goals](Outcomes_vs_Goals.png)
    Here we see that the most successful "plays" campaigns, by percentage of goal, set a goal between _ and the most failed "plays" campaigns set a goal between $45,000-50,000.
    
    
    
    
    
### Results

#### Recommendations 
