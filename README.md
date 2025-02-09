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





