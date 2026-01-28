# Data Engineer OneDay - Databricks Training

## About This Repository

This repository contains training materials, source code, and exercises for the "Data Engineer OneDay" training course provided by Altkom Akademia. The materials are designed to guide participants through key aspects of data engineering on the Databricks Lakehouse Platform.

## Course Agenda

The training program covers the full data engineering lifecycle, from platform introduction to orchestration and governance.

### Demo Modules (`notebooks/demo/`)

1.  **01_platform_intro** - Introduction to the Databricks platform, interface, and basic concepts (Workspace, Compute).
2.  **02_ingestion_transformations** - Data Ingestion from various sources and transformations using PySpark and SQL.
3.  **03_delta_lake_optimization** - Working with Delta Lake format, ACID operations, Time Travel, and optimization techniques (Z-Order, Optimize).
4.  **04_streaming_incremental** - Stream processing (Structured Streaming) and incremental data loading (Auto Loader).
5.  **05_medallion_lakeflow** - Medallion Architecture (Bronze/Silver/Gold) and building data pipelines in Lakeflow (Delta Live Tables).
6.  **06_orchestration** - Task orchestration using Databricks Workflows (Jobs).
7.  **07_governance** - Data management and security with Unity Catalog.

### Workshops (`notebooks/workshops/`)

Practical exercises for participants to complete independently:

*   **W1_ingestion_transformations** - Workshop on data ingestion and transformation.
*   **W2_delta_optimization** - Exercises on Delta table optimization.
*   **W3_lakeflow_pipeline** - Building a complete ETL pipeline in Medallion architecture.
*   **W4_governance_security** - Configuring permissions and governance.

## Repository Structure

```text
.
├── assets/                 # Graphical assets and helper files
├── dataset/                # Sample datasets (CSV, JSON)
├── lakeflow/               # Definitions and scripts for Delta Live Tables (DLT)
│   ├── lakeflow_trn_pipeline/
│   └── lakeflow_workshop/
├── notebooks/              # Jupyter/Databricks Notebooks
│   ├── demo/               # Demo notebooks (instructor-led)
│   └── workshops/          # Workshop notebooks (for students)
└── README.md               # Repository documentation
```

## Prerequisites

*   Basic knowledge of SQL and Python.
*   Access to Databricks platform (Azure Databricks, AWS Databricks, or GCP).
*   Basic understanding of cloud and database concepts.

## How to Use

1.  Clone the repository to your Databricks Workspace (Databricks Repos).
2.  Ensure that a compute cluster (All-Purpose Compute) is running.
3.  Run configuration scripts (if available, e.g., `00_setup.ipynb`) to prepare the environment (catalogs, databases).
4.  Go through the notebooks in the `demo` folder sequentially.
5.  Complete the tasks in the `workshops` folder as instructed by the trainer.

---
*Altkom Akademia Training Materials*
