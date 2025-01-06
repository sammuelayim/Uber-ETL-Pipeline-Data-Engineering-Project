# 🚖 Uber Data Analytics | Modern Data Engineering GCP Project
📜 Project Overview
This project showcases a complete end-to-end data engineering pipeline for analyzing Uber trip data. By leveraging modern data engineering tools and cloud technologies, the pipeline handles data ingestion, transformation, storage, and visualization. This is a comprehensive demonstration of transforming raw data into actionable insights!

Key Features:

ETL Pipeline: Developed using Mage for seamless data ingestion and transformation.
BigQuery Analytics: Leveraged Google BigQuery for large-scale data storage and analysis.
Looker Studio Dashboard: Created interactive and insightful dashboards for effective visualization.
🏗️ Architecture

Extract: Load raw Uber data into Mage.
Transform: Apply data cleaning and transformation, creating dimension and fact tables.
Load: Store transformed data in Google BigQuery.
Visualize: Design dashboards in Looker Studio to generate actionable insights.
💻 Technologies Used
Tool/Platform	Purpose
Python	Data transformation and scripting
Mage	ETL pipeline development
Google Cloud Storage	Storing raw data
BigQuery	Data warehousing and analysis
Looker Studio	Visualization and dashboarding
📂 Dataset Details
Source: NYC Taxi and Limousine Commission Trip Record Data
Dataset URL: Uber Data
Dataset Description: Includes fields such as pickup and drop-off times, trip distances, fare details, and passenger counts.
More Info:
Website: NYC TLC Trip Record Data
Data Dictionary: Yellow Trip Data Dictionary
🚀 Project Workflow
1️⃣ Data Ingestion
Import raw Uber trip data into Mage pipelines for preprocessing.
2️⃣ Data Transformation
Cleaned and normalized data.
Created dimensional tables such as datetime_dim, rate_code_dim, and pickup_location_dim.
Built a consolidated fact_table for analytics.
3️⃣ Data Export
Uploaded transformed data to Google BigQuery for querying and analysis.
4️⃣ Visualization
Designed a Looker Studio dashboard featuring:
Filters for Vendor, Payment Type, Rate Code, and Trip Distance.
Revenue metrics, average trip distance, and fare amount.
Interactive maps for pickup and drop-off locations.
📊 Dashboard Features

Revenue Insights: Total revenue by payment type and vendor.
Trip Metrics: Average trip distance and fare amount.
Geographic Trends: Visualized pickup and drop-off hotspots.
🛠️ How to Reproduce
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/uber-data-engineering.git
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Configure Settings:

Edit the io_config.yaml file to connect Mage with BigQuery.
Run the Pipeline:

Use Mage to process the raw data into analytics-ready tables.
View the Dashboard:

Connect Looker Studio to BigQuery and import the dataset.
🌟 Future Enhancements
Real-Time Data Ingestion: Implement streaming data pipelines for live updates.
Machine Learning: Add predictive analytics for trip demand forecasting or fraud detection.
Advanced Visualizations: Include dynamic charts, heatmaps, and trendlines for deeper insights.
📝 Acknowledgments
This project was inspired by Darshil Parmar's excellent tutorial.
You can view the original tutorial here: YouTube Video.

🤝 Contributions
We welcome contributions to enhance this project!

Explore the open-source Mage AI tool.
Submit issues or pull requests to improve this repository.
📷 Gallery
Add project screenshots or architecture diagrams here.

🔗 Explore the Project
GitHub Repository: Uber Data Analytics Pipeline
Live Dashboard: Uber Analytics Dashboard
