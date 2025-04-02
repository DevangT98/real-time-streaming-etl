# Real-Time Data Pipeline with Kafka, Spark & Cassandra | Complete ETL Workflow

This project showcases a complete real-time data engineering pipeline using modern big data tools. It demonstrates how to ingest data from an external API, stream it through Kafka, process it with Spark, and store it in a NoSQL database like Cassandra. The orchestration is handled by Airflow, and everything runs on Docker for easy deployment.

---

## Table of Contents

- [Introduction](#introduction)
- [System Architecture](#system-architecture)
- [What You'll Learn](#what-youll-learn)
- [Technologies](#technologies)
- [Getting Started](#getting-started)

---

## Introduction

This end-to-end project demonstrates how to build a real-time streaming ETL pipeline. You'll learn how to:

- Orchestrate workflows using **Apache Airflow**
- Stream data through **Apache Kafka**
- Process streaming data with **Apache Spark**
- Store results in **Apache Cassandra**
- Containerize the whole environment with **Docker**

The source data is fetched from the public `randomuser.me` API, emulating real-world user events in motion.

---

## System Architecture

![System Architecture](Data%20engineering%20architecture.png)

---

## What You'll Learn

- Setting up and scheduling ETL workflows with **Airflow**
- Real-time streaming with **Kafka + Zookeeper**
- Data transformation using **Spark Structured Streaming**
- Writing transformed data into **Cassandra**
- Using **Docker Compose** to containerize a full data stack

---

## Technologies

- **Apache Airflow** – Workflow orchestration
- **Python** – Used for the API client and Airflow DAGs
- **Apache Kafka** – Real-time messaging system
- **Apache Zookeeper** – Kafka coordination
- **Apache Spark** – Stream processing and transformation
- **Cassandra** – NoSQL database for storing results
- **Docker** – Containerized deployment

---

## Getting Started

Follow these steps to set up the pipeline locally.

### 1. Clone the repository

```bash
git clone https://github.com/DevangT98/real-time-streaming-etl.git

cd real-time-streaming-etl 
```
### 2. Run docker compose
```bash
docker compose up
```
