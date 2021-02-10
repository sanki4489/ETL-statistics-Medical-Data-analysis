Statistics-Medical-Data-analysis
Group Project
Concept covered: Statistics, ETL, Google colab, cloud
subject: Mcahine learning
sem: 5th
Group number: 02
Group Memeber: Sankalp verma, Bhavin S patel, Jhalak Rasaily

Problem statements:
1. A dataset is taken from WHO, which contains patients data who have tb from different countries. We need to clean the database and extract the useful information from it.
2. Build an ETL pipeline using Python and azure notebook

Solution steps:
How ETL works:
step 1: Extraction- Data extraction is the process of collecting or retrieving disparate types of data from a variety of sources, many of which may be poorly organized or completely unstructured. Data extraction makes it possible to consolidate, process, and refine data so that it can be stored in a centralized location in order to be transformed.

step 2: Transform-Data transformation is the process of converting data from one format to another, typically from the format of a source system into the required format of a destination system. Data transformation is a component of most data integration and data management tasks, such as data wrangling and data warehousing.

Step 3: Loading-The final step in the ETL process is to load the newly transformed data into a new destination. Data can be loaded all at once (full load) or at scheduled intervals (incremental load).


building ETL for our problem->
1. Extract
   The data set comes from the World health organisation and it records the number of confirmed tuberculosis cases by country, year, and demographic group.
   the demographic groups are broken down by sex and age.
   Datasets extracted is tb.csv

2. Transform
   we have used google colab and juypter notebook to perform data cleaning, visualising and analysis on the tb.csv dataset file.
   following listed operations are performed.
   Cleansing — inconsistencies and missing values in the data are resolved. 
   Standardization — formatting rule are applied to the data set.
   Deduplication — redundant data is excluded or discarded.
   Verification — unusable data is removed and anomolies are flagged.
   Sorting — data is organized according to type.
   Other tasks — any additional/optional rules can be applied to improve data quality.

3. Load
   The last step was to transfer our final output into a Database. We created a database and respective tables to match the columns from the final Panda’s Data Frame 
   using MYSQL and then uploaded the data into mysql database.

