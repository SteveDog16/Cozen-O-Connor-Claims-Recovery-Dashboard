# Cozen O'Connor Claims Recovery Trend Dashboard

## Introduction
I have worked at Cozen O'Connor as an Information Systems intern, where I have built and optimized BI reports for the Subrogation department. One of the reports I optimized tracks the statute of limitations on active claims, displaying claims that were approaching the relevant statute. After converting the report from a PDF to Excel file, the report was able to run weekly faster with lesser manual work of the BI team. The dataset I used for this project is a sample of the report. Information, such as analyst names, have been altered to keep private of the company's information.
The objective of this project is to analyze paid claim trends at Cozen O'Connor and determine the underlying causes driving these trends.

## Questions to Ask
1. Which date variable is the most significant to determine the paid claim amount?
2. At what time period the paid claim amounts are at its peak?
3. What recovery stages associate with low and high paid claim amount?
4. What are the relationships between date variables in terms of the paid claim amount?
5. What are the recommended next steps based on the findings?

## Tools Used
- Python for data exploration, analysis, and visualization
- Power BI for displaying KPIs, graphs, and filters

## Dataset

  The dataset consists of 238 claims. The columns are:
- Unique Identifier: Code that distinguishes a claim from others.
- Analyst: Name of the analyst who is handling or is responsible for the case.
- Incident Date: The date on which the incident occurred or was initially reported.
- SOL PD (Statute of Limitations Projected Date): Estimated date for when a task, project, or event will be completed.
- Litigation Date Type: Category of dates associated with the litigation process.
- Paid Claim: Amount that has been paid out for a claim.
- Add Date: The date when this case or incident was added to the tracking system.
- Recovery Stage: The current stage of the recovery or resolution process for this case. The demand has been made and is under review by the opposing party or their insurance carrier.
 
## Dashboard
  ![image](https://github.com/user-attachments/assets/d077c6d2-b4ca-404c-b151-9c5572e12d3a)


## 1. Which date variable is the most significant to determine the paid claim amount?
![image](https://github.com/user-attachments/assets/29b1ecf2-da20-4e03-a7e2-e63e1a07df9a)
![image](https://github.com/user-attachments/assets/b1fa113d-f3a0-42cc-936e-f46226cf8900)
![image](https://github.com/user-attachments/assets/8909e076-fa8e-4eec-bb2b-87fe10eca179)

- Given the graphs showing each date variable and the understanding of the variables, incident date is the most significant variable to determine the relationship with paid claim amount.

## 2. At what time period the paid claim amounts are at its peak?
![image](https://github.com/user-attachments/assets/98d0e103-6cdb-47ad-a873-90cfc032f7d1)
KPI Scorecards when filtered by 2022
![image](https://github.com/user-attachments/assets/a696b85a-c123-4183-bc18-1b6e534f55c7)


- Paid claim amounts are at its highest in incidents that occurred between February to May of 2022, with May 2022 being the highest at a total of $1 million.

## 3. What recovery stages associate with low and high paid claim amount?
![image](https://github.com/user-attachments/assets/8684be5d-1e6c-45b3-8e7c-dfd592c61801)
![image](https://github.com/user-attachments/assets/fd989b24-de11-4f6d-90fb-d1f9da0a6f84)

- "Issued Demand Letter to Responsible Party" is the stage with the highest paid claims, following "Demand Under Review by Adverse Carrier/Resp Party" and "Settled and Awaiting Settlement Proceeds". This means that the majority of the claim amount is paid during the earlier stages of the litigation process.
- Claim that occurred in 2022 have a lot of paid amount at many distributed early stages. 2021 claims are also widely distributed in the early stages, but not as much as 2022. There are very few claims from 2018, 2020, and 2023 that showed up in some of the stages.
- The spring months have a lot of paid amount at many distributed early stages.

## 4. What are the relationships between date variables in terms of the paid claim amount?
![image](https://github.com/user-attachments/assets/2b7be990-b849-4261-a384-aa60717b4584)
![image](https://github.com/user-attachments/assets/78b0eb83-73b0-44f1-af55-72c8885d5126)

- Since SOL PD only ranges between February to May of 2024, it is not as significant as the other dates in analyzing the paid claim amount.
- There's a huge day difference between add and incident dates in February-March of 2020. Despite the huge difference, the paid claim amount is not as high as in 2022, which has little day difference. The smallest difference occurred throughout 2023. The pattern is very similar when comparing the trend of incident dates and paid claim and count vs. add dates and paid claim and count. Therefore, there's very little significance in the impact that the relationship between these variables have on paid claim.

## 5. What are the recommended next steps based on the findings?

The main recommended next objective is to address the spike in incidents and the associated paid claims observed during February to May 2022.

Some of the steps that are recommended to take to work on this objective include:
1. Incident Categorization: Break down the incidents by category to see if specific categories are contributing disproportionately to the spike.
    - If there are, conduct a detailed review of the financial impact of these incidents. Which types of claims were most costly? This could help prioritize areas for immediate intervention. Then, assess current insurance covers and claims processes to identify potential improvements or areas where coverage might need to be enhanced.
2. Internal Factors: Evaluate internal operational factors such as changes in workforce or policy shifts during these months and year that might have contributed to the rise in incidents.
3. External Factors: Consider external influences like economic downturns, regulatory changes, or environmental factors. For instance, severe weather conditions can often lead to higher incidents in certain industries.
    - This could be further investigated by reviewing the geographical distribution of the incidents. Certain regions might be more affected during these months due to local factors.
4. Historical Comparisons: Compare this period with any similar past events. Understanding how these were managed and what the outcomes were can provide valuable lessons.
    - Then, evaluate the effectiveness of measures taken in response to past incidents. This will help in refining current strategies.
5. Employee Feedback: Interview employees and management to gain insights into what they believe might be causing the increase. This might uncover issues not visible through data analysis alone.
6. Customer Feedback: If applicable, gather feedback from customers or end-users affected by these incidents. They might provide a perspective that internal data does not capture.
7. Preventative Measures: Develop or enhance preventative measures based on the findings. This could include training, better safety protocols, or enhanced risk management strategies.
8. Monitoring Systems: Implement or upgrade existing systems for better monitoring and reporting of incidents as they occur.
9. Continuous Improvement: Regularly review the outcomes of implemented measures and adjust strategies as needed based on what is or isn’t working. Also establish feedback loops with all stakeholders involved to ensure that all perspectives are considered in ongoing incident management strategies.

  
