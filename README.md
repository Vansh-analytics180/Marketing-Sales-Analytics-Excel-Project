# Marketing & Sales Analytics | Excel Project

## Dashboard Preview

<img width="1332" height="818" alt="Screenshot 2026-10-12 080246" src="https://github.com/user-attachments/assets/675e3917-bde1-4985-bf79-fbd08438b769" />

## Project Overview

This project explores customer enquiries, sales activity, service response, issue resolution, and customer satisfaction using Microsoft Excel.

The objective is to understand where enquiries come from, how effectively they are handled, how sales activity changes over time, and where service performance may need improvement.

Rather than looking at enquiry volume alone, this analysis brings together customer service and sales-related indicators to support more informed business decisions.

## Business Problem

Businesses need to understand whether customer enquiries are being answered, whether issues are being resolved, and which channels and products contribute to sales activity.

This project addresses the following questions:

* Which channels generate the highest number of enquiries?
* How many enquiries receive a response and how many are resolved?
* Which enquiry types and priority levels require attention?
* How does new product sales activity change month by month?
* Which product types contribute most to recorded sales activity?
* How is customer satisfaction distributed?
* How do enquiry and resolution patterns vary across agents?

## Dataset Overview

* **Reporting period:** January–December 2025
* **Records:** 10,712
* **Columns:** 16
* **Tool:** Microsoft Excel

Key fields include Date, Enquiry ID, Enquiry Source, Enquiry Type, Priority Type, Agent Name, Country, Gender, Product Type, Response Status, Resolution Status, New Product Sales, Response Time, Resolution Time, and Satisfaction Rating.

## Tools & Techniques

* Microsoft Excel
* PivotTables and PivotCharts
* KPI calculations
* Data summarization and aggregation
* Monthly trend analysis
* Customer satisfaction analysis
* Agent and channel performance analysis

## Dashboard Preview

Add your dashboard screenshot to the repository and display it here.

![Marketing and Sales Dashboard](images/marketing-sales-dashboard.png)

## Key Performance Indicators

| KPI                                |         Result |
| ---------------------------------- | -------------: |
| Total Enquiries                    |         10,712 |
| Enquiries Responded To             |          9,672 |
| Response Rate                      |         90.29% |
| Enquiries Resolved                 |          8,239 |
| Overall Resolution Rate            |         76.91% |
| Recorded New Product Sales Entries |          2,984 |
| Average Response Time              |   9.01 minutes |
| Average Resolution Time            | 248.41 minutes |
| Average Satisfaction Rating        |       3.93 / 5 |

**Calculation notes**

Response Rate = Responded Enquiries / Total Enquiries

Overall Resolution Rate = Resolved Enquiries / Total Enquiries

Average Satisfaction Rating is calculated from records with an available rating. The resolution-time average excludes missing values.

The 2,984 sales entries represent records where the New Product Sales field is populated. They should not be interpreted as a confirmed number of completed purchases without validating the field's business definition.

## Chart-by-Chart Analysis

### 1. Monthly Enquiry Trend by Channel

**Chart type:** Monthly column charts.

**Purpose:** To understand how enquiry volume changes over time across communication channels.

**Interpretation:** Each column represents the number of enquiries recorded in a month for a specific channel. Higher columns indicate greater enquiry volume.

**Business value:** Monthly patterns help identify changes in channel demand and support workload planning.

**Recommended action:** Compare monthly volume with response rate, resolution rate, and staffing capacity before making resource-allocation decisions.

### 2. New Product Sales Trend

**Chart type:** Monthly column chart.

**Purpose:** To track the number of records containing new product sales information over time.

**Interpretation:** Higher monthly values indicate more records with a populated sales field.

**Business value:** This view helps identify months with higher or lower recorded sales activity.

**Recommended action:** Validate the sales field and compare its monthly trend with total enquiries and conversion data, if available, before drawing conclusions about sales growth.

### 3. New Product Sales by Product Type

**Chart type:** Product-wise column chart.

**Purpose:** To compare recorded new product sales activity across product types.

**Interpretation:** Taller columns represent product types with more populated sales records.

**Business value:** The chart provides an initial view of the product types associated with recorded sales activity.

**Recommended action:** Compare sales value, units sold, and conversion rates where available to determine which products contribute the most commercial value.

### 4. Enquiries by Enquiry Type

**Chart type:** Column chart.

**Purpose:** To understand the distribution of enquiries across service and sales-related categories.

**Interpretation:** Each column represents the count for an enquiry type, including service upgrades, incidents, cancellations, downgrades, problems, and new product enquiries.

**Business value:** The distribution helps identify the types of customer requests that contribute most to operational workload.

**Recommended action:** Review frequent enquiry types alongside resolution rates and satisfaction scores to identify opportunities for process improvement.

### 5. Enquiries by Priority Type

**Chart type:** Doughnut chart.

