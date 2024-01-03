# Data Engineering Zoomcamp

## Syllabus

* [Module 1: Introduction & Prerequisites](#module-1-introduction--prerequisites)
* [Module 2: Workflow Orchestration](#module-2-workflow-orchestration)
* [Module 3: Data Warehouse](#module-3-data-warehouse)
* [Module 4: Analytics Engineering](#module-4-analytics-engineering)
* [Module 5: Batch processing](#module-5-batch-processing)
* [Module 6: Streaming](#module-6-streaming)
* [Module 7: Project](#module-7-project)

***

### [Module 1: Introduction & Prerequisites](1_basics_n_setup)

* Course overview
* Introduction to GCP
* Docker and docker-compose
* Running Postgres locally with Docker
* Setting up infrastructure on GCP with Terraform
* Preparing the environment for the course
* Homework

[More details](1_basics_n_setup)


### [Module 2: Workflow Orchestration](2_workflow_orchestration/)

* Data Lake
* Workflow orchestration
* Workflow orchestration with Mage
* Homework

[More details](2_workflow_orchestration/)


### [Module 3: Data Warehouse](3_data_warehouse)


* Data Warehouse
* BigQuery
* Partitioning and clustering
* BigQuery best practices
* Internals of BigQuery
* Integrating BigQuery with Airflow
* BigQuery Machine Learning

[More details](week_3_data_warehouse)


### [Module 4: Analytics engineering](4_analytics_engineering/)

* Basics of analytics engineering
* dbt (data build tool)
* BigQuery and dbt
* Postgres and dbt
* dbt models
* Testing and documenting
* Deployment to the cloud and locally
* Visualizing the data with google data studio and metabase


[More details](4_analytics_engineering)


### [Module 5: Batch processing](5_batch_processing)

* Batch processing
* What is Spark
* Spark Dataframes
* Spark SQL
* Internals: GroupBy and joins

[More details](5_batch_processing)

### [Module 6: Streaming](6_stream_processing)

* Introduction to Kafka
* Schemas (avro)
* Kafka Streams
* Kafka Connect and KSQL

[More details](6_stream_processing)


### [Module 7: Project](7_project)

Putting everything we learned to practice

* Week 7 and 8: working on your project
* Week 9: reviewing your peers

[More details](7_project)

### Course UI

Alternatively, you can access this course using the provided UI app, the app provides a user-friendly interface for navigating through the course material. 

* Visit the following link: [DE Zoomcamp UI](https://dezoomcamp.streamlit.app/)

![dezoomcamp-ui](https://github.com/DataTalksClub/data-engineering-zoomcamp/assets/66017329/4466d2bc-3728-4fca-8e9e-b1c6be30a430)

### Asking for help in Slack

The best way to get support is to use [DataTalks.Club's Slack](https://datatalks.club/slack.html). Join the [`#course-data-engineering`](https://app.slack.com/client/T01ATQK62F8/C01FABYF2RG) channel.

To make discussions in Slack more organized:

* Follow [these recommendations](asking-questions.md) when asking for help
* Read the [DataTalks.Club community guidelines](https://datatalks.club/slack/guidelines.html)

## Overview

### Architecture diagram
<img src="images/architecture/arch_2.png"/>

### Technologies
* *Google Cloud Platform (GCP)*: Cloud-based auto-scaling platform by Google
  * *Google Cloud Storage (GCS)*: Data Lake
  * *BigQuery*: Data Warehouse
* *Terraform*: Infrastructure-as-Code (IaC)
* *Docker*: Containerization
* *SQL*: Data Analysis & Exploration
* *Mage*: Workflow Orchestration
* *dbt*: Data Transformation
* *Spark*: Distributed Processing
* *Kafka*: Streaming


### Prerequisites

To get the most out of this course, you should feel comfortable with coding and command line
and know the basics of SQL. Prior experience with Python will be helpful, but you can pick
Python relatively fast if you have experience with other programming languages.

Prior experience with data engineering is not required.



## Instructors

- [Ankush Khanna](https://linkedin.com/in/ankushkhanna2)
- [Victoria Perez Mola](https://www.linkedin.com/in/victoriaperezmola/)
- [Alexey Grigorev](https://linkedin.com/in/agrigorev)

## Tools

For this course, you'll need to have the following software installed on your computer:

* Docker and Docker-Compose
* Python 3 (e.g. via [Anaconda](https://www.anaconda.com/products/individual))
* Google Cloud SDK
* Terraform

See [Module 1](week_1_basics_n_setup) for more details about installing these tools