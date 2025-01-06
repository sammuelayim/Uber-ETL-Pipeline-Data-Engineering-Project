# 🚖 Uber Data Analytics | Modern Data Engineering GCP Project  

![architecture](https://github.com/user-attachments/assets/99c3e1f6-0b75-4710-879f-9eedff9b2196)


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

![Architecture Diagram](https://via.placeholder.com/800x400?text=Architecture+Diagram)  

1. **Extract**: Load raw Uber data into Mage.  
2. **Transform**: Apply data cleaning and transformation, creating dimension and fact tables.  
3. **Load**: Store transformed data in Google BigQuery.  
4. **Visualize**: Design dashboards in Looker Studio to generate actionable insights.

  ## Data Model
![data_model](https://github.com/user-attachments/assets/7c714174-6a8b-4630-afdb-c7d95d44d3bc)
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
