\# 📈 Stock Market Real-Time Data Pipeline using Apache Kafka & AWS



\## 📌 Project Overview



This project demonstrates an end-to-end real-time data engineering pipeline that streams stock market data using \*\*Apache Kafka\*\* and stores it in \*\*Amazon S3\*\*. The data is automatically cataloged using \*\*AWS Glue\*\* and queried using \*\*Amazon Athena\*\*.



The objective of this project is to simulate a real-world streaming architecture used in industries such as finance, e-commerce, and IoT.



\---



\## 🏗️ Architecture



```

CSV Dataset
      │
      ▼
Python Producer
      │
      ▼
Apache Kafka
      │
      ▼
Python Consumer
      │
      ▼
Amazon S3
      │
      ▼
AWS Glue
      │
      ▼
Athena
```



\---



\## 🚀 Technologies Used



\- Python

\- Apache Kafka

\- Amazon EC2

\- Amazon S3

\- AWS Glue

\- Amazon Athena

\- Pandas

\- s3fs

\- Jupyter Notebook



\---



\## ✨ Features



\- Streams stock market records in real time.

\- Uses Apache Kafka as a distributed messaging system.

\- Stores streaming data in Amazon S3.

\- Automatically discovers schema using AWS Glue.

\- Queries data directly from S3 using Athena.

\- Demonstrates an end-to-end cloud-based data pipeline.



\---



\## 📂 Project Structure



```

Stock-Market-Real-Time-Data-Pipeline-using-Kafka/

│

├── Kafka-Producer.ipynb

├── Kafka-Consumer.ipynb

├── indexProcessed.csv

├── requirements.txt

├── README.md

└── .gitignore

```



\---



\## ⚙️ Installation



1\. Clone the repository



```bash

git clone <repository-url>

```



2\. Install dependencies



```bash

pip install -r requirements.txt

```



3\. Configure Kafka Broker.



4\. Start ZooKeeper and Kafka.



5\. Run Kafka-Producer.ipynb.



6\. Run Kafka-Consumer.ipynb.



\---



\## 📊 Dataset



Stock Market Historical Dataset



Columns include:



\- Index

\- Date

\- Open

\- High

\- Low

\- Close

\- Adjusted Close

\- Volume



\---



\## 📈 Future Improvements



\- Apache Spark Streaming

\- Apache Airflow Integration

\- Docker Deployment

\- Kubernetes

\- AWS Lambda

\- Amazon QuickSight Dashboard



\---



\## 👨‍💻 Author



Mohd Subhan

