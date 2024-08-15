
# Data Engineering Knowledge Collection
Collection of useful articles / websites about Data Engineering

## <ins>1. Python<ins>
## <ins>2. SQL<ins>
### Merge
- [Understanding the SQL MERGE statement](https://www.sqlshack.com/understanding-the-sql-merge-statement/)
### Dynamic SQL
- [The Curse and Blessings of Dynamic SQL](https://www.sommarskog.se/dynamic_sql.html)

## <ins>3. Concepts<ins>
### Data modelling
### Batch/Streaming processing
### OLAP/OLTP
### Data lakehouse
- [How I Built a Data Lakehouse With Delta Lake Architecture](https://nickefy.medium.com/how-i-built-a-data-lakehouse-with-delta-lake-architecture-c7cdf0d18ee5)
### Clean code
- [Clean Code Notes](https://github.com/JuanCrg90/Clean-Code-Notes)
## <ins>4. Data platforms<ins>
### Databricks
- [Optimizing Databricks Clusters for Performance](https://blog.devgenius.io/optimizing-databricks-clusters-for-performance-47ee8e656ca3)
- [Harnessing the Potential of Databricks Liquid Clustering: A Dynamic Data Layout Scaling with Growth of Data](https://balachandar-paulraj.medium.com/harnessing-the-potential-of-databricks-liquid-clustering-a-dynamic-data-layout-scaling-with-growth-2f7879eb6a5d)
- [Converting Stored Procedures to Databricks](https://medium.com/@24chynoweth/converting-stored-procedures-to-databricks-73fe4ab64ed0)
### Snowflake
### Microsoft Fabric
### Azure Synapse Analytics
[Azure Synapse and Delta Lake](https://www.jamesserra.com/archive/2022/03/azure-synapse-and-delta-lake/)
##### Dedicated SQL pool
- [Azure Synapse Analytics : Choose Right Index and Partition (Dedicated SQL Pools)](https://tsmatz.wordpress.com/2020/10/16/azure-synapse-analytics-sql-dedicated-pool-columnstore-index-partition/)
- [Guidance for designing distributed tables using dedicated SQL pool in Azure Synapse Analytics](https://learn.microsoft.com/en-us/azure/synapse-analytics/sql-data-warehouse/sql-data-warehouse-tables-distribute)
- [Loading Azure Synapse Dedicated SQL Pool with COPY INTO](https://pl.seequality.net/load-synapse-analytics-sql-pool-copy-into/)
## <ins>5. Databases / Data stores<ins>
### Data lake
- [Transactional Data Lakes — a Comparison of Apache Iceberg, Apache Hudi and Delta Lake](https://medium.com/geekculture/transactional-data-lakes-a-comparison-of-apache-iceberg-apache-hudi-and-delta-lake-9d7e58fd229b)
- [What is Apache XTable (formerly OneTable) — Interoperability for Apache Hudi, Iceberg & Delta Lake](https://dipankar-tnt.medium.com/onetable-interoperability-for-apache-hudi-iceberg-delta-lake-bb8b27dd288d)
##### Delta lake
- [Delta Lake: The Data Engineer’s missing piece Part-1](https://databeans-blogs.medium.com/delta-lake-the-data-engineers-missing-piece-part-1-ebab66a3f8c0)
- [Delta lake , ACID transactions for Apache Spark](https://medium.com/@achilleus/delta-lake-acid-transactions-for-apache-spark-2bf3d919cda)
- [Hands-On Introduction to Delta Lake with (py)Spark](https://towardsdatascience.com/hands-on-introduction-to-delta-lake-with-py-spark-b39460a4b1ae)
- [Delta Lake Liquid Clustering — A visual explanation](https://levelup.gitconnected.com/delta-lake-liquid-clustering-a-visual-explanation-b9d8782a9f33)
- [Regulatory Compliance (GDPR and CCPA) Using Spark & Delta Lake](https://aws.plainenglish.io/regulatory-compliance-gdpr-and-ccpa-using-delta-lake-fa0582b2fc2d)

### NoSQL
##### DuckDB
- [Quacking Queries in the Azure Cloud with DuckDB](https://medium.com/datamindedbe/quacking-queries-in-the-azure-cloud-with-duckdb-14be50f6e141)
- [Use dbt and Duckdb instead of Spark in data pipelines](https://medium.com/datamindedbe/use-dbt-and-duckdb-instead-of-spark-in-data-pipelines-9063a31ea2b5)
## <ins>6. Data processing tools<ins>
### Spark
- [Internal working of Spark](https://www.linkedin.com/posts/bigdatabysumit_bigdata-dataengineer-apachespark-activity-7123640497633431552-Epx1/?utm_source=share&utm_medium=member_desktop)
- [Spark processing example scenario](https://www.linkedin.com/posts/bigdatabysumit_bigdata-career-dataengineering-activity-7159812190508576768-U_jB/?utm_source=share&utm_medium=member_desktop)
- [Six Spark Exercises to Rule Them All](https://towardsdatascience.com/six-spark-exercises-to-rule-them-all-242445b24565)
- [4 Examples to Take Your PySpark Skills to Next Level](https://towardsdatascience.com/4-examples-to-take-your-pyspark-skills-to-next-level-2a04cbe6e630)
- [PySpark & Data Quality](https://medium.com/towards-data-engineering/pyspark-data-quality-3bbeb5e17887)
- [Building Spark Data Pipelines in the Cloud —What You Need to Get Started](https://towardsdatascience.com/spark-data-pipelines-in-the-cloud-118f38ea90b7)
- [What happens when you ask Spark to Load a 1GB CSV file?](https://medium.com/datavidhya/what-happens-when-you-ask-spark-to-load-a-1gb-csv-file-59321dea62a9)
- [3 Ways To Create Tables With Apache Spark](https://towardsdatascience.com/3-ways-to-create-tables-with-apache-spark-32aed0f355ab)
- [Developing a PySpark application on a local Kubernetes cluster](https://medium.com/israeli-tech-radar/developing-a-pyspark-application-on-a-local-kubernetes-cluster-using-macos-b73d5c0f26ee)
- [Difference between reduce and reduceByKey in Apache Spark](https://medium.com/@vishalbarvaliya/apache-sparks-reducebykey-and-reduce-transformations-42b3bd80e32e)
- [PySpark DataFrames: a Comprehensive Guide](https://ai.gopubby.com/pyspark-dataframes-a-comprehensive-guide-6cac34964c02)
- [Important Spark Topics for Data Engineer](https://medium.com/@vishalbarvaliya/important-spark-topics-for-data-engineer-96cdccf88acc)
- [Spark Concepts Simplified: Cache, Persist, and Checkpoint](https://medium.com/@john_tringham/spark-concepts-simplified-cache-persist-and-checkpoint-225eb1eef24b)
- [distinct() vs dropDuplicates() in Apache Spark](https://towardsdatascience.com/distinct-vs-dropduplicates-in-spark-3e28af1f793c)
- [Merging different schemas in Apache Spark](https://medium.com/data-arena/merging-different-schemas-in-apache-spark-2a9caca2c5ce)
- [Benefits of using Vectorized UDFs (Pandas UDFs) on Spark](https://medium.com/@wonseok.chris.choi/benefits-of-using-vectorized-udfs-pandas-udfs-on-spark-60e2cef23653)
- [Using Airflow to Schedule Spark Jobs](https://medium.com/swlh/using-airflow-to-schedule-spark-jobs-811becf3a960)
##### Performance tuning
- [Apache Spark Performance Boosting](https://towardsdatascience.com/apache-spark-performance-boosting-e072a3ec1179)
- [Performance tuning](https://www.linkedin.com/posts/bigdatabysumit_bigdata-apachespark-dataengineering-activity-7137859349942599681-JXxJ/?utm_source=share&utm_medium=member_desktop)
- [4 Performance improving techniques to make Spark Joins 10X faster](https://medium.com/analytics-vidhya/4-performance-improving-techniques-to-make-spark-joins-10x-faster-2ec8859138b4)
- [Partition skew](https://www.linkedin.com/posts/bigdatabysumit_bigdata-dataengineering-apachespark-activity-7161390669914140672-NWtt/?utm_source=share&utm_medium=member_desktop)
- [Handling Data Skew in Apache Spark: Techniques, Tips and Tricks to Improve Performance](https://medium.com/@suffyan.asad1/handling-data-skew-in-apache-spark-techniques-tips-and-tricks-to-improve-performance-e2934b00b021)
- [Adaptive Query Execution](https://www.linkedin.com/posts/bigdatabysumit_bigdata-dataengineering-apachespark-activity-7107097499626045440-i5b0/?trk=public_profile_post_view)
- [Finding the Right Autobroadcast Join Threshold: Optimizing Spark Performance](https://medium.com/@vishalbarvaliya/finding-the-right-autobroadcast-join-threshold-optimizing-spark-performance-2e929e79949a)
##### Query plan
-  [Spark’s Logical and Physical plans … When, Why, How and Beyond.](https://medium.com/datalex/sparks-logical-and-physical-plans-when-why-how-and-beyond-8cd1947b605a)
-  [Be in charge of Query Execution in Spark SQL](https://towardsdatascience.com/be-in-charge-of-query-execution-in-spark-sql-c83d1e16b9b8)
-  [Mastering Apache Spark's Catalyst Optimizer: A Deep Dive with Detailed Examples](https://medium.com/@vishalbarvaliya/mastering-apache-sparks-catalyst-optimizer-a-python-deep-dive-with-detailed-examples-47d3aa28eb07)
##### Joins
- [The art of joining in Spark](https://towardsdatascience.com/the-art-of-joining-in-spark-dcbd33d693c)
- [Spark normal vs. broadcast join](https://www.linkedin.com/posts/bigdatabysumit_sumitteaches-bigdata-apachespark-activity-7137793450728464384-mFKf/?utm_source=share&utm_medium=member_desktop)
##### Bucketing
- [Best Practices for Bucketing in Spark SQL](https://towardsdatascience.com/best-practices-for-bucketing-in-spark-sql-ea9f23f7dd53)
- [Bucketing in Spark](https://blog.clairvoyantsoft.com/bucketing-in-spark-878d2e02140f)
##### Shuffling
- [Should I repartition?](https://towardsdatascience.com/should-i-repartition-836f7842298c)
- [Spark Optimization : Reducing Shuffle](https://selectfrom.dev/spark-optimization-reducing-shuffle-9cb2c109e977)
- [Revealing Apache Spark Shuffling Magic](https://medium.com/swlh/revealing-apache-spark-shuffling-magic-b2c304306142)
##### Configuration
- [Basics of Apache Spark Configuration Settings](https://towardsdatascience.com/basics-of-apache-spark-configuration-settings-ca4faff40d45)
- [Dive into Spark memory](https://luminousmen.com/post/dive-into-spark-memory)
- [Spark Memory Management](https://0x0fff.com/spark-memory-management/)
- [Memory Management in Apache Spark: Disk Spill](https://towardsdatascience.com/memory-management-in-apache-spark-disk-spill-59385256b68c)
##### Streaming
- [Building a Data Streaming Pipeline: Leveraging Kafka, Spark, Airflow, and Docker](https://medium.com/@simardeep.oberoi/building-a-data-streaming-pipeline-leveraging-kafka-spark-airflow-and-docker-16527f9e9142)
- [A Fast Look at Spark Structured Streaming + Kafka](https://towardsdatascience.com/a-fast-look-at-spark-structured-streaming-kafka-f0ff64107325)
- [Apache Spark Structured Streaming — Checkpoints and Triggers (4 of 6)](https://medium.com/expedia-group-tech/apache-spark-structured-streaming-checkpoints-and-triggers-4-of-6-b6f15d5cfd8d)
##### JSON parsing
- [PySpark JSON: A Comprehensive Guide to Working with JSON Data in PySpark](https://supergloo.com/pyspark-sql/spark-sql-json-examples-python/)
- [Flattening JSON records using PySpark](https://towardsdatascience.com/flattening-json-records-using-pyspark-b83137669def)


## <ins>7. Pipeline orchestration tools<ins>
### Airflow
### Azure Data Factory / Synapse pipelines
### DBT
## <ins>7. Data governance tools<ins>
### Unity Catalog

### Azure Purview
- [Modern Data Pipelines with Azure Synapse Analytics and Azure Purview](https://piethein.medium.com/modern-data-pipelines-with-azure-synapse-analytics-and-azure-purview-fe752d874c67)
- [Best practices for Purview and a federated way of working](https://piethein.medium.com/best-practices-for-purview-and-a-federated-way-of-working-7a146f10b3ac)
## <ins>8. DevOps practices<ins>
### Git
### CI/CD





















