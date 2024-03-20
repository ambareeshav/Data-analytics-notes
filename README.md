A **modern data ecosystem** includes a network of interconnected and continually evolving entities that include:
- Data that is available in a host of different formats, structure, and sources.
- Enterprise Data Environment in which raw data is staged so it can be organized, cleaned, and optimized for use by end-users.
- End-users such as business stakeholders, analysts, and programmers who consume data for various purposes.
- Emerging technologies such as Cloud Computing, Machine Learning, and Big Data, are continually reshaping the data ecosystem and the possibilities it offers.
- Data Engineers, Data Analysts, Data Scientists, Business Analysts, and Business Intelligence Analysts, all play a vital role in the ecosystem for deriving insights and business results from data.

Primary types of Data Analysis: 
- Descriptive Analytics, that helps decode “What happened.” 
- Diagnostic Analytics, that helps us understand “Why it happened.” 
- Predictive Analytics, that analyzes historical data and trends to suggest “What will happen next.” 
- Prescriptive Analytics, that prescribes “What should be done next.” 

The Data Analysis process involves:
- Developing an understanding of the problem and the desired outcome. 
- Setting a clear metric for evaluating outcomes. 
- Gathering, cleaning, analyzing, and mining data to interpret results. 
- ommunicating the findings in ways that impact decision-making. 

**Role of a DA**
- Acquiring data
- Creating queries to extract data
- Filter, clean, standardize and reorganize data
- Use stat tools to interpret data
- Use techniques to identify patterns and correlations
- Analyse patterns and interpret trends
- Prepare reports to communicate trends
- Create documentation to define and demonstrate process

**Tehchnical Skills**
- Sheets/Excel
- Cognos, SPSS, oracle va, power BI, SAS, Tableau
- R, Python, C++, Java, MATLAB
- SQL, NoSQL, RDBMS
- Data marts, warehouses, lakes and pipelines
- Hadoop. Hive and Spark

**Functional skills**
- Statistics
- Analytical
- Problem Solving
- probing (Identify, understand and define problem)
- Data visualization
- Project management

**Soft skills**
- Collaboration
- Communication
- Compelling stories
- Curiosity
- Attention to detail
- Intuition
- Decision making

**Data**
- **Structured** – Rigid, Rows and columns, databases and spreadsheets. SQL , py etc
- **Semi structured** – Characteristic but no rigid structure, Email. XML, Json
- **Unstructured** – Complex and qualitative, Photos videos. Files, Docs, NoSQL

**Data formats**
- Plain text, XML, HTML, JSON, Media files

**What is data**
- Facts, observations, perceptions, numbers characters, symbols and pictures

**File Formats**
-CSV, XLSX, XML, PDF, JSON

**Sources of data**
- API’s, web services, social platforms
- **Web scraping** – Downloading data from websites based on specific parameters (BeautifulSoup, Scrapy, Pandas and selenium)
- **Data streams** – IoT, GPS, Programs sites and social media (Apache – Kafka Spark and Storm)

**Languages**
- **Query** – Accesing and manipulating data - SQL
- **Programming** – Developing apps and controlling app behaviour - Python, R, Java
- **Shell and scripting languages** – Unix, Linux, Powershell
- **Pandas**  - Data cleaning and analysis
- **Numpy**, Scipy for statistical analysis
- **BSoup and scrapy** – Web scraping
- **Matplotlib and seaborn**  - Visualization

**Data repositories**
Databases, data warehouses, data marts, data lakes, big data stores
- Data warehouses consolidate data through the ETL process, Extraction, transfer and Load

**RDBMS**
- IBM DB2, SQL Server, MySQL, ORACLE, PostgreSQL
- Cloud based - Amazon RDS, Google SQL, IBM DB2 on cloud, Oracle cloud and Azure SQL
- Use Cases
  - Online transaction processing systems
  - Data warehouses
  - IoT solutions
    
