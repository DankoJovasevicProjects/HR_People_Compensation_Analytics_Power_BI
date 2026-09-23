# HR People & Compensation Analytics with Power BI

## Introduction

This independently developed Power BI portfolio project is based on a fully synthetic but realistic 2025 HR dataset representing a fictional company. It was created to apply and strengthen data analysis, data modeling, and visualization skills through a practical business scenario covering two closely connected HR areas: **People Analytics** and **Compensation & Benefits**.

The source data was imported from Excel and organized into a **star schema**, with dedicated employee, job, organization, and date dimensions connected to separate monthly workforce and compensation fact tables. This structure enables consistent analysis across reporting periods, departments, pay grades, employment categories, and other relevant HR dimensions.

Using custom **DAX measures** and interactive **Power BI** visuals, the data was transformed into two dashboards focused on workforce trends, headcount and FTE, hiring and attrition, employer costs, salary positioning, and compa-ratio analysis. Although all employee and compensation records are fictional, the data structure, calculations, and reporting logic were designed to reflect realistic HR analytics requirements.

## People Analytics Dashboard

![Dashboard Page 1](/Images/People_Analytics_Dashboard.PNG)

The **People Analytics Dashboard** provides a consolidated view of workforce size, movement, and composition throughout 2025. Custom DAX measures were developed to distinguish month-end snapshot metrics, such as **Ending Headcount** and **Ending Active FTE**, from period-based workforce flows, including hires, terminations, net hires, and attrition.

The dashboard combines several analytical perspectives:

- **Workforce overview** through KPI cards displaying Ending Headcount, Ending Active FTE, Net Hires, and Attrition Rate.
- **Monthly workforce trends** comparing headcount and active FTE to show changes in both employee numbers and available workforce capacity.
- **Employee movement analysis** through a monthly comparison of hires and terminations.
- **Attrition analysis by department** helping identify organizational areas with comparatively higher employee turnover.
- **Workforce composition** by gender and employment type.

Interactive **Period** and **Department** slicers allow users to explore the same measures across different timeframes and organizational areas, while all visuals respond dynamically to the selected filter context.

## Compensation & Benefits Dashboard

![Dashboard Page 1](/Images/Compensation_Benefits_Dashboard.PNG)

The **Compensation & Benefits Dashboard** focuses on employer costs, salary structures, and employee positioning within defined pay ranges. All monetary values are presented in **RSD**, while custom DAX measures calculate total and average employer costs, base salary per FTE, salary band benchmarks, and compa-ratio indicators under the active filter context.

The dashboard presents several key areas of compensation analysis:

- **Employer cost overview** through KPI cards showing Total Employer Cost, Average Employer Cost per FTE, Average Base Salary per FTE, and Average Compa-Ratio.
- **Employer cost composition**  illustrating the relative contribution of base salary, employer contributions, benefits, allowances, and variable pay.
- **Average employer cost by department** enabling comparison of compensation costs across organizational areas.
- **Base salary positioning by pay grade** comparing average employee salaries with the minimum, midpoint, and maximum of the corresponding salary bands.
- **Average compa-ratio by pay grade** using the 100% band midpoint as a reference point for evaluating salary positioning.
- **Employee distribution by compa-ratio zone** separating employees positioned below, around or above their salary band midpoint.

Interactive Period and Pay Grade slicers enable more focused analysis of compensation costs and salary positioning across different reporting periods and grade levels.

## Skills Showcased

- **End-to-End Power BI Development**: Building an independent analytical project from source data import and modeling through measure development, visualization, and final dashboard design.
- **Power Query & Data Preparation**: Importing and transforming structured HR data from Excel, validating data types, and preparing workforce and compensation tables for analysis.
- **Data Modeling**: Designing a star schema with separate fact and dimension tables, one-to-many relationships, and a dedicated date dimension.
- **DAX Measure Development**: Creating context-aware measures for headcount, active FTE, hires, terminations, attrition, employer costs, salary benchmarks, and compa-ratio analysis.
- **HR Analytics**: Translating People Analytics and Compensation & Benefits concepts into measurable KPIs and practical reporting views.
- **Data Visualization**: Selecting appropriate cards, line charts, bar charts, treemaps, and donut charts to communicate workforce and compensation insights clearly.
- **Interactive Reporting**: Implementing slicers, cross-filtering, tooltips, and responsive visual interactions for dynamic exploration of the data.
- **Dashboard Design**: Creating two consistent, visually structured, and user-friendly report pages tailored to different HR analytical needs.

## Key Business Insights & Recommendations

- **Sales requires focused retention analysis**. Sales recorded the highest departmental attrition rate at 24.2%, followed by Marketing and Customer Support. HR should investigate the underlying drivers by reviewing exit reasons, tenure, management structure, workload, performance, and compensation positioning before defining targeted retention actions.
- **Workforce growth should be reviewed alongside the year-end decline**. The company finished the year with 540 employees, 532.1 active FTE, and 20 net hires. However, headcount and FTE peaked in October before declining during the final two months, suggesting that planned versus unplanned exits and future hiring requirements should be reviewed as part of workforce planning.
- **The overall compa-ratio masks differences in individual salary positioning**. An average compa-ratio of 101.8% indicates that salaries are generally positioned close to the midpoint of their respective salary bands. However, only 54.0% of employees fall within the 90–110% zone, while 18.8% are below and 27.2% are above it. Targeted reviews should prioritize employees below 90% for market alignment and salary progression, while employees above 110% should be assessed separately based on performance, tenure, scarce skills, and grade suitability.


## Conclusion

This project demonstrates how a well-structured Power BI solution can transform workforce and compensation data into clear, interactive insights that support more informed People Analytics and Compensation & Benefits decisions.