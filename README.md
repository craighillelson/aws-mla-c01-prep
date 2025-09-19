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