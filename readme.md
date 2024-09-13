# CRUD Operations with Multiple Databases

## Overview

This repository demonstrates the implementation of CRUD (Create, Read, Update, Delete) operations across six different types of databases: Relational, Document, Vector, Graph, Key-Value, and Time-Series. Each database is chosen to highlight its unique strengths and capabilities in handling specific types of data and use cases.


## Properties of these Databases?

- *MySQL:* Fast, reliable, and suitable for read-heavy applications with robust ACID support.
- *MongoDB:* Flexible schema, ideal for unstructured data like product catalogs.
- *Pinecone:* Specialized in vector searches, perfect for semantic search applications.
- *Neo4j:* Optimized for handling complex relationships and hierarchical data.
- *Redis:* In-memory storage, providing extremely fast session management.
- *InfluxDB:* Efficient handling of time-series data, great for monitoring and metric storage.


### Environment Configuration

To securely manage sensitive information like database credentials, create a .env file in the project root directory. This file should contain the following environment variables:

# MySQL Configuration
MYSQL_HOST=127.0.0.1
MYSQL_USER=root
MYSQL_PASSWORD=your_mysql_password
MYSQL_DB=your_mysql_database

# MongoDB Configuration
MONGODB_URI=mongodb://localhost:27017/
MONGODB_DB=shop
MONGODB_COLLECTION=products

# Neo4j Configuration
NEO4J_URI=neo4j+s://your_neo4j_uri
NEO4J_USER=neo4j
NEO4J_PASSWORD=your_neo4j_password

# Pinecone Configuration
PINECONE_API_KEY=your_pinecone_api_key

# Redis Configuration
REDIS_HOST=your_redis_host
REDIS_PORT=6379
REDIS_PASSWORD=your_redis_password

# InfluxDB Configuration
INFLUXDB_URL=https://your_influxdb_url
INFLUXDB_TOKEN=your_influxdb_token
INFLUXDB_ORG=your_org_name
INFLUXDB_BUCKET=your_bucket_name


