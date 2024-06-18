# Security, reliability, and performance

### Users
- **Interactive Users**: Users who interact directly with Databricks via web applications.
- **BI Apps**: Business Intelligence applications like Qlik and Looker used for data visualization and analysis.

### Control Plane
- **Web Application**: The main interface for users to interact with Databricks.
- **Configurations**: Settings and configurations that manage the behavior of Databricks services.
- **Notebooks, Repos, DBSQL**: Tools for coding (notebooks), version control (repos), and querying (Databricks SQL).
- **Cluster Manager**: Manages the creation, scaling, and operation of clusters used for computation.

### Customer (Data Plane)
- **Clusters**: Multiple clusters can be deployed as per the user's processing needs.
- **Your Cloud Storage**: The storage solution where the user’s data is stored.
  - **Data**: Actual data stored in user-specified formats.
  - **DBFS Root**: The root directory for Databricks File System (DBFS), integrating various data sources.

### User Identity and Access

- **Table ACLs Feature**: Allows for fine-grained access control at the table level, ensuring that users can only access the data they are permitted to see.

- **IAM Instance Profiles**: Utilizes AWS Identity and Access Management (IAM) instance profiles to manage permissions for Databricks resources securely.

- **Securely Stored Access Key**: Ensures that access keys used for authentication and authorization are stored securely, protecting against unauthorized access.

- **The Secrets API**: Provides a secure way to handle sensitive data like passwords and API keys through the Databricks environment, keeping them hidden from user scripts and logs.

### Databricks Serverless Data Plane Overview

#### Components
- **Customer**
  - **Your Cloud Storage**: Consists of your data and the Databricks File System (DBFS) root where data is stored.

- **Databricks**
  - **Serverless Data Plane**: Contains clusters and an unallocated pool of resources that can be dynamically used as needed.
  - **Control Plane**: Includes the web application for user interaction, configurations, repositories, Databricks SQL, and the cluster manager.

- **Users**
  - **Interactive Users**: Users who directly interact with Databricks through the web application.
  - **BI Apps**: Business Intelligence applications like Qlik and Looker that integrate with Databricks for data analytics.

#### Benefits and Features
- **Managed Servers**: Always-running server fleet that is patched and upgraded automatically.
- **Serverless SQL Compute**: Hosted within the Databricks cloud account, allowing instant compute resource allocation and high availability.
- **Elastic**: Automatically scales up and down based on the workload requirements.
- **Secure**: Ensures data security through three-layer isolation and encryption.
- **Productivity**: Users benefit from instant query execution and built-in connectors, enhancing productivity.
- **Cost Efficiency**: Reduces operational costs by minimizing idle time and preventing over-provisioning.

#### Photon
-   I think of it as an advanced version of Spark