## **Data Engineering Easter Holiday Challenge.**

### **Problem Statement: YouTube Channel Analytics Dashboard**
In the creator economy, YouTube content creators produce vast amounts of video content and rely heavily on performance metrics to guide their strategies. However, YouTube's native dashboard can be limited in flexibility, depth, and custom visualization. Creators often lack a centralized, customizable platform to analyze how their videos perform over time, track audience engagement trends, and gain insights into what type of content works best.

---

#### The Problem

Creators need an **automated analytics data pipeline** that:
- Periodically pulls video-level performance data from the **YouTube API**
- Cleans, aggregates, and stores that data in a structured format.
- Delivers **actionable insights** like:
  - Growth trends (subscribers, views, likes).
  - Most engaging videos over time.
  - Weekly or monthly performance summaries.
  - Content strategy suggestions.

Manual data collection and analysis is error-prone, inconsistent, and not scalable as a channel grows.

---

#### Objective

To build a **data engineering pipeline** that automates the collection, processing, and visualization of YouTube channel data for a creator or content strategist. The solution should:

- ✅ **Extract** video metadata, views, likes, comments, and publish times from the YouTube API  
- ✅ **Transform** and enrich this data using Apache Spark (e.g., convert dates, calculate engagement metrics)  
- ✅ **Load** cleaned and aggregated data into a PostgreSQL database. (If you don't access to our cloud base PostgreSQL database, you can create an account with Aiven, create a free postgreSQL service, and putll you data there.   
- ✅ **Schedule** the entire process daily and weekly using Apache Airflow. 
- ✅ **Display** key analytics on a Grafana dashboard to support decision-making. We have Grafana installed on the ubuntu server 128.85.32.87. 
---

#### Key Questions the Dashboard Should Answer
- 📈 How has my channel grown over time? (Pick a specicif channel to work with example, youtube.com/@cristiano or youtube.com/@luxtechacademy. 
- 🎥 Which videos perform best by engagement (likes/comments/views)?
- ⏱️ What days and times work best for publishing content?
- 🧑‍🤝‍🧑 What audience patterns or behaviors can we spot?
- 📅 Can I receive automated summaries of channel activity every week?
---

#### Expected Outcomes
- A self-updating PostgreSQL table with structured video performance data  
- A scheduled Airflow DAG that syncs new data  daily and weekly  
- A clean, interactive Grafana dashboard that provides creators with:
  - Time series analytics  
  - Engagement heatmaps  
  - Top content breakdown  
  - Summary statistics
 
#### Tools and Technologies. 
- Python
- PostgreSQL
- Apache Airflow
- Apache Spark
- Grafana
- Git and GitHub
- You can leverage Ubuntu server 128.85.32.87, the user and the password were shared in the class. 
 
Project Duration: From 18th April 2025 to 26th April 2025. 
- Daily standups everyday from Teuday, 9:30 to 10:00 PM EAT
- You work should be tracked on a  GitHub Repository and the luink shared during the first stand up.
- Write an article documenting the whole proccess how you solved the end to end project.

Please request for help anytime you are stuck at 0796448232 or email dataengineering@luxdevhq.com  
