Objective:
The project aimed to analyze information on children living in low-income households across various wards in London, organized by geographic areas and boroughs. Using an 8-year dataset, the goal was to provide insights into trends over time and differences across boroughs.

Data Description:
The dataset comprised five variables:

Ward.code: Code for different wards in London

Wards..2018: Name of different wards in London

year: Different years for which data was collected

Borough: Name of different boroughs in London

children: Average number of children in low-income households

Data Processing:

Calculated mean, standard deviation, minimum, and maximum number of children for each borough, excluding certain unusual boroughs with null values.
Plotted graphs to visualize the average number of children over the years using violin plots and mean with standard deviation.

Statistical Analysis:

Conducted a t-test comparing the mean number of children in low-income households between 2014 and 2021.
Performed linear regression analysis to estimate the relationship between the year and the number of children in low-income households.
Key Findings:

Identified an increasing trend in the mean number of children in low-income households from 2014 to 2021.
Welch Two Sample t-test indicated a significant difference in the mean number of children between 2014 and 2021.
Linear regression analysis confirmed a statistically significant relationship between the year and the number of children in low-income households, with an increasing trend over time.

Conclusion:

The analysis highlights the changing dynamics of children living in low-income households in London over the study period. The findings underscore the importance of continued monitoring and potential interventions to address the needs of vulnerable populations.

References:

www.stackoverflow.com

www.datacamp.com

Lecture Resources

R for Data Science by Garrett Grolemund and Hadley Wickham
