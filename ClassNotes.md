# Data Engineering Class

## Data Engineering on Google Cloud - 5 Days
    Module 1: Introduction to Data Engineering
    Module 2: Building a Data Lake
    Module 3: Building a Data Warehouse
    Module 4: Introduction to Building Batch Data Pipelines,
    Module 5: Executing Spark on Cloud Dataproc
    Module 6: Serverless Data Processing with Cloud Dataflow
    Module 7: Manage Data Pipelines with Cloud Data Fusion and Cloud Composer
    Module 8: Introduction to Processing Streaming Data
    Module 9: Serverless Messaging with Cloud Pub/Sub
    Module 10: Cloud Dataflow Streaming Features
    Module 11: High-Throughput BigQuery and Bigtable Streaming Features
    Module 12: Advanced BigQuery Functionality and Performance
---

## Links 
#### Tutorials and demos
- https://github.com/GoogleCloudPlatform/training-data-analyst

## Admin Stuff
- class Hours 10-6 EDT Last hour  QA discussions
- Lunch 12-1 
- Two breaks 15 min 
- Hands on 
- Materials - github repo

## Introductions
- Name you prefer 
- Area of expertise. 
- Background data engineering, data science, google and other cloud
- What do you want the course to do for you?

## Data Implementation Models
- Hierarchical model
- Network model
- Relational Model
    - Data model - schema
    - Transactional process CRUD 
    - Protect from corruption
    - OLTP - online transaction processing
    - Most queries tend to be the same
    - Row oriented data
- Data warehouse
    - OLAP - online analytic processing
    - Dimensional model
    - Read only queries
    - Schema required
- Nosql data bases
    - Not only SQL
    - Key-value store
    - Document store
        - Semistructure - email
    - Columnar formats
        - AVRO, ORC PARQUET
## Data Modeling
    - what does the data look, what does it mean, how is it organized
    - https://www.dama.org/cpages/home

## Data Prep
    - Data managment - data as corporate ase
    - Data compiant - 
 ## Data use
    - Data Analyst - What can we learn from the data
    - Business Intel - How can tune our business
    - Data Mining / ML - cluster analysis
    - MLOps 
## Cloud 101
- DevOps, Infrastructure as code
- Google Cloud
    - Colossus - Internal Storge
    - Jupiter - petabit network

## Class Project
- Global Warming
- 
 ## Data Quality
 - Fnu Katheswaranath 
 - Joashua Rodson
 - Amber Roddottir

---


- https://cloud.google.com/blog/products/data-analytics/whats-happening-bigquery-adding-speed-and-flexibility-10x-streaming-quota-cloud-sql-federation-and-more
- https://cloud.google.com/dataproc

---

## NoSQL
1. Key value store
2. Document database - semi structure
    - MongoDB
3. Columnar Storage 
    - Sparce data set 

```bash

index colum  [ca: [....], cz: [.....]]
```

- Data Drift 
- Concept drift 

---

Nature based
    - emulating natural behaviours
    - emulate natural cognition
Rational AI
    - developing ML models that are use
    - Rational actors
- Datraproc
    - specificy parameter for a hdfs cluster

---
# Resources

## Public Examples Repository
- https://github.com/GoogleCloudPlatform/training-data-analyst
- There are other repos in github.com/GoogleCloudPlatform that you might want to explore as well

## Coursera
- Google offers their certification training through Coursera as a series of courses.  Info on that is here.
- https://www.coursera.org/specializations/gcp-data-machine-learning
  
## Practice exam
- Free example exam questions for the certification are at:
- https://gcp-examquestions.com/course/google-professional-cloud-data-engineer-practice-exam/
- https://www.vmexam.com/google/google-gcp-pde-certification-exam-sample-questions

# References
The following are the all references pulled from the class materials

## Module 1-01 - Data Engineering
- https://cloud.google.com/architecture/build-a-data-lake-on-gcp#cloud-storage-as-data-lake
- Demo: https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/courses/data-to-insights/demos/external-data-query.sql
- https://cloud.google.com/bigquery/docs/monitoring
- https://www.youtube.com/watch?v=BbFCbWIn-as&t=461s
- Demo: https://cloud.google.com/dlp/demo/#!/
- https://www.youtube.com/watch?v=kGVDFzIbhco&t=1451s
  
## Module 1-02 - Building a Data Lake
- https://cloud.google.com/solutions/data-lake/
- https://www.youtube.com/watch?v=l5I0knEcH4I
- https://cloud.google.com/blog/products/data-analytics/keep-parquet-and-orc-from-the-data-graveyard-with-new-bigquery-features
- https://cloud.google.com/bigquery/docs/external-data-cloud-storage
- https://cloud.google.com/bigquery/docs/hive-partitioned-queries-gcs
- https://cloud.google.com/bigquery/docs/hive-partitioned-loads-gcs
- https://cloud.google.com/sql/docs/mysql/high-availability
  
