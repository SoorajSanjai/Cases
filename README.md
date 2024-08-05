# Analysis of Customer Complaints and Feedback for Financial Products

## Problem Statement
The financial services sector has seen a significant influx of customer complaints across various institutions. This case study aims to analyze these complaints to identify key issues and areas for improvement. By examining the complaint data, response times, and resolution rates, we seek to provide actionable insights that can help financial institutions enhance customer satisfaction and operational efficiency.

## Action Taken
- **Data Cleaning**: The data was mostly clean and required minimal preprocessing.
- **Preprocessing**: Preprocessing was performed in the Power Query editor, as Power BI was used for data visualization.
- **Handling Null Values**: Null values, initially marked as 0 in some columns, were modified to "None" where appropriate.

## Objectives
1. **Identify Key Areas of Concern**: Determine the most common products and issues that customers are complaining about.
2. **Analyze Response Efficiency**: Evaluate the average response time and timely response rate to understand how effectively companies are addressing customer complaints.
3. **Assess Resolution Rates**: Examine the resolution rate to gauge the effectiveness of the complaint resolution process.
4. **Geographical Distribution**: Analyze the geographical distribution of complaints to identify any patterns or hotspots.
5. **Company Performance**: Evaluate the performance of different companies in handling and resolving complaints.

## Data Overview
The dataset includes records of customer complaints received by various financial institutions, detailing the product and sub-product involved, the specific issue and sub-issue, the company's response, and the status of the complaint. This entire detail is contained in a single table.

## Methodology Used
1. **Data Cleaning and Preparation**: Ensured the dataset is clean, with no missing or inconsistent values.
2. **Descriptive Analysis**: Used visualizations to understand, analyze, and present an overview of the complaint data, including counts, trends over time, and distribution by product and company.
3. **Key Performance Metrics**: Identified, calculated, and analyzed key performance metrics such as average response time, timely response rate, and resolution rate.

## Expected Outcomes
- **Identification of Key Products and Issues**: Determine the most frequently complained-about products and issues.
- **Response Efficiency Insights**: Gain insights into the efficiency and effectiveness of companies' responses to complaints.
- **Regional Variations**: Understand regional variations in complaint patterns.
- **Recommendations**: Provide recommendations for improving complaint handling processes and customer satisfaction.
- 
## Visualizations/Dashboard
![image](https://github.com/user-attachments/assets/c13ea53f-20a8-45a1-8ff3-56eb3b123774)

## Findings
- **Average Response Time**: The average response time to complaints is 0.25 days, indicating a quick initial reaction from the companies.
- **Timely Response Rate**: An impressive 99.7% of cases receive a timely response, showcasing the efficiency in acknowledging complaints.
- **In-Progress Cases**: A concerning 89% of cases are still in progress, indicating potential delays or backlogs in resolution processes.
- **Resolution Rate**: The resolution rate is relatively low at 11.02%, largely due to the high percentage of in-progress cases.
- **Complaints by Month**: 
  - There is a notable spike in the number of complaints in June. The reasons for this spike are currently unknown and may require further investigation.
- **Top Companies by Complaint Count**:
  - Equifax INC: 172 complaints
  - Transunion Intermediate Holdings INC.: 167 complaints
  - Experian Information Solutions Inc.: 165 complaints
  - Complaints to these companies constitute the highest number of cases in this dataset.
- **Company Response to Consumer**:
  - A majority of the resolved cases are closed with an explanation (45 cases).
  - 20 cases were closed with non-monetary relief.
  - A significant number of cases (525) are still in progress.
- **Geographical Distribution of Complaints**:
  - The states with the highest number of complaints are:
    - California (CA)
    - Texas (TX)
    - Florida (FL)
  - This spike in case numbers can also be partially attributed to the increased number of complaints for the top companies by complaint count (i.e., Equifax, Transunion, and Experian) since they offer their services in these states.
  - This geographical concentration suggests regional issues that may need targeted interventions.
- **Complaints and In-Progress Count by Product**:
  - The product category with the highest number of complaints is "Credit reporting or other personal consumer reports" with 520 complaints, out of which 483 are still in progress.


## Recommendations

#### 1. Improve Case Resolution Rates
- **Issue**: The high number of cases still in progress (89%) indicates a need for more efforts in resolving complaints.
- **Recommendations**:
  - Hire additional staff.
  - Improve training programs.
  - Implement more efficient complaint resolution processes.

#### 2. Improve Response Times for In-Progress Cases
- **Issue**: The average response time is good at 0.25 days, but the large number of in-progress cases suggests that while the initial response is quick, the follow-through to resolution is lacking.
- **Recommendations**:
  - Implement stricter follow-up protocols.
  - Conduct regular progress reviews.
  - Identify and address bottlenecks in the resolution process to help close cases faster.

#### 3. Enhance Communication with Consumers
- **Issue**: Consumers need to be regularly updated on the status of their complaints to manage their expectations and improve satisfaction.
- **Recommendations**:
  - Ensure clear and regular communication with consumers regarding the status of their complaints.
  - Provide updates even if the resolution takes longer.

#### 4. Focus on High Complaint Companies
- **Issue**: Equifax, Transunion, and Experian have the highest number of complaints, significantly higher than other companies.
- **Recommendations**:
  - These companies should review their products and reasons for the high number of complaints.
  - Work closely with customers to understand the root causes of complaints.
  - Develop joint strategies for improvement to reduce the number of issues.

#### 5. Investigate the Spike in June Complaints
- **Issue**: There was a spike in complaints in June.
- **Recommendations**:
  - Analyse the reasons behind the spike.
  - Examine any external factors, changes in company policies, or specific incidents that may have contributed to the increase.

## Conclusion:
By systematically analysing the customer complaint data, this case study provides valuable insights for financial institutions to enhance their customer service operations. The findings will help identify critical areas for improvement, enabling companies to address customer issues more effectively and improve overall satisfaction.

We have also included a Power BI dashboard that was used to analyse the data and can be used further to keep track of the metrics detailed in this case study.







