# Postgresql Vector Quickstart

## Overview

Notes on using the `pgvector` extension for PostgreSQL.

## Prerequisites

- Install PostgreSQL.
- Use the [instructions here](https://github.com/pgvector/pgvector) to install the `pgvector` extension.

## Using the Extension on WSL (Windows with Ubuntu)

- The installation of `pgvector` required a build that didn't work without the PostgreSQL development files. To install them:
  
  ```bash
  sudo apt install postgresql-server-dev-15
  ```

## Example of the output from the GEtting Started instructions
![Vector Quick Start Image](vector-quick-start-results.png)

## Notes
- It was very easy to implement the vector data type in Postgres
- Functionality wise - there is not much difference between the extension and the DataStax vector data type
- There are two supported index types for pgvector versus three index types for Cassandra
- There are slight differences on how the queries are written
