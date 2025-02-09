# Cozen O'Connor Claims Recovery Trend Dashboard

## Introduction
I have worked at Cozen O'Connor as an Information Systems intern, where I have built and optimized BI reports for the Subrogation department. One of the reports I optimized tracks the statute of limitations on active claims, displaying claims that were approaching the relevant statute. After converting the report from a PDF to Excel file, the report was able to run weekly faster with lesser manual work of the BI team. The dataset I used for this project is a sample of the report. Information, such as analyst names, have been altered to keep private of the company's information.
The objective of this project is to analyze paid claim trends at Cozen O'Connor and determine the underlying causes driving these trends.

## Questions to Ask
- What variables correlate with paid claim amount?
- Which date variable is the most significant to determine the paid claim amount?
- At what time period the paid claim amounts are at its peak?
- What recovery stages associate with low and high paid claim amount?
- Do the add and SOL projected dates affect the paid claim amount?

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

### Filters
![image](https://github.com/user-attachments/assets/a8358f8b-cb0d-4c5c-88cb-1b67133172f6)
![image](https://github.com/user-attachments/assets/6b3ec9ce-1172-4c4f-843a-45ea8e18cf27)
![image](https://github.com/user-attachments/assets/d1b1c9d5-a7bb-4179-84aa-9f6b55a84891)



