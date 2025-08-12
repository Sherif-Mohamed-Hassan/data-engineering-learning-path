# 6-Month Data Engineering Learning Plan

## Month 1 – Core Foundations

### Week 1 – Python Foundations
- Learn: Variables, data types, loops, functions, modules.
- Learn: File handling (read/write CSV, JSON).
- Resource: Python Crash Course (Eric Matthes)
- Resource: FreeCodeCamp Python course: https://www.youtube.com/watch?v=rfscVS0vtbw
- Project: Script to read CSV file and calculate statistics.

### Week 2 – Python for Data Work
- Learn: pandas, requests, os, sqlalchemy.
- Learn: Environment variables (dotenv).
- Resource: Pandas Docs https://pandas.pydata.org/docs/
- Project: Fetch API data → clean with pandas → save to CSV.

### Week 3 – SQL Mastery
- Learn: SELECT, JOIN, GROUP BY, CTEs, window functions, indexes.
- Resource: SQLBolt https://sqlbolt.com/
- Resource: Mode Analytics SQL Tutorial https://mode.com/sql-tutorial/
- Project: Load NYC taxi data into PostgreSQL and run queries.

### Week 4 – Linux, Git & Automation
- Learn: Shell navigation, permissions, grep, awk, sed, cron jobs.
- Learn: Git basics: branch, commit, merge, PR.
- Resource: Learn Git Branching https://learngitbranching.js.org/
- Project: Automate API → CSV script with cron.

## Month 2 – ETL & Orchestration

### Week 5 – ETL Concepts
- Learn: Batch vs streaming, CSV, JSON, Parquet.
- Project: Python ETL script CSV → pandas → PostgreSQL.

### Week 6 – Airflow Basics
- Learn: DAGs, tasks, scheduling.
- Project: Airflow DAG fetch crypto prices → PostgreSQL.

### Week 7 – Docker
- Learn: Dockerfile, docker-compose.
- Project: Dockerize Airflow + PostgreSQL.

### Week 8 – Advanced Airflow
- Learn: Branching, retries, sensors.
- Project: S3 → pandas → DB pipeline.

## Month 3 – Big Data with Spark

### Week 9 – Spark Basics
- Learn: Spark architecture, RDDs, DataFrames.
- Project: Aggregate NYC taxi dataset.

### Week 10 – Spark SQL
- Learn: Spark SQL, caching, partitioning.
- Project: Analyze logs with Spark SQL.

### Week 11 – PySpark Transformations
- Learn: map, filter, groupBy, joins.
- Project: CSV → Spark → Parquet → PostgreSQL.

### Week 12 – Spark Optimization
- Learn: Partitioning, avoiding shuffles.
- Project: Optimize Spark pipeline.

## Month 4 – Cloud Data Engineering

### Week 13 – AWS Basics
- Learn: S3, IAM, EC2.
- Project: Upload & read datasets from S3.

### Week 14 – AWS Data Tools
- Learn: Glue ETL, Athena queries.
- Project: Process S3 data with Glue → Athena.

### Week 15 – Data Warehousing
- Learn: Redshift basics, COPY commands.
- Project: Load S3 → Redshift.

### Week 16 – Serverless ETL
- Learn: Lambda functions for ETL.
- Project: Auto-process S3 file uploads with Lambda.

## Month 5 – Real-Time Data

### Week 17 – Kafka Basics
- Learn: Producers, consumers, topics.
- Project: Producer sends random events, consumer logs them.

### Week 18 – Kafka + Spark Streaming
- Learn: Structured Streaming API.
- Project: Kafka → Spark → PostgreSQL.

### Week 19 – Real-Time Analytics
- Learn: Sliding windows, watermarking.
- Project: Real-time dashboard with BI tool.

### Week 20 – Reliability
- Learn: Offsets, retries, exactly-once semantics.
- Project: Error handling & monitoring for streaming pipeline.

## Month 6 – Portfolio & Job Prep

### Week 21 – Data Modeling
- Learn: Star vs Snowflake schemas.
- Project: Design DW schema for e-commerce.

### Week 22 – CI/CD & Testing
- Learn: GitHub Actions, pytest.
- Project: Add CI/CD to pipeline.

### Week 23 – Monitoring & Governance
- Learn: Airflow alerts, data quality checks.
- Project: Monitoring for Airflow project.

### Week 24 – Final Portfolio & Prep
- Finalize 3 portfolio projects.
- Practice SQL & Python interview questions.

