## History of Data Management Platforms

1. 1980s, businesses need more than relational databases
2. Data warehouse
    - Pros:
        - Business Intelligence, Analytics, Structured & clean data, Predefined Schemas
        - External data and operation data were combined using ETL and stored in Data warehouses from which BI/Reports could be made
    - Cons:
        -   No support for semi or unstructured data, Inflexible schemas, Struggled with volume and velocity upticks,
        Long processing time
3. Data Lakes
    - Multiple data types can be stored: Structured, Semi-Structured, Unstructured
    - Pros:
        - Flexible data storage, streaming support, cost efficient in the cloud, support for AI and ML
    - Cons:
        - No transactional support, Poor data reliability, Slow analysis performance, Data governance concerns, Data warehouses still needed
4. Data Lakehouse
    -   Bring the best of both worlds. A open, unified foundation for all your data
    -   Open Data Lake -> Unified data storage for reliability and sharing -> Unified security, governance, and cataloging -> (Data Science & AI, ETL & Real-time analytics, Orchestration, Data Warehousing)
    -   Features:
        Transaction support, Schema enforcement and governance ,Data governance, BI Support, Decoupled storage form compute, Open storage formats, Support for diverse data types, Support for diverse workloads, end-to-end streaming
5.  Data Intelligence Platform
    -   Data Lakehouse + Generative AI
    -   Open Data Lake [All raw data] -> Unified data storage for reliability and sharing [Delta Lake] -> Unified security, governance, and cataloging [Unity Catalog] -> Use generative AI to understand the semantics of your data [Data Intelligence Engine] -> (Data Science & AI [Databricks AI] , ETL & Real-time analytics [Delta Live Tables] , Orchestration [Workflows] , Data Warehousing [Databricks SQL] )


Good resourse: https://eric.nz/posts/dbx-lakehouse-fundamentals/