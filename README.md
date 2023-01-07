# TableauDataAnalysis

## Total four component:
1. Purpose: To unlock sales insights that are not visible before for sales team for decision support & automate them to reduced manual time spent in data gathering.

2. Stakeholders: sales director, marketing team, customer service team, data & analytics team, it.
3. End result: An automated dashbord providing quick & latest sales insights in order to support data driven decison making.
4. Success Criteria: 
- Dashbord uncovering sales order insights with latest data available, 
- sales team able to take better  decisions & prove 10% cost savings of total spend.
- Sales Analysts stop data gathering manually in order to save 20% of their business time and reinvest it value added activity.

## Data Analysis using SQL

## Model Creation in Tableau

![image](https://user-images.githubusercontent.com/86125144/211152688-5d205690-1d09-4c2b-9387-892cd81f238a.png)


## Data cleaning in Tableau
1. Sales Amount in Transcations table contain value -1 and 0 that is not possible may be some wrong data entry so we have to remove that row for better analysis.

![image](https://user-images.githubusercontent.com/86125144/211151725-27b35bfc-a035-432e-b6d1-322077fcf4d0.png)

<b>go to tableau-> data -> edit data source filter -> select range upto 1.</b>

![image](https://user-images.githubusercontent.com/86125144/211151316-e5519f3d-b16a-495c-8afd-df5fd644e502.png)


2. In our markets table there two markets code MARK097 and MARK999 for NEW YORK and PARIS respectiviley but our company have only business in India, so that is a case of wrong data entry we have to remove this.![image](https://user-images.githubusercontent.com/86125144/211151445-8a1a17b6-5892-4985-8667-4ef13315a2b9.png)
![image](https://user-images.githubusercontent.com/86125144/211151992-b14b4411-323a-4c96-b75f-dd4abf1839ba.png)


3. Dollar :Here two currency is in DOLLAR that may be possible as some NRI visit our shop and make payment in Dollar. But for our analysis our currency unit must be same so we will convert DOLLAR to RUPEES by creating NEW COLUMN NORMALIZED AMOUNT. 

![image](https://user-images.githubusercontent.com/86125144/211152328-dd9f7ff6-eb0a-4b4f-b9f6-36199cbc80b2.png)


![Dashboard 1](https://user-images.githubusercontent.com/86125144/211169320-bcdb6044-576c-41b0-bc6d-18b99120f6c5.png)


