# An-Analysis-of-Reported-Crime-Incidents-in-Chicago

## 📌 Project Description
This project uses Big Data processing (Hadoop + Hive) and advanced visualization (Tableau) to analyze 5.8M+ Chicago Police Department crime records (2001–2020).
Our team performed large-scale data ingestion, distributed processing, temporal & geospatial analysis, and pattern discovery using a 3-node Hadoop cluster.

This project demonstrates real-world data engineering + analytics workflow and mirrors enterprise Big Data pipelines.

## 🎯 Objectives / Goals
- Process a multi-gigabyte (1.7GB) Chicago crime dataset using a Hadoop cluster
- Perform distributed querying using Hive & Beeline
- Conduct temporal, spatial, and categorical crime analysis
- Visualize crime trends across locations, months, years, and offense types
- Generate insights to support crime reduction and public safety strategies

## 🧠 Skills Learned
- Big Data processing with Hadoop (HDFS, YARN) and distributed file management  
- Data querying, cleaning, and transformation using HiveQL  
- Large-scale dataset handling (5.8M+ records, 1.7GB CSV)  
- Building tempo-spatial, geospatial, and categorical dashboards in Tableau  
- Identifying long-term trends
- Designing end-to-end data workflows from ingestion → processing → visualization  
- Data storytelling and presenting analytical insights to stakeholders  
- Collaborating in team-based analytics projects and version-controlled environments  

## 🛠 Tools & Technologies
- Hadoop 3.3.3 (HDFS + YARN)
- Hive / Beeline
- Apache Hadoop Distributed Cluster (1 master, 2 workers)
- Tableau
- Power BI (dataset exploration)

## 📐 Methodology
This project followed a full Big Data analytics workflow:
1. Data Acquisition
- Downloaded 1.7GB Chicago PD dataset from Kaggle

2. Data Ingestion
- Uploaded data into HDFS and distributed across 3 nodes

3. Data Processing
- Cleaned, sorted, and queried the dataset using Hive tables
- Performed aggregations, category analysis, and temporal breakdowns

4. Visualization & Insight Generation
- Built dashboards for geo-spatial heatmaps, temporal trends, arrest analysis, and top crime types

5. Insight Interpretation
- Identified high-crime areas, peak months/years, arrest ratios, and emerging trends

## 📊 Outcomes / Results
Using the Tableau charts and Hadoop processing (see project presentation), the project revealed:

🔹 Crime Distribution Findings
- Theft (1.5M cases) and Battery (1.18M) were the two highest incident types.
- Crime locations were dominated by streets, residences, and sidewalks, accounting for the majority of incidents.

🔹 Arrest Trends
- Arrest-to-incident ratios varied dramatically by offense type, as shown in the bar comparison.
- Significant gaps highlighted areas lacking enforcement and requiring deeper policy review.

🔹 Temporal Insights
- Crime peaked in July 2002 (46,012 incidents) — the highest monthly count across the entire dataset.
- Long-term trend shows a consistent decline in crime from 2001–2020, despite seasonal fluctuations.

🔹 Geo-Spatial Insights
- Heatmap showed crime concentrated around:
  - Chicago’s South Side
  - Near West Side
  - Central business areas

## 📁 Repository Structure
- [Project Presentation](Presentation/)
- [Project Report](Project-report/)
- [Project Tutorial](Tutorial/)