## Module 1-03 Building a data warehouse
- Demo: https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/courses/data-engineering/demos/bigquery_scale.md
- https://cloud.google.com/bigquery/docs/managing-table-schemas
- https://www.youtube.com/watch?v=K8A6_G3DTTs
- https://cloud.google.com/blog/products/data-analytics/new-persistent-user-defined-functions-increased-concurrency-limits-gis-and-encryption-functions-and-more
- Demo: https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/quests/bq-optimize/demos/code/information_schema.sql
- https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf
- https://cloud.google.com/blog/products/data-analytics/whats-happening-bigquery-adding-speed-and-flexibility-10x-streaming-quota-cloud-sql-federation-and-more

## Module 2-01 Introduction to Building Batch Data Pipelines
- Demo: https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/courses/data-engineering/demos/simple_healthcheck.md
  
## Module 2-02 Batch Processing of Data with Spark and Hadoop on GCP_M2 - Executing Spark on Cloud Dataproc
- https://cloud.google.com/dataproc/docs/concepts/configuring-clusters/init-actions#examplewzxhzdk15staging_binaries
- https://cloud.google.com/dataproc/docs/guides/create-cluster
- https://cloud.google.com/dataproc/docs/concepts/configuring-clusters/cluster-properties
- https://cloud.google.com/dataproc/docs/guides/dataproc-images
- https://cloud.google.com/dataproc/docs/concepts/jobs/life-of-a-job
- https://cloud.google.com/dataproc/docs/concepts/jobs/restartable-jobs
- https://cloud.google.com/dataproc/docs/guides/monitoring
- https://cloudplatform.googleblog.com/2015/06/A-Look-Inside-Googles-Data-Center-Networks.html
- https://cloud.google.com/dataproc/docs/concepts/workflows/overview
- https://cloud.google.com/dataproc/docs/guides/creating-managing-labels
- https://cloud.google.com/dataproc/docs/concepts/configuring-clusters/autoscaling

## Module 2-03 Serverless Data Processing with Cloud Dataflow.
- https://github.com/apache/beam/blob/master/sdks/python/apache_beam/examples/streaming_wordcount.py
- https://cloud.google.com/dataflow/docs/concepts/dataflow-templates
- https://github.com/GoogleCloudPlatform/DataflowTemplates
- https://cloud.google.com/dataflow/docs/guides/templates/provided-templates
  
## Module 2-04 Manage Data Pipelines with Cloud Data Fusion and Cloud Composer
- https://cloud.google.com/composer/docs/how-to/using/writing-dags#gcp_name_operators
- https://airflow.apache.org/docs/apache-airflow/stable/integration.html#gcp
- https://github.com/GoogleCloudPlatform/python-docs-samples/blob/main/composer/workflows/bq_notify.py
- https://cloud.google.com/composer/docs/how-to/using/triggering-with-gcf
- https://github.com/GoogleCloudPlatform/training-data-analyst/tree/master/courses/data-engineering/demos
  
## Module 3-01 Introduction to Processing Streaming Data
- None
  
## Module 3-02 Serverless Messaging with Cloud Pub_Sub
- None

## Module 3-03 Cloud Dataflow Streaming Features
- https://beam.apache.org/documentation/programming-guide/#windowing-basics
  
## Module 3-04 High-Throughput BigQuery and Bigtable Streaming Features
- https://cloud.google.com/bigquery/docs/streaming-data-into-bigquery
- https://cloud.google.com/blog/products/data-analytics/whats-happening-bigquery-adding-speed-and-flexibility-10x-streaming-quota-cloud-sql-federation-and-more
- https://cloud.google.com/bigtable/docs/schema-design
- https://cloud.google.com/bigtable/docs/performance
- https://cloud.google.com/bigtable/docs/replication-overview

## Module 3-05 Advanced BigQuery Functionality and Performance
- https://cloud.google.com/bigquery/docs/best-practices-performance-compute
- https://cloud.google.com/bigquery/docs/clustered-tables#automatic_re-clustering
- https://cloud.google.com/blog/products/data-analytics/whats-happening-bigquery-adding-speed-and-flexibility-10x-streaming-quota-cloud-sql-federation-and-more
- https://cloud.google.com/bigquery/pricing
  
## Module 4-01 Introduction to Analytics and AI
- https://cloud.google.com/blog/products/gcp/empowering-businesses-and-developers-do-more-ai 
- https://cloudplatform.googleblog.com/2018/07/predict-your-future-costs-with-google-cloud-billing-cost-forecast.html
  
## Module 4-02 Prebuilt ML model APIs for Unstructured Data
- https://www.youtube.com/watch?v=BwWg__HVfsM&t=281s
- https://cloud.google.com/blog/products/gcp/google-cloud-machine-learning-now-open-to-all-with-new-professional-services-and-education-programs
  
## Module 4-03 Big Data Analytics with Cloud AI Platform Notebooks
- None

## Module 4-04 Production ML Pipelines with Kubeflow
- None

## Module 4-05 Custom Model building with SQL in BigQuery ML
- Demo: https://github.com/GoogleCloudPlatform/training-data-analyst/blob/master/courses/data-engineering/demos/predict_taxi_bigqueryml.md
  
## Module 4-06  Custom Model building with Cloud AutoML
- https://cloud.google.com/natural-language/automl/docs/evaluate

