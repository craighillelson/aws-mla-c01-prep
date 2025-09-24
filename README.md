# AWS Certified Machine Learning Engineer MLA-C01 Notes

# Domains
- **Domain 1**: Data Preparation for Machine Learning (ML) (28% of scored content)
- **Domain 2**: ML Model Development (26% of scored content) 
- **Domain 3**: Deployment and Orchestration of ML Workflows (22% of scored content) 
- **Domain 4**: ML Solution Monitoring, Maintenance, and Security (24% of scored content)

# Services
- [Amazon Data Firehose](https://aws.amazon.com/kinesis/data-firehose/)
- [AWS DataSync](https://aws.amazon.com/datasync/)
- [AWS Glue](https://aws.amazon.com/glue/)
- [Amazon SageMaker](https://aws.amazon.com/sagemaker/)

# Notes from AWS Certified Machine Learning Engineer Study Guide
# Chapter 1: Introduction to Machine Learning

## Knowledge
- contextuality
- applicability
- experience-based
- dynamism

## ML Lifecycle
1. define ml problem
1. collect data
1. process data
1. choose algorithm
1. train model
1. evaluate model
1. deploy model
1. derive inference
1. monitor model

## Structure of a Neural Network
- neuron
- input layer
- hidden layers
- output layer

## Types of Neural Networks
- **Artificial Neural Networks (ANN)**: capable of learning from data by adjusting the weights of connections between neurons to minimize error
- **Deep Neural Networks**: able to model more complex patterns in the data
- **Convolutional Neural Networks (CNN)**: designed for processing grid-like data such as images
- **Recurrent Neural Networks (RNN)**: tailored for sequential data

# Chapter 2: Data Ingestion and Storage
## Ingesting and Storing Data
**AWS Storage Systems**
- **Storage Abstractions**: Data Lake, Data Lakehouse, Data Platform, Cloud Data Warehouse
- **Storage Systems**: HDFS, EMRFS, Object Storage, Block Storage, Streaming Storage, Cache
- **Storage Low-Level Components**: HDD, SSD, RAM, CPU, Networking, Compression, Serialization

### Data Formats and Ingestion Techniques
**Data Formats**
- CSV
- JSON
- Apache Parquet
- Apache Optimized Row Columnar (ORC)
- Apache Avro
- RecordIO

**Benefits of Columnar Formats**
- column-specific compression
- column-specific encoding and compression
- queries only access relevant columns, improving performance

## AWS DataSync Use Cases
- discover data
- migrate data
- archive cold data
- replicate data
- transfer data for timely in-cloud processing

## AWS Glue Use Cases
- complex ETL pipeline development
- data discovery
- support for data processing frameworks
- simplified data engineering experience

## Amazon Simple Storage Service (S3)
**S3 Storage Classes**
- S3 Standard: frequently accessed data, low latency, high throughput
- S3 Intelligent-Tiering: data with unknown or changing access patterns, automatic cost savings
- S3 Standard-IA (Infrequent Access): long-lived but infrequently accessed data
- S3 One Zone-IA: infrequently accessed data that does not require multiple Availability Zone
- S3 Glacier Instant Retrieval: long-term archive data that requires milliseconds retrieval
- S3 Glacier Flexible Retrieval: long-term archive data that requires minutes to hours retrieval
- S3 Glacier Deep Archive: long-term archive data that is accessed once or twice a year
- S3 Outposts: data that needs to remain on-premises for latency or data residency requirements
### Amazon Athena
- serverless interactive query service
- uses standard SQL
## Amazon Elastic File System (EFS)
## Amazon FSx for Lustre
## Amazon FSx for NetApp ONTAP
## Amazon FSx for Windows File Server
## Amazon FSx for OpenZFS
## Amazon Elastic Block Storage (EBS)
## Amazon Relational Database Service (RDS)
## Amazon DynamoDB

# Chapter 3: Data Transformation and Feature Engineering
## Understanding Feature Engineering
- **Categorical data**: finite number of distinct categories
- **Numerical data**: anything that can be represented as a number
    - **Discrete**: countable values
    - **Continuous**: any value within a range
- **Textual data**: books, social media posts, articles, etc.
- **Image data**: pixel values
- **Time series data**: collection of observations or measurements recorded over regular intervals of time
### Defining Features
### Selecting Features for Model Training
## Data Cleaning and Transformation
- **Managing Missing Values**
    - **Collect**
    - **Impute**
    - **Drop**
- **Detecting and Treating Outliers**
    - **Delete**
    - **Logarithmic Transform**
    - **Impute**
- **Performing Deduplication**
- **Standardizing and Reformatting**
    - **Load Data**
    - **Standardize Data**
    - **Export Data**
    - **Create AWS Glue job**
    - **Load clean data**
- **Removing Noise and Errors**

# Chapter 4: Model Selection

# Chapter 5: Model Training and Evaluation

# Terms
- **Overfitting**: model learns the training data too well, including noise and outliers, leading to poor generalization on new data
- **Scaling**: adjusting the range or distribution of features
