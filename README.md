# 🎓 LinkedIn Job Postings Dashboard (Power BI)



## 📊Dashboard Preview



**Summary (Overview)**



!\[Summary Overview](images/summary(overview).png)





**Salary Trends**



!\[Salary Trends](images/salary-trends.png)





**Hiring Patterns**



!\[Hiring Patterns](images/hiring-patterns.png)





**Companies \& Industries**



!\[Companies and Industries](images/companies-industries.png)



This project presents a fully interactive Power BI dashboard built on the [arshkon/linkedin-job-postings](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings) dataset from Kaggle. The analysis explores salary trends, hiring patterns, and top companies/industries across \~3,000 job postings.

## 🎯 Objectives

* Analyze salary trends by job title and industry
* Compare hiring patterns across work types (Full-time, Part-time, Contract, Temporary, Other, Internship)
* Identify top hiring companies and industries

## ⚙️ Data Preparation

**🧹 Data Cleaning**

* Removed null/duplicate rows
* Renamed column headers
* Verified and corrected data types

**🔁 Data Transformation**

* Joined `postings.csv` with `job\\\_industries.csv` → `industries.csv` on `industry\\\_id`
* Normalized salary fields across Yearly/Monthly/Weekly/Hourly/Biweekly pay periods

**📈 Data Enrichment (Measures)**

* Total Postings, Total Industries, Total Companies, Total Work Types
* Average Salary, Median Salary, Max Salary Listed, Min Salary Listed
* Work Type Percent, Percentage of Contract Jobs, Percentage of Full-Time Jobs
* Top Company Posting Count

## 📊 Dashboard Pages (4 pages)

1. **Summary (Overview)** — Total Postings (3K), Total Industries (388), Average Salary ($121.68K), Total Companies (1K); charts for Pay Period, Total Postings by Top Companies, Total Companies by Location, Average Salary by Top Job Title, Total Postings by Pay Period, Total Postings by Work Type
2. **Salary Trends** — Average Salary by Industry Name, Average Salary by Pay Period, Max/Min/Average/Median Salary cards, table of Maximum Average Salary by Title \& Industry
3. **Hiring Patterns** — WorkType by Industry Name, Work Type Percent table (Full-time 88.42%, Part-time 5.67%, Contract 4.94%, Temporary 0.57%, Other 0.24%, Internship 0.17%), Total Postings by Work Type donut, Count of Work Type by Location
4. **Companies \& Industries** — Total Industries, Total Companies, Top Company Posting Count (44); table of Company/Industry/Total Postings, Total Postings by Company Name, Percentage of Work Type by Industry, Count of Jobs in TOP 5 Industries donut

## 🎛️ Slicers / Filters

Title, Location, Work Type, Company, Industry Name, Pay Period — available across relevant pages

## 🔑 Key Insights

* Full-time postings dominate the market at 88.42%, with Part-time and Contract together making up just over 10%
* Salary varies significantly by pay period type, with Yearly roles commanding the highest averages
* Hiring is concentrated in a small set of top companies and a few dominant industries, despite 388 industries represented in the data
* Average salary ($121.68K) sits notably above median ($107.69K), indicating high-salary outliers pull the average up

## ✅ Conclusion

This dashboard provides a clear view into current job market trends — helping job seekers, recruiters, or analysts understand salary benchmarks, hiring patterns by work type, and which companies/industries are actively hiring.

## 🚀 How to Use

1. Clone this repo or download the files.
2. Open `job-postings-dashboard.pbix` in Power BI Desktop.
3. Explore the slicers, charts, and KPIs across all 4 pages!

## 📁 Project Structure

```
job-postings-dashboard.pbix

Data/

\&#x20; postings.csv

\&#x20; job\\\_industries.csv

\&#x20; industries.csv

\&#x20; companies.csv



images/

\&#x20; summary(overview).png

\&#x20; salary-trends.png

\&#x20; hiring-patterns.png

\&#x20; companies-industries.png

```

## 🛠️ Tools Used

* Power BI Desktop — data modeling and dashboard creation
* Power Query — data transformation and cleaning

## 👤 Author

Misty Saha

* LinkedIn: [linkedin.com/in/misty-saha-120875400](https://www.linkedin.com/in/misty-saha-120875400)
* GitHub: [github.com/mistysaha](https://github.com/mistysaha)
* Email: sahamisty2006@gmail.com

## 🌟 Feedback \& Support

Feel free to share suggestions or compliments — your feedback is appreciated! If you found this project useful, please consider giving it a ⭐.

