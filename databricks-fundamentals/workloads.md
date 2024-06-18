# Supported Workloads

## Data Warehousing

- **Databricks SQL**:
    -   Text to SQL
    -   AI-driven queries
    -   AI-driven serverless computing scales for cost efficiency and peak performanc
    -   AI-driven debugging and remediation
- **Problems without AI**:
    -   Resource misallocation: Inefficient resource allocation leading to potential infrastructure overuse or underuse.
    -   Difficulty in scaling: Challenges in scaling up for larger data volumes and complex queries.
    -   Higher operational costs: Increased manual efforts leading to higher operational costs.
### AI-powered Data Warehousing for Performance

- **Auto-tuning**: Automatically optimizes writes and compacts storage of managed tables to reduce latency and cost.
- **Intelligent Workload Management**: Uses machine learning to efficiently route queries and scale clusters for optimal cost and performance.
- **Predictive I/O**: Delivers performance comparable to expensive search-optimized indexes automatically.

### Databricks Assistant in Action for BI

- **Text-to-SQL Conversion**: Effortlessly transforms natural language into SQL queries.
- **Auto-Generates & Completes Code/Queries**: Streamlines coding with intelligent automation.
- **Problem Diagnosis & Resolution**: Identifies issues and provides solutions.
- **Unity Catalog Integration**: Delivers contextually relevant results aligned with your data assets.

### Best TCO and Performance for Data Warehousing

- **Instance Optimization**: Automatically determines instance types and configurations for the best price/performance ratio.
- **High Concurrency**: Features built-in, automatic load balancing.
- **Intelligent Workload Management**: Provides faster reads for queries.
- **Serverless Benefits**: Instant startup, greater availability, and 40% average lower overall costs.

## Orchestration

## Workflows
- **Intelligent ETL processing**
- **AI-driven debugging and remediation**
- **End-to-end observability and monitoring**
- **Broad ecosystem integration**

### Simplified and Automated Orchestration

- **Intelligent Pipeline Triggering**
  - Scheduled tasks via cron.
  - File arrival triggers.
  - Updates to Delta tables.
  - Continuous run capabilities.
  - Programmable API for custom triggers.

- **Automatic Resource Allocation**
  - Serverless compute resources.
  - Intelligent autoscaling based on load.
  - Automatic startup and shutdown of compute resources to optimize usage.
  - Automatic sharing of compute resources across tasks.

- **Automatic Checkpointing and Recovery**
  - In the event of a failure, the system automatically recovers from the last checkpoint.
  - This avoids the need to reload data, saving time and resources.

- **Automatic Monitoring and Alerting**
  - Predefined timeouts to identify and flag late-running jobs.
  - Automatic alerts for errors and timeouts, with notifications sent through Email, Slack, Teams, or web hooks.

## ETL and Real-time Analytics

### Delta Live Tables
- **Automated scalable streaming ingestion and transformation**
- **Workload-specific autoscaling**
- **Intelligent orchestraion, error handling and optimization**

### Building an ETL Pipeline: Key Challenges
1. **Need High-Quality, Fresh Data in Real-Time**: Requires sophisticated infrastructure to handle data complexity while reducing costs.
2. **Slow Queries and Delayed Data Access**: Impacts timely decision-making, machine learning outcomes, and overall productivity.
3. **Extensive Coding and Debugging**: Consumes significant time managing the ETL lifecycle, affecting efficiency.

### Automated and Scalable Data Ingestion
- **Simple SQL Syntax**: Makes data streaming accessible to all data engineers and analysts.
- **Automatic Ingestion Scalability**: Handles high volumes of data via incremental processing.
- **Real-time Analytics and BI**: Supports operational use cases with streaming data for real-time decision-making.

### Intelligent Optimizations for Incremental ETL
- **MERGE for Specific Rows**: Utilizes database techniques to optimize and update results efficiently.
- **Automatic Incremental Ingestion**: Enhances the ETL pipeline from ingestion to transformation.
- **Evaluation of Incremental Strategies**: Determines the best approach based on query plans and data.

### AI-enhanced Autoscaling
- **Backlog and Utilization Monitoring**: Automatically adjusts compute resources based on demand.
- **Intelligent Allocation Algorithm**: Optimizes compute scheduling to reduce costs and latency.
- **Adaptability to Workloads**: Ensures efficient resource use for streaming workloads, maintaining performance and cost efficiency.

## Data Science and AI

-   Create, tune, and serve custom LLMs
    -   Gen AI
        -   Custom Models, Model Serving, RAG
    -   End-to-end AI
        -   MLOps (MLflow)
        -   AutoML
        -   Monitoring
        -   Governance
    -   Project Genie
        -   Data and AI for all with natural language

### Databricks AI — Optimized for Generative AI

#### Datasets
- **Vector Search**: Enhances data retrieval capabilities by implementing vector search for complex query handling.
- **Feature Serving**: Provides real-time feature serving capabilities to support model predictions.
- **Data Collection and Preparation**: Facilitates the gathering and preparation of data, ensuring it's ready for use in training and inference.

#### Models
- **Curated AI Models**: Offers a range of pre-built models tailored for various AI tasks.
- **AutoML for LLM Training**: Automates the process of training large language models, optimizing for performance and accuracy.
- **MLflow Evaluation**: Utilizes MLflow for robust model evaluation and management.
- **Use Existing Model or Build Your Own**: Allows flexibility in model usage and customization according to specific needs.

#### Applications
- **MLflow AI Gateway**: Serves as the interface for deploying and managing AI models.
- **Model Serving Optimized for LLMs**: Ensures efficient serving of large language models to handle extensive computational needs.
- **Lakehouse Monitoring**: Integrates monitoring tools to oversee model performance and data quality within a unified data architecture.
- **Model Serving and Monitoring**: Implements a comprehensive approach to deploy and continuously monitor model performance and health.

#### Platform Structure
- **Unity Catalog**: Centralizes data management and governance, ensuring consistent data access and security across the platform.
- **Data Platform**: Provides the foundational infrastructure and tools necessary for robust data handling and model training.
