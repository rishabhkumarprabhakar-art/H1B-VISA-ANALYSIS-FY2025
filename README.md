# 📊 H-1B Visa Performance Metrics — FY2025

## 📌 Project Overview
This project presents a comprehensive analysis of the H-1B visa program for Fiscal Year 2025, built on a dataset of over **453,000 applications**.

The dashboard provides a macro-level view of employer demand, job roles, salary distribution, and geographic trends, enabling deeper insights into the U.S. labor market for high-skilled foreign workers.

---

## 🎯 Objectives
- Analyze approval trends and case outcomes  
- Identify top job roles and sponsoring employers  
- Explore salary distribution across occupations  
- Map geographic concentration of H-1B employment  
- Deliver an interactive dashboard for decision-making  

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Value |
|------|------|
| Total Applicants | **453K** |
| Total Approvals | **420K** |
| Total Denials | **2,807** |
| Approval Rate | **92.78%** |

---

## 🔍 Key Insights

### 💼 Top Job Roles
- **Software Engineers** dominate with ~21K cases  
- Followed by:
  - Software Developers (~16K)  
  - Senior Software Engineers (~6K)  

👉 Indicates strong demand for tech talent in software development  

---

### 🏢 Leading Employers
- Amazon — 11.1K  
- Cognizant — 9.0K  
- Microsoft — 7.1K  
- Tata Consultancy Services & Ernst & Young also rank highly  

👉 Large multinational and tech firms are primary visa sponsors  

---

### 💰 Salary Insights
- Highest wages observed in specialized healthcare roles:
  - Cardiology / Orthopedics (~$500K)  
- Tech roles show high volume but relatively moderate salary bands  

👉 Highlights a value vs. volume divide in labor demand  

---

### 🌍 Geographic Trends
- New York leads with ~25K approvals  
- Other major hubs:
  - Austin (~11K)  
  - Seattle (~11K)  
  - San Francisco & San Jose (~8K each)  

👉 H-1B jobs remain concentrated in major tech and economic hubs  

---

### 🗺️ Geospatial Distribution
- Interactive map shows global spread of worksite cities  
- Strong clustering in North America and coastal U.S. regions  

---

## 🧠 The Economic Narrative
> This analysis highlights a shifting U.S. economy. While software engineering roles dominate in volume, the highest wages are concentrated in specialized healthcare professions.  
>
> Additionally, despite the rise of remote work, H-1B employment remains heavily clustered in traditional economic and technology hubs such as New York, Seattle, and Austin.

---

## 🛠️ Technical Stack

| Layer | Tools Used |
|------|-----------|
| Data Source | U.S. Department of Labor (OFLC Disclosure Data) |
| Data Cleaning | SQL (data transformation, filtering, normalization) |
| Data Modeling | Power BI (DAX measures, relationships) |
| Visualization | Power BI Dashboard |
| Optional Processing | Python (Pandas) for exploratory analysis |

---

## ⚙️ Data Pipeline

1. **Raw Data Ingestion**
   - Imported large CSV dataset from OFLC  

2. **Data Cleaning (SQL)**
   - Removed null/invalid records  
   - Standardized job titles & employer names  
   - Filtered relevant case statuses  
   - Structured data for analysis  

3. **Data Modeling (Power BI)**
   - Built relationships  
   - Created DAX measures:
     - Approval Rate %
     - Total Cases  
     - Employer Rankings  

4. **Dashboard Development**
   - KPI cards  
   - Job & employer ranking visuals  
   - Salary distribution charts  
   - Interactive map  

---

## 📸 Dashboard Preview
![Dashboard Preview]()

---

## 🚀 How to Use
1. Clone the repository  
2. Open the `.pbix` file in Power BI Desktop  
3. (Optional) Run SQL scripts to reproduce cleaned dataset  
4. Use filters to explore:
   - Case Status  
   - Job Titles  
   - Employers  
   - Locations  

---

## 📊 Features
- Interactive filtering by case status  
- Employer & job ranking visuals  
- Salary comparison across occupations  
- Geographic heatmap of job locations  
- Clean and executive-friendly layout  

---

## 🔮 Future Improvements
- Add year-over-year trend analysis  
- Build predictive approval models  
- Integrate real-time visa data updates  
- Enhance role classification using NLP
