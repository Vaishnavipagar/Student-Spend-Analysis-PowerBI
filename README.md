# Student Survey Power BI Report
# Project Overview

The Student Survey Power BI Report project analyzes spending patterns of students across different stores and categories such as Video Games, Indoor Games, Toys, Books, Gadgets, etc. The goal is to provide meaningful insights using Power BI visualizations, helping store managers and stakeholders understand consumer behavior.

# Problem Statement

Create a comprehensive Power BI Report to visualize student spending patterns across different store locations and store settings.

Visualizations
1. Tabular Visualization

Format the Total Amount of Purchase (TAP) based on Store location and Store setting:

i) If 0 < TAP < 35000 → Red color

ii) If 35000 <= TAP < 60000 → Yellow color

iii) If TAP >= 60000 → Blue color

2. Matrix Visualization

- Display amount spent on Outdoor sports across different ages and Store setting.

- Apply color formatting for total Outdoor sports amount.

3. Funnel Chart

- Show Total Amount of Purchase by Store setting.

- Display data labels as Percentage of First.

4. Pie Chart

- Show Total Amount of Purchase by different Store location for Suburban Store setting only.

- Use Filter context to restrict data.

5. Scatter and Sand Dance Plots

- Scatter Plot: Video Games purchase vs. Outdoor Sports spent across different ages.

- Sand Dance Plot: Indoor Sports vs. Video Games spent across different age groups.

6. Row-Level Security (RLS)

- Restrict data access for users based on User Mapping Table.

- Example: Mani should only view Rural area data.

7. Publish and Schedule

- Publish the report on Power BI Cloud Service.

- Design a Master Dashboard consisting of Funnel Chart and Scatter Plots.

- Schedule refresh 6 times a day every 4 hours.

8. Q&A Feature in Power BI

- Average age of students using Q&A.

- Donut chart for Total Amount of Purchase by Store location.

# Technologies Used

- Power BI Desktop for data modeling and visualization.

- Power BI Service for publishing and scheduling refresh.

- DAX (Data Analysis Expressions) for calculated columns and measures.

- Row-Level Security (RLS) for user access restriction.

# Authors

Vaishnavi Pagar

# License

This project is licensed under the MIT License.

# Contact

For any queries, please contact: vaishnavipagar31@gmail..com