**Purpose:** To show the composition of enquiries across Critical, High, and Normal priorities.

**Interpretation:** Each segment represents a priority category's share of the recorded enquiry population.

**Business value:** The chart helps assess the volume of high-priority work that the team needs to manage.

**Recommended action:** Review response and resolution performance by priority. Critical enquiries may need stricter service-level monitoring than Normal enquiries.

### 6. Enquiries by Product Type

**Chart type:** Doughnut chart.

**Purpose:** To compare enquiry volume associated with different products.

**Interpretation:** Each segment represents the number of enquiries associated with a product type.

**Business value:** Products generating more enquiries may warrant closer investigation into customer needs, service issues, or product-related support demand.

**Recommended action:** Compare enquiry volume with sales volume and customer satisfaction to understand whether a product has high demand, high support needs, or both.

### 7. Customer Satisfaction Distribution

**Chart type:** Column chart.

**Purpose:** To understand how customers rate their experience.

**Interpretation:** Ratings from 1 to 5 show the distribution of recorded customer satisfaction scores.

**Business value:** The distribution helps distinguish positive experiences from lower-rated interactions that may require further investigation.

**Recommended action:** Review low ratings alongside enquiry type, channel, response time, and resolution status to identify potential drivers of dissatisfaction.

### 8. Enquiries by Gender

**Chart type:** Column chart.

**Purpose:** To describe the distribution of recorded enquiries across gender categories.

**Interpretation:** The chart compares enquiry counts for each category.

**Business value:** It provides a descriptive view of the dataset's customer composition.

**Recommended action:** Use this breakdown only where relevant to a legitimate business question. Enquiry counts alone do not establish differences in satisfaction or service quality between groups.

### 9. Enquiry Volume by Agent

**Chart type:** Agent-wise comparison chart.

**Purpose:** To compare the workload recorded for individual agents.

**Interpretation:** Higher values represent greater enquiry volume for the corresponding agent.

**Business value:** The comparison can help understand workload distribution and identify potential capacity imbalances.

**Recommended action:** Review enquiry volume together with case complexity, working hours, response times, and resolution outcomes before evaluating agent performance.

### 10. Resolution Status by Agent

**Chart type:** Agent-wise comparison chart.

**Purpose:** To compare enquiry resolution outcomes across agents.

**Interpretation:** The chart compares the recorded resolution status associated with each agent.

**Business value:** It helps identify differences in resolved and unresolved workload that may need further review.

**Recommended action:** Compare resolution rates, open-case volume, case age, and priority mix rather than judging agents using raw counts alone.

### 11. Priority Distribution by Agent

**Chart type:** Agent-wise priority comparison chart.

**Purpose:** To examine the mix of Critical, High, and Normal enquiries handled by agents.

**Interpretation:** The series compare the number of enquiries in each priority category for individual agents.

**Business value:** The chart helps show whether agents handle different types of workload.

**Recommended action:** Consider priority mix when comparing resolution performance. Agents handling more complex or high-priority cases may require a different performance context.

## Key Business Observations

The dataset contains 10,712 enquiry records from 2025. A response is recorded for 9,672 enquiries, giving a response rate of approximately 90.29%.

A total of 8,239 enquiries are marked as resolved, equivalent to 76.91% of all recorded enquiries. These are overall rates; they do not, by themselves, explain why some enquiries remain unresolved.

The average recorded response time is approximately 9.01 minutes, while the average recorded resolution time is approximately 248.41 minutes. These measures represent different stages of the service process and should be monitored separately.

The average satisfaction rating is approximately 3.93 out of 5 among records with a rating. Understanding the distribution of scores and their relationship with resolution outcomes would provide a more complete view of customer experience.

## Recommendations

1. Monitor response and resolution rates separately.
2. Investigate enquiry categories with higher unresolved volumes.
3. Track monthly sales-related activity and validate it against actual sales measures.
4. Compare agent performance using rates, workload, and case complexity.
5. Review lower satisfaction ratings to identify potential service improvement opportunities.
6. Establish targets based on approved business standards and monitor performance against them.

## Limitations

The analysis is based on the fields and values available in the workbook. Missing response times, resolution times, satisfaction ratings, and sales entries may affect comparisons.

A populated sales field is not necessarily equivalent to a completed sale or a monetary sales total. Likewise, overall resolution rates do not indicate the resolution rate among responded enquiries unless that denominator is calculated separately.

The findings are descriptive and do not prove the causes of performance differences.

## Conclusion

This project demonstrates how Microsoft Excel can be used to summarize customer enquiries, monitor service indicators, analyze sales-related activity, and present business information through charts and KPIs.

It also highlights the importance of interpreting metrics in context. Enquiry volume, response rate, resolution rate, sales activity, and satisfaction each provide a different perspective on business performance.

## Author

**Vansh Kumar**
Aspiring Data Analyst

Skills: Excel, data analysis, KPI reporting, business insights, and data visualization.


