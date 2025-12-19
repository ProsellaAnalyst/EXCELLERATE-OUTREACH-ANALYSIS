# EXCELLERATE-OUTREACH-ANALYSIS
Recommending strategies for outreach team using messy real life university data.

 **## Excellerate Internship Project: 
 Student Outreach Data DashboardsAuthor: Daniella Shalom**
 
Date: December 19, 2025


**Introduction:**
 
 During my Excellerate internship, I worked with real call data from university student outreach programs. The goal was to clean the messy data and build 3 dashboards in Looker Studio to answer key questions:  How active were our campaigns?  
How successful were our calls?  
Who did we reach and who performed best?

This project taught me data cleaning, SQL, BigQuery, and visualization.

Here's how I did it, step by step.

**Project Overview:** 
The data came from three files: applicant data , outreach data, and campaign data.

It was messy — IDs broken, emails hidden, phone numbers inconsistent.

I cleaned and combined them into one master table (over 100 rows) in PostgreSQL and BigQuery. 

Then, I built the dashboards in Looker Studio.


**##Data Preparation ProcessExplored the data:** 
- Checked for issues like corrupted IDs and missing info.  
- Joined tables first: Learned to combine raw tables before cleaning — this rescued key details like clean App_IDs from the calls file.  
- Fixed problems: Added success flags ("Connected/Not Connected"), recovered emails, formatted phones.  
- Created calculated fields: Used SQL-like formulas for success rates and unique counts.  
- Loaded to BigQuery: For fast querying in Looker Studio.

Dashboard 1: Campaign Activity

This dashboard shows call volume, categories, trends, and details. 

*Key Features:*  
Bar chart: Total calls by campaign  
Donut chart: Calls by category  
Table: Campaign name, start date, success rate, connected calls  
Line chart: Calls over time

## Dashboard 1
Screenshot  <img width="602" height="453" alt="Campaign Activity Dashboard" src="https://github.com/user-attachments/assets/5576f138-7002-49a4-ae7c-8b1e0906e6a2" />

Link to Dashboard: https://lookerstudio.google.com/reporting/4aa9736f-7257-4c68-86c1-a016edb47912

**Insights:** Post-Admission campaigns dominated (81.3%), with peaks in certain months. 
**Recommendation:** Replicate high-volume strategies.


Dashboard 2: Connectivity Performance
This one focuses on call success rates across campaigns, callers, and countries.  

*Key Features:*  Scorecard: Overall 83.33% connectivity  
Bar chart: Connectivity by campaign  
Geo map: Call volume by country  
Bar chart: Calls by country  
Bar chart: Top callers by connectivity

Dashboard 2 
Screenshot <img width="690" height="517" alt="Connectivity Performance Dashboard" src="https://github.com/user-attachments/assets/0f0d60a3-8923-4173-bba3-644d8856803d" />

Link to Dashboard: https://lookerstudio.google.com/reporting/4aa9736f-7257-4c68-86c1-a016edb47912

**Insights:**  Top callers like Mounika (100%) stand out. Variation shows room for training. 
***Recommendation:** Share top performers' techniques to boost rates.Dashboard 3: Student Reach PerformanceThis dashboard highlights unique students reached and top performers.  

*Key Features:*
Bar chart: Unique students by top campaigns  
Bar chart: Top callers by connectivity  
Line chart: Student reach over time  
Stacked bar: Total vs successful reach (top campaigns)

Dashboard 3 Screenshot <img width="670" height="504" alt="Student Reach Performance Dashboard" src="https://github.com/user-attachments/assets/88ec399a-707a-4363-b076-41c1443bb695" />


Link to Dashboard: https://lookerstudio.google.com/reporting/4aa9736f-7257-4c68-86c1-a016edb47912

**Insights:** Top campaign reached 4,726 students, but gaps in successful reach. 

**Recommendation:** Focus on effective callers and timing for better results.


##Challenges & Lessons 
**LearnedTechnical hurdles:** Permissions errors, slow loading, formatting issues — solved with calculated fields and style tweaks.  
**Key lesson:** Join data first, then clean — saved hours.  
**Growth:** Went from zero experience in BigQuery/Looker to building full dashboards. SQL in calculated fields was a game-changer.  
**Overall:** Data work is 80% cleaning, 20% visualization — but the insights make it worth it.

## Validation & Accuracy

I validated all key metrics with PostgreSQL queries — everything matched 100%.

For example: * Overall connectivity: 83.33%*
<img width="932" height="318" alt="Screenshot 2025-12-19 131051" src="https://github.com/user-attachments/assets/f52a8591-c11d-4e38-a194-f21ecc145326" />
<img width="395" height="169" alt="Screenshot 2025-12-19 131807" src="https://github.com/user-attachments/assets/d01cc7f3-5fc1-44bd-b280-a49b50e084e1" />

*Calls Distribution by Category*
<img width="339" height="208" alt="Screenshot 2025-12-19 130013" src="https://github.com/user-attachments/assets/d088d269-29d5-4e45-863c-3330725fd4d9" />
<img width="712" height="315" alt="Screenshot 2025-12-19 130057" src="https://github.com/user-attachments/assets/9f215f65-9cec-407f-b1f2-edd5aba29d31" />



RecommendationsTrain team using top callers' methods.  
Replicate high-success campaigns.  
Optimize timing based on peaks.

This project showed me how data drives decisions. Open to feedback!(Feel free to add your LinkedIn or contact info.) 

