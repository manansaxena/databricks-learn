# DI platform architecture overview

## Delta Lake Overview
- **Predictive I/O**: Optimizes I/O operations to enhance query performance by predicting and managing data access paths.

- **Predictive Optimizations**: Improves efficiency via query planning and data layout optimizations based on data characteristics and access patterns.

- **Liquid Clustering**: Dynamically reorganizes data into clusters based on ingestion and access patterns to reduce query times.

- **ACID Transactions Guarantees**: Ensures data integrity with atomicity, consistency, isolation, and durability in transactions.

- **Scalable Data and Metadata Handling**: Manages large volumes of data and metadata efficiently.

- **Audit History and Time Travel**: Tracks changes and allows accessing historical data snapshots.

- **Schema Enforcement and Schema Evolution**: Maintains and adapts data schema over time, ensuring data quality.

- **Support for Deletes, Updates, and Merges**: Enables modifying data with delete, update, and merge operations.

- **Unified Streaming and Batch Data Processing**: Supports both real-time streaming and batch processing within the same framework.

- **Compatibility with Apache Spark**: Fully integrates and leverages Apache Spark for processing.

- **Use Delta Tables**: Utilizes Delta tables for storage and operations, enhancing capabilities over regular Spark tables.

- **Transaction Log**: Maintains a log of all transactions, essential for ACID properties and time travel.

- **Open-Source Project**: Available for community use and contribution, enhancing transparency and collaboration.

## Unity Catalog Overview

- **Context-aware Search**: Enhances search functionality by understanding the context of queries, improving result relevance.

- **Auto Describe Tables and Columns**: Automatically provides descriptions for tables and columns, aiding in data understanding and governance.

- **Automated Lineage**: Tracks and visualizes the flow of data across systems automatically, crucial for compliance and troubleshooting.

- **End-to-End Observability and Monitoring**: Offers comprehensive tools to monitor and observe data operations across the entire data pipeline.

- **Sharing AI Models**: Facilitates the sharing of AI models across different teams or projects, promoting reusability and collaboration.

### Core Components
- **User Management**: Controls and manages user access and roles.
- **Access Controls**: Ensures data security through fine-grained access permissions.
- **Data Lineage**: Provides visibility into data origins and transformations.
- **Automated Monitoring**: Tools for tracking and optimizing performance.
- **Auditing**: Records operations for compliance and review.
- **Data Discovery and Classification**: Classifies and organizes data assets for easier access.
- **Data Sharing**: Facilitates the sharing of data across various teams or departments.

### Unified View of the Data and AI Estate
- **Discover, Classify and Organize Data**: Manages both structured and unstructured data, including notebooks and machine learning models.
- **Data Federation**: Allows integration of data from external sources without needing to ingest it into the system.
- **Tag-Based Search**: Enhances data discoverability through efficient tagging mechanisms.

### Single Permission Model for Data and AI
- **Unified Interface**: Secures your data estate with a unified interface for managing access policies across all data and AI assets.
- **Fine-Grained Access Controls**: Enables enhanced security through fine-grained access controls on rows and columns.
- **Open Interfaces**: Securely access data from diverse computing platforms using open interfaces.

### AI-Driven Monitoring and Reporting
- **Proactive Alerts**: Receive proactive alerts for quality issues and errors in data and ML model pipelines.
- **Real-Time Data Lineage**: Access real-time data lineage down to the column level for efficient root cause analysis and error debugging.
- **Auto-Generated Dashboards**: Utilize auto-generated dashboards to easily share data and ML quality reports.
- **End-to-End View**: Gain a clear end-to-end view on data flow and consumption, ensuring compliance and audit readiness.


## Data Governance

### Key Elements of Data Governance
- **Data Cataloging**: Organizing data assets for easy access and management.
- **Data Classification**: Categorizing data to enforce security and compliance measures.
- **Auditing Data Entitlements and Access**: Monitoring and recording access to data assets.
- **Data Discovery**: Tools and processes for locating and understanding data.
- **Data Lineage**: Tracing the origin and movement of data through systems.
- **Data Quality**: Ensuring the accuracy, completeness, and reliability of data.
- **Data Security**: Protecting data from unauthorized access and breaches.
- **Data Sharing and Collaboration**: Facilitating the controlled sharing of data across teams.

### Challenges in Data and AI Governance
- **Fragmented View of Data Estate**: Leads to a reduced pace of innovation due to lack of a holistic view.
- **Multiple Tools for Access Management**: Increases data breach risks and operational expenses.
- **Incomplete Monitoring and Visibility**: Results in non-compliance risks and reputational harm.
- **Lack of Cross-Platform Data Sharing**: Causes costly data sharing and untapped monetization opportunities.

### Databricks Data Governance Offerings
- **Unity Catalog**: Provides unified governance and security across all data and AI assets.
- **Delta Sharing**: Enables secure sharing of data between organizations.
- **Databricks Marketplace**: Facilitates the commercialization of data assets.
- **Databricks Cleanrooms**: Offers private, secure computing environments.

### Governance Simplified with Intelligence
- **Context-aware Search**: Utilizes an AI-powered knowledge engine for enhanced data discovery.
- **AI-generated Descriptions**: Automatically generates descriptions and comments for data assets.
- **Natural Language Search**: Allows finding data using natural language across the entire data estate.
- **Auto-capture Real-time Lineage**: Automatically captures data lineage in real time.
- **Proactive Anomaly Detection**: Automates the detection of anomalies in data and models for early intervention.
- **Operational Intelligence**: Achieves complete observability of data and AI systems for optimized operations.

### Benefits of Delta Sharing
- **Open Cross-platform Sharing**: Facilitates data sharing across different platforms without copying data.
- **Centralized Governance**: Centralizes administration and governance of shared data.
- **Marketplace for Data Products**: Enables monetization and exploration of data assets in a marketplace.
- **Privacy-safe Data Clean Rooms**: Provides environments for confidential collaboration on sensitive data.

### Open Data Sharing and Collaboration
- **Avoid Vendor Lock-in**: Uses open-source Delta Sharing to enable seamless data sharing across clouds and platforms without replication.
- **Share Beyond Data**: Allows sharing of notebooks, ML models, and dashboards.
- **Monetize Data Products**: Explores and monetizes data through an open marketplace.
- **Scalable Clean Rooms**: Offers scalable environments for confidential collaboration on sensitive data.

### Databricks Clean Room

- **Collaboration Across Platforms**: Enables multiple collaborators to work together using the Delta Sharing Protocol. Each collaborator, whether on AWS, Google Cloud, or Azure, uses existing tables.

- **Trusted Compute Environment**: Jobs are executed on a trusted compute environment, ensuring that only mutually approved jobs run, which maintains security and integrity.

- **Arbitrary Computation**: Supports running any computation in Python, SQL, R, Java, etc., providing flexibility in the analytical tools used.

- **No Data Replication**: Utilizes Delta Sharing for cross-region or cross-cloud sharing without the need to replicate data, preserving bandwidth and reducing storage costs.

- **Scalability**: Designed to easily scale according to the needs of the collaboration, supporting multiple collaborators on data of any size.

