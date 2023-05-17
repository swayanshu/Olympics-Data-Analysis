# Olympics Data Analysis for Triathlon Sport
                                                                       
## Overview
The objective of these analyses is to determine whether or not there are patterns in the characteristics of Olympic medal winners across categories such as nationality, age, height, etc. I used statistical analysis to determine if any of these factors were substantially correlated with Olympic medalists, with the aim of identifying the characteristics that are most predictive of Olympic success.

## Data Source
Kaggle: https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results

## Data Details

The file athlete_events.csv contains 271116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event (athlete-events). The columns are:

ID - Unique number for each athlete
Name - Athlete's name
Sex - M or F
Age - Integer
Height - In centimeters
Weight - In kilograms
Team - Team name
NOC - National Olympic Committee 3-letter code
Games - Year and season
Year - Integer
Season - Summer or Winter
City - Host city
Sport - Sport
Event - Event
Medal - Gold, Silver, Bronze, or NA

# Results
![](/Images/EDA.png)

![](/Images/Heightvs weight.png)

![](/Images/Maps.png)

![](/Images/Menvswomen.png)


# Conclusion & Discussion
* From this analysis, we discover that men around the average age of 24 won more medals, whereas women won the most medals between the ages of 27 and 35.
According to our weight analysis, men and women who weigh between 60 and 80 pounds are more likely to win medals, but this is likely due to the fact that there are more medals available for this weight range and more athletes competing in this weight range.
* From our year-by-year analysis, we can see that medal distribution and medal winners have increased since the 1956 Olympics. China, the United States, and European nations had the most Olympic victories for both males and women. The height and weight analysis was the most eye-opening. Traditionally, we presumed that heavier and taller athletes were physically more capable of winning, but our research indicates that this is not the case.
* It appears that people of average weight and height are more successful, which makes sense given that there are more people of average height, but we were still surprised that their larger counterparts did not dominate them. There was not a significant correlation between an Olympic athlete's weight and height and their performance. The year in which the athlete competed had no significant effect on whether or not the athlete won a medal.
