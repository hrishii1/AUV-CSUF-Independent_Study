# AUV-CSUF-Independent_Study

Autonomous Underwater Vehicle (AUV) Research Project 🌊🤖
🚀 Independent Research Study – CSUF, 2024

This project focuses on enhancing underwater object detection and mission analysis using machine learning, real-time data streaming, and cloud computing. By integrating Faster R-CNN, SSD, Apache Kafka, Spark, and AWS, the system improves target identification accuracy and optimizes sonar data processing for low-visibility environments.

📌 Project Overview
🔹 Objective: Develop an AI-driven AUV capable of accurate object detection, anomaly tracking, and performance analysis in underwater environments.
🔹 Key Achievements:
✅ 30% improvement in target identification accuracy using Faster R-CNN & SSD
✅ 25% increase in torpedo hit accuracy
✅ 40% reduction in computation time for image processing using Apache Spark
✅ Efficient real-time sensor streaming via Apache Kafka
✅ Optimized mission analysis using AWS Redshift & Power BI

🛠️ Tech Stack & Tools
Machine Learning & Data Processing
Object Detection Models: 🏷️ Faster R-CNN, SSD

Big Data Processing: 🔥 Apache Spark (PySpark), Kafka

Sensor Data: 📡 Ping 360 Sonar, JSN-SR04T Ultrasonic Sensor

Cloud & Storage
Data Storage: 🗄️ AWS S3

ETL & Querying: 🔗 AWS Glue, Athena

Data Warehousing: 🚀 AWS Redshift

Visualization & Analytics
Power BI Dashboard 📊 (for tracking mission stats, navigation paths, and system performance)

📜 Features & Implementation
✅ 1. Object Detection for Underwater Target Identification
Implemented Faster R-CNN & SSD for detecting underwater targets.

Trained models on sonar and vision datasets.

✅ 2. Data Processing & Streaming
Real-time sonar & sensor data streaming via Apache Kafka.

Apache Spark (PySpark) for large-scale image data transformation.

✅ 3. ETL Pipeline & Data Storage
AWS Glue processes & transforms sonar images.

AWS S3 stores raw & processed sensor data.

AWS Athena enables structured querying on sonar datasets.

✅ 4. Historical Mission Analysis & Optimization
AWS Redshift stores mission logs for model training & analytics.

