## Problem Statement

Which state should the College Board spend more money on to improve SAT participation rates?

## Executive Summary

The SAT and ACT are the primary standardised tests used for college admissions in the USA. Although not the only factor considered by colleges when reviewing prospective students, these standardised tests are useful as an objective criteria. Generally, there is no advantage in choosing either one of the tests, although participation rates and average grades tend to vary between states.

The new format for the SAT was released in March 2016. By studying the data from the following two years, we are able to identify trends and make recommendations based on these observations.

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|All|State in the US from which ACT/SAT data was collected|
|**act_xx_participation**|*integer*|ACT|Percentage rate of participation in the ACT for high school graduates in the year 20xx|
|**act_xx_english**|*float*|ACT|Average score for English (Range: 1 - 36)|
|**act_xx_math**|*float*|ACT|Average score for Math (Range: 1 - 36)|
|**act_xx_reading**|*float*|ACT|Average score for Reading (Range: 1 - 36)|
|**act_xx_science**|*float*|ACT|Average score for Science (Range: 1 - 36)|
|**act_xx_comp**|*float*|ACT|Average composite score, obtained from averaging the scores for English, Math, Reading & Science (Range: 1 - 36)|
|**sat_xx_participation**|*integer*|SAT|Percentage rate of participation in the SAT for high school graduates in the year 20xx|
|**sat_xx_ebrw**|*integer*|SAT|Average score for Evidence-Based Reading and Writing (Range: 200 - 800)|
|**sat_xx_math**|*integer*|SAT|Average score for Math (Range: 200 - 800)|
|**sat_xx_total**|*integer*|SAT|Average total score (Range: 400 - 800)|

## Exploratory Data Analysis

After cleaning & combining our datasets, we carry out an initial exploratory analysis to identify some information markers from the data, including the general distribution, spread & central tendency. Some trends can be observed in this step as well.

## Data Visualisation

To further expound on the Exploratory Data Analysis, creating plots and graphs helps us to visualise the data better and better find trends and correlations. Comparisons across certain factors such as time can also be easily made.

## Conclusions and Recommendations

Based on the exploration of the data, we know that the participation rates for SAT and ACT tend to mirror each other within a state. The states with the most extreme differences in rates are those with legislations in place that make on of the two tests [compulsory](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent). Meanwhile, participation rates and average scores for the tests tend to be inversely correlated, but this may just be due to selective bias as the low participation rates likely reflect the students who willingly take the optional test, and are of a higher caliber.

Additionally, the biggest factor in influencing participation rates outside of legislation is [money](https://www.chicagotribune.com/news/breaking/ct-iillinois-act-exam-met-20170414-story.html). States which switched over and sponsored a certain test for a year tended to have a higher participation rate that year as well.

With these in mind, it is recommended that the college board should invest more resources into *Oklahoma* to raise SAT participation rates there. One thing to note is to spend the money wisely, and the most effective way would probably be to lobby for legislation making the SAT compulsory in the state as that has been observed to be the greatest factor in increasing participation rates.

Some additional data that could help improve the analysis would include:
- Education Budgets by state
- Poverty rates by state
- Race/Religion statistics by state