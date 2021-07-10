# Kickstarting with Excel

## Overview of Project

### Purpose and Background
This project seeks to analyze the results of Kickstarter campaigns based on their initial goals and launch date. A previous customer wants to know how other Kickstarter campaigns similar to her own fared, specifically with respect to launch date and pledge goal. She is interested in campaigns in the 'theater' parent category and in the 'plays' subcategory.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis counted the successful, failed, and canceled theater campaigns by launch date (per month) from the year 2009 to 2017. Looking at the image below it is clear that campaigns which were launched in May and June were the most successful by far. The least successful campaigns began in the winter months from December through March. If someone wanted to lauch a theater campaign on Kickstarter, they would find the most probable success if they launched it in late spring/early summer.
![Theater_Outcomes_vs_Launch](kickstarter-analysis/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
This analysis counted the successful, failed, and canceled theater plays campaigns by pledge goal. The goals were condensed into ranges to help visualize the results as seen in the line graph below. The highest percentage of successful theater plays campaigns are found in the less than $5000 and $35000 to $45000 ranges. This would suggest that lower goals tend to be more successful, with the exception of the $35000 - $45000 range. The higher range could be sweet spot for larger projects while the lower range could be the sweet spot for smaller productions.
![Outcomes_vs_Goals](kickstarter-analysis/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
No significant challenges or difficulties were encountered during this analysis. Possible difficulties could include formatting the pivot tables to show just the months (instead of years as well) and accidentally using filtered data to create a pivot table.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. The most successful months to launch a theater campaign are May and June
    1. The least successful times to launch a theater campaign are during the fall and winter months

- What can you conclude about the Outcomes based on Goals?
    1. Small productions should aim for a goal under $5000
    1. Large productions shoudl aim for a goal between $35000 and $45000

- What are some limitations of this dataset?
    1. This dataset's most recent data is 4 years old and trends may have changed since then
    1. This dataset contains kickstarter campaigns that are unlikely to be legitimate and may have skewed the data

- What are some other possible tables and/or graphs that we could create?
    1. We could narrow the scope of outcomes based on launch date to only include plays
    1. We could narrow the outcomes based on goals to only look at the most successful launch dates (by month)
