# Gender-Age-Distribution-Analysis
Data Analysis: Homeless Deaths by Age Group and Gender
This project analyzes homeless death trends across different age groups and genders from 2013 to 2020. The goal is to identify demographic segments most affected and highlight patterns that can support targeted social interventions.

Methodology
1. Data Loading & Reshaping
The dataset (2013–2020) was loaded into a Pandas DataFrame.
Since the raw file recorded yearly death counts across multiple columns, the data was reshaped using melt().
This transformation created:
A single Year column
A corresponding Count column
This structure made it easier to analyze trends across all years consistently.

2. Data Aggregation
The melted dataset was grouped by sex and age_group.
Death counts were summed across all years to determine the total number of deaths for each demographic segment.

Key Findings
1. Major Gender Disparity
Males account for a much higher number of homeless deaths compared to females.
This imbalance is visible across almost all age brackets.

2. Peak Age Groups
Males: Highest concentrations occur in middle-aged groups, especially:
35–39
40–44
45–49
Females: The 40–44 age group shows the highest death count.

3. 'All Ages' Category Insight
Total deaths recorded across all age groups:
Males: 7,559
Females: 1,035
This highlights the severe and disproportionate impact on men.

Conclusion

This analysis reveals critical demographic segments disproportionately affected by homelessness-related deaths. Middle-aged males show the highest vulnerability, emphasizing the need for focused support, improved social programs, and stronger intervention strategies.
