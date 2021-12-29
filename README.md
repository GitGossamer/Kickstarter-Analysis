# An Analysis of Kickstarter Campaigns

## Overview of Project
Performing analysis on Kickstarter data to discover trends.

### Purpose
To provide Louise analysis and insight on how different fundraising campaigns fared in relation to respective launch dates and funding goals.

## Analysis and Challenges
Leveraging the COUNTIFS formula, allowed for visualization of the relevant data in organized pivot tables and charts to show campaign outcomes based on “successful”, “failed”, and “canceled”.

### Analysis of Outcomes Based on Launch Date
The data analyzed here will offer Louise insight into how other campaigns fared with her Fever campaign based on launch date.

Analysis performed on Launch Date was filtered on “Parent Category” and “Years”, then broken down by month for each individual category of “successful”, “failed”, and “canceled”. This data was presented in both a pivot table and a pivot chart to visualize trends for each category listed above.

![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/96449605/147700186-acf20aca-8609-490d-95fb-a5f42df45f82.png)

### Analysis of Outcomes Based on Goals
The data analyzed here will offer Louise insight into how other campaigns fared with her Fever campaign based on goals.

The COUNTIFS formula was used to collect the outcome and goal data for the “plays” subcategory. The analysis shows volumes and % of each individual category: “successful”, “failed”, and “canceled”. This data was presented in a pivot table and then visualized in a line chart to reflect trends over each individual goal range.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96449605/147701621-01d36ed2-f170-4d4c-9c99-d8f4016437c8.png)

### Challenges and Difficulties Encountered
Specific challenges related to accurately and manually entering all of the appropriate formulas and ranges to correctly reflect the data outcomes. Due to this process, there is ample room for human error. In order to overcome these, I reviewed my work and collaborated with colleagues for an additional perspective to see what I might be missing. This effort identified a few gaps which I corrected to give a more accurate representation of the data and how it is trending.

## Results

**- What are two conclusions you can draw about the Outcomes based on Launch Date?**
1.	May, June, and July are popular months for launching a successful theater-focused fundraising campaign. Louise should consider launching her next fundraising campaign during these months.
2.	Successful campaigns outnumbered failed campaigns nearly 2:1.

**- What can you conclude about the Outcomes based on Goals?**
•	There is an inverse relationship between “% successful” and “% failed” fundraising campaigns.
•	The goal range of 1000-4999 had the highest volume of both successful and failed campaigns.
•	The goal range of “Less Than 1000” had the highest % of successful campaigns; whereas the goal range of “45000-49999” had the highest % of failure (with only 1 campaign launched), followed by “Greater than 50000” with 88% failed, then “25000-29999” with 80% failed.

**- What are some limitations of this dataset?**
•	Doesn’t include external factors that might have an influence on fundraising success, failure, or cancelation (e.g., the economic conditions).
•	How reliable is the data? Ex: The data set only covers 8 years. Would more clarity and confidence come from a broader range of dates?

**- What are some other possible tables and/or graphs that we could create?**
•	A scatterplot would be a good chart to investigate for identifying possible outliers.
•	A table or graph that compares Theater campaigns against other campaigns to see how they fare…as was Louise’s original intent for the analysis.

