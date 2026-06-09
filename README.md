# NYC 311 Service Requests Analysis

## Project Overview

This project analyzes New York City's 311 Service Requests dataset to uncover patterns in citizen complaints, agency workload, and service request resolution performance.

Using Python, Pandas, Matplotlib, and Seaborn, the project follows a complete data analytics workflow including data cleaning, feature engineering, exploratory data analysis (EDA), KPI creation, and business insight generation.

A representative sample of 100,000 service requests was used to perform efficient analysis while preserving overall dataset trends.

---

## Business Problem

New York City's 311 system receives thousands of requests related to issues such as illegal parking, sanitation, housing, infrastructure maintenance, and noise complaints.

For city administrators, understanding this data is important for answering questions such as:

* Which agencies receive the highest workload?
* Which departments resolve requests most efficiently?
* What complaint categories generate the most service requests?
* When do complaint volumes peak?
* Which operational areas may require additional resources?

The objective of this project is to transform raw service request records into actionable insights that can support operational decision-making.

---

## Dataset

**Source:** NYC Open Data – 311 Service Requests from 2020 to Present

Key attributes include:

* Complaint Type
* Agency
* Borough
* Created Date
* Closed Date
* Status
* Location Information

---

## Data Cleaning & Preparation

Before analysis, several data quality checks and preprocessing steps were performed:

### Data Quality Validation

* Examined missing values across columns
* Converted date fields into datetime format
* Investigated categorical inconsistencies
* Removed records with invalid timestamps where Closed Date occurred before Created Date

### Feature Engineering

Created new analytical features including:

* Resolution Time (Days)
* Resolution Time (Hours)
* Hour of Request
* Day of Week
* Month
* Year
* Time of Day Category
* Weekend vs Weekday Indicator

These engineered features enabled deeper operational and temporal analysis.

---

## Analysis Performed

### 1. Complaint Volume Analysis

Analyzed:

* Most frequent complaint categories
* Complaint distribution across agencies
* Workload concentration among city departments

  <img width="875" height="547" alt="image" src="https://github.com/user-attachments/assets/db7bf0ac-af6e-43ef-b0e1-894c7101b142" />



### 2. Agency Efficiency Analysis

Developed operational KPIs to compare agency performance:

* Total complaints handled
* Average resolution time
* Median resolution time

This analysis helped identify differences in workload and responsiveness across agencies.

<img width="996" height="547" alt="image" src="https://github.com/user-attachments/assets/7135bdf4-72f4-406d-8de0-9df8acd2a987" />


### 3. Resolution Time Analysis

Examined:

* Distribution of ticket resolution times
* Long-running service requests
* Resolution speed variations between agencies

  <img width="687" height="679" alt="image" src="https://github.com/user-attachments/assets/11b05a0e-4148-4cad-ad13-2d5e87fbeba6" />


### 4. Temporal Trend Analysis

Analyzed complaint activity across:

* Hour of day
* Day of week
* Month
* Year

to identify recurring demand patterns and peak activity periods.

<img width="570" height="600" alt="image" src="https://github.com/user-attachments/assets/2a8a41ea-1860-49eb-b18d-a00501fe9574" />


### 5. Priority Scoring Framework

Created a priority ranking system by combining:

* Complaint volume rankings
* Resolution delay rankings

This framework highlights complaint categories that are both high-volume and slow to resolve.

<img width="1196" height="547" alt="image" src="https://github.com/user-attachments/assets/116d07bb-d97c-4ac2-a803-da35525c2734" />


---

## Key Visualizations

The project includes several analytical visualizations:

### Agency Efficiency Scatter Plot

Compares:

* Number of complaints handled by each agency
* Average resolution time

This helps identify agencies managing high workloads efficiently versus agencies experiencing longer service delays.

### Complaint Volume Analysis

Bar charts were used to identify:

* Most common complaint types
* Agencies handling the largest number of requests

### Resolution Time Distribution

Histograms and distribution plots were used to examine service request closure times and identify potential outliers.

### Temporal Analysis

Visualizations were created to analyze complaint activity by:

* Hour
* Day of Week
* Month
* Year

### Priority Matrix

A ranking-based framework was developed to identify complaint categories that may require operational attention.

---

## Key Findings

### Agency Workload is Highly Concentrated

A small number of agencies handle a disproportionately large share of all service requests, indicating significant workload concentration.

### Resolution Performance Varies Across Agencies

Agencies show noticeable differences in average and median resolution times, suggesting varying levels of operational efficiency and case complexity.

### Complaint Activity Follows Time-Based Patterns

Service requests are not evenly distributed throughout the day or week. Certain periods consistently experience higher complaint volumes.

### High Workload Does Not Always Result in Slow Resolution

Some agencies successfully manage large request volumes while maintaining relatively low resolution times.

### Priority Scoring Highlights Potential Bottlenecks

Combining complaint frequency with resolution delays helps identify service categories that may benefit from process improvements or resource reallocation.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Skills Demonstrated

### Data Analytics

* Exploratory Data Analysis (EDA)
* Data Cleaning & Validation
* Feature Engineering
* KPI Development
* Business Insight Generation

### Python & Pandas

* Data Manipulation
* Aggregation & Grouping
* Datetime Analysis
* Missing Value Handling
* Data Transformation

### Visualization

* Distribution Analysis
* Comparative Analysis
* Trend Analysis
* Performance Benchmarking

---

## Future Improvements

* Analyze the complete dataset rather than a sampled subset
* Build an interactive Power BI/Tableau dashboard
* Perform geospatial hotspot analysis
* Develop complaint volume forecasting models
* Apply statistical testing to compare agency performance

---

## Conclusion

This project demonstrates how raw public-sector operational data can be transformed into actionable business insights through data cleaning, feature engineering, visualization, and KPI analysis.

The workflow closely mirrors real-world responsibilities of Data Analysts and Business Analysts, including performance benchmarking, operational analysis, trend identification, and data-driven decision support.