**NoSQL**
- **Key-Value store** (Redis, MemcacheD, DynamoDB)
- **Document based** (MongoDB, DocumentDB, CouchDB, Cloudant)
- **Column based** (Cassandra, Apache HBASE)
- **Graph Based** (Neo4J, CosmosDB)
- **ETL** (Extract, Transform, Load)
- **Batch processing**  Stitch, Blendo
- **Stream processing** – Apache samza storm and kafka
- Initial, Incremental, Full refresh
- Load verification

> ETL is a subset of the Data pipeline(Apache, beam, dataflow, kafka)(Typically sourced from a data lake)

> Data marts are sub sections of a data warehouse

**Big Data**
- Velocity, Volume, Variety, Veracity, Value
  - **Velocity** – Speed at which data is gathered
  - **Volume** – Scale of data 
  - **Variety** – Diversity of data
  - **Veracity** – Quality and origin of data
  - **Value** – Ability to turn the data into data
  
**Big Data Processing technologies**
- **Hadoop** – Distributed storage and processing of big data
- **Hive** – Data warehouse for data query and analysis built on top of Hadoop
- **Spark** – Distributed analytics framework for complex, real-time data analytics

**Data Repositories**
- Databases, which can be relational or non-relational
- Data Lakes, that serve as storage repositories for all types of data 
- Big Data Stores, that provide distributed computational and storage infrastructure to store, scale, and process very large data sets.
  
ETL, or Extract Transform and Load, Process is an automated process that converts raw data into analysis-ready data by:
Extracting data from source locations.
  - Transforming raw data by cleaning, enriching, standardizing, and validating it.
  - Loading the processed data into a destination system or data repository.

>Data Pipeline, sometimes used interchangeably with ETL, encompasses the entire journey of moving data from the source to a destination data lake or application, using the ETL process.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Process for identifying data**
- Determine the info you want to collect
- Define the data you want to collect
= Determine your data collection needs
- Make sure data governance and data security are in check

**Sources for gathering data**
- Databases
- Web
- Social media sites and Interactive platforms
- Sensor data
- Data exchange (AWS de, Crunchbase, Lotame, Snowflake)
- Surveys
- Census
- Interviews
- Observation studies
  
>Talond, informatica, R, Python can be used for importing data

**Data wrangling** 
- Discovery (Exploration)
- Transformation (Majority of time is spent here)
  - Structuring (Unions and Joins)
  - Normalizing and de normalizing
  - Cleaning
  - Enriching data
- Validation
- Publishing
- Document all considerations and actions
  
**Factors for choosing a tool for data wrangling**
- Supported data size
- Data structures
- Cleaning and transforming capabilities 
- Infrastructure needs
- Ease of use
- Learnability

**Data Cleaning**
- Subset of the data wrangling process
- Inspection 
- Cleaning 
  - Profiling
  - Visualization
  - Missing
  - Duplicate
  - Irrelevant
  - Standardize
  - Syntax, Typos, Format, Outliers
- Verification (Re inspect results after corrections)
- Documentation (All changes with reason and quality of data)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Descriptive statistics**
- Central tendency
- Dispersion
- Skewness
  
**Inferential Statistics**
- Hypothesis testing
- Confidence Intervals
- Regression analysis

>SAS, SPSS, StatSoft

**Data Mining**
- Classification
- Clustering
- Anomaly or Outlier detection
- Association rule mining
- Sequential patterns
- Affinity grouping
- Decision trees
- Regression
  
**Data presentation**
- Who is my audience
- What is important to them
- What will help them trust me
- Structure your presentation
  
**Data Visualization and choosing the appropriate structures**
- What is the question I’m trying to answer
- What should be the key takeaway 
- What does my audience want to know
- What is the relationship I’m trying to establish
- Do i need my audience to the relation between two values
- Do i want to find anomalies in the data


**Visualization graphs**
- Bar charts
  - comparing related data sets or parts of a whole
- Column charts
  - Compare values side by side, change over time
- Pie charts
  - Break down values into subparts and their relational proportion
- Line charts
  - Trends, change over time
  - Variations in data
**Dashboards**
- Present findings to your audience
- Present a consolidated findings report of all the data analyzed
- Make live dashboards to have an interactive story session

