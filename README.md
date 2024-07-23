# Databricks dataflows

**The goal of this project to share code snippets how to create different ETL workflows in Databricks with SQL and PySpark.**

> Notebooks are created in Databricks Community Edition with the cluster config of:
> - Runtime version: *12.2 LTS (includes Apache Spark 3.3.2, Scala 2.12)*
> - Driver type: *Community Optimized - 15.3GB Memory, 2 Cores, 1 DBU*


## Setup

The exported notebooks can be imported from the sources (.dbc) and also from the HTMLs, where you can see the output of the workflow without running it.

## Cases

- `simple_dataflow` - *A simple data workflow by ingesting, cleaning, processing and aggregating user data to extract business insights from user distribution data. It uses medallion architecture to logically organize data.*
