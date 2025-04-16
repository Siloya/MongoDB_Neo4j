#  NoSQL Data Management with MongoDB, Neo4j and Cassandra

This repository contains a series of practical assignments for managing structured and graph-based data using NoSQL technologies: **MongoDB**, **Neo4j**, and **Apache Cassandra**. The projects involve handling pharmaceutical data, restaurant datasets, and transportation networks with a focus on document, graph, and column-oriented models.

##  Contents

### 1. `MongoDB_Neo4j_Pharmacy`
A complete application for managing pharmaceutical data using:
- **MongoDB** for storing drug and disease data as JSON documents.
- **Neo4j** for representing relationships (e.g., treatments, symptoms, complications) using a graph structure.

Includes:
- JSON schema design
- Data insertion scripts using `pymongo` and `py2neo`
- Cypher queries for relationship exploration
- Graph visualization using `NetworkX`

📄 Reference: [`MongoDB___Neo4j.pdf`](./MongoDB___Neo4j.pdf)

# TpMongoDB_Neo4j.ipynb`
Jupyter notebook demonstrating code execution for the MongoDB and Neo4j projects including:
- JSON insertions
- Py2Neo connection
- Cypher-based queries
- Dynamic visualizations

---

### 2. `NoSQL_MongoDB_Cassandra`
Covers practical exercises using:
- **MongoDB** to manipulate NYC restaurant datasets with queries, aggregation, geospatial search, and indexing.
- **Apache Cassandra** to manage transport and inspection data using Docker, CQL, and multi-node clusters.

 Focus:
- Differences between relational and document/column models
- Setup of Cassandra with Docker volumes and networked nodes
- Query design and CSV imports

📄 Reference: [`NoSQL_MongoDB.pdf`](./NoSQL_MongoDB.pdf)

---

### 3. `Neo4j_AirportGraph`
Introduces graph modeling in Neo4j using CSV files representing airports, airlines, and routes.

 Features:
- Creation of `Airport`, `Airline`, and `Flight` nodes
- Establishment of complex relationships (`SOURCE`, `DESTINATION`, `BELONGS`, etc.)
- Use of Cypher for importing data and querying
- Visual representation of the graph with Neo4j Browser

📄 Reference: [`Neo4j.pdf`](./Neo4j.pdf)

---

##  Requirements

- Python ≥ 3.7
- MongoDB (local or Atlas)
- Neo4j (Aura or Desktop)
- Apache Cassandra (via Docker)
- Python Libraries:
  - `pymongo`
  - `py2neo`
  - `networkx`
  - `matplotlib`
  - `cassandra-driver` (for Cassandra queries)

