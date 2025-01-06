# 🚖 Uber Data Analytics | Modern Data Engineering GCP Project  

![architecture](https://github.com/user-attachments/assets/18443919-970d-47ad-a446-5b00b8b5ed8b)



---


## 📜 Project Overview  
This project showcases a complete **end-to-end data engineering pipeline** for analyzing Uber trip data. By leveraging **modern data engineering tools and cloud technologies**, the pipeline handles data ingestion, transformation, storage, and visualization. This is a comprehensive demonstration of transforming raw data into actionable insights!  

---

### Key Features:  
- **ETL Pipeline**: Developed using [Mage](https://www.mage.ai/) for seamless data ingestion and transformation.  
- **BigQuery Analytics**: Leveraged Google BigQuery for large-scale data storage and analysis.  
- **Looker Studio Dashboard**: Created interactive and insightful dashboards for effective visualization.  

---

## 🏗️ Architecture  

![architecture](https://github.com/user-attachments/assets/18443919-970d-47ad-a446-5b00b8b5ed8b)


1. **Extract**: Load raw Uber data into Mage.

![image](https://github.com/user-attachments/assets/e7cf8190-335a-451b-8455-40fccc770fc3)

2. **Transform**: Apply data cleaning and transformation, creating dimension and fact tables.  

3. **Load**: Store transformed data in Google BigQuery.  

![image](https://github.com/user-attachments/assets/16ff8741-9089-4a6f-97af-dcc0a518a33c)

4. **Visualize**: Design dashboards in Looker Studio to generate actionable insights.

  ## Data Model
  ![Screenshot 2025-01-06 061141](https://github.com/user-attachments/assets/fa0d0ad5-1c8c-421f-ba6d-f23181977be5)

  [Data Model Link Page](https://shorturl.at/Qup6m)

---

## 💻 Technologies Used  


| Tool/Platform           | Purpose                           |
|--------------------------|-----------------------------------|
| **Python**               | Data transformation and scripting|
| **Mage**                 | ETL pipeline development         |
| **Google Cloud Storage** | Storing raw data                 |
| **BigQuery**             | Data warehousing and analysis    |
| **Looker Studio**        | Visualization and dashboarding   |  

---

## 📂 Dataset Details  

- **Source**: NYC Taxi and Limousine Commission Trip Record Data  
  - **Dataset Description**: Includes pickup and drop-off times, trip distances, fare details, and passenger counts.  
  - **More Info**:  
    - Website: [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
    - Data Dictionary: [Yellow Trip Data Dictionary](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)  

---

## 🚀 Project Workflow  

### 1️⃣ **Data Ingestion**  
- Import raw Uber trip data into Mage pipelines for preprocessing.  

### 2️⃣ **Data Transformation**  
- Cleaned and normalized data.  
- Created dimensional tables such as `datetime_dim`, `rate_code_dim`, and `pickup_location_dim`.  
- Built a consolidated `fact_table` for analytics.  

### 3️⃣ **Data Export**  
- Uploaded transformed data to Google BigQuery for querying and analysis.  

### 4️⃣ **Visualization**  
- Designed a **Looker Studio dashboard** featuring:  
  - Filters for Vendor, Payment Type, Rate Code, and Trip Distance.  
  - Revenue metrics, average trip distance, and fare amount.  
  - Interactive maps for pickup and drop-off locations.  

---

## 📊 Dashboard Features  

  ![image](https://github.com/user-attachments/assets/41d8deab-609d-4931-bbb2-640e1ee689ee)

1. **Revenue Insights**: Total revenue by payment type and vendor.  
2. **Trip Metrics**: Average trip distance and fare amount.  
3. **Geographic Trends**: Visualized pickup and drop-off hotspots.  
  ![image](https://github.com/user-attachments/assets/48bf0a8a-349a-4472-a441-6d11c78e2bcb)

🌟 **Live Dashboard Link**: [Uber Analytics Dashboard](https://lookerstudio.google.com/s/nl3slVGcC1g)
---

## 🛠️ How to Reproduce  

### Clone the Repository:  
```bash
git clone https://https://github.com/sammuelayim/Uber-ETL-Pipeline-Data-Engineering-Project.git
