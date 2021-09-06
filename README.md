# Database, Data Warehouse Technologies for Analytics

## Topic: **Can you eat healthy at fast foods or chain restaurants?**
Abstract—Using a data set of nutrition facts, this project tries to help people to choose the best meals in order to 
reduce health risks with dining out or choosing fast foods as their source of meals. We worked on a dataset that has 
nutrition facts of each item in chain restaurants from 2008 to 2018. The questions we answered are where to avoid, 
what to avoid, healthy changes in the menus. To answer these questions it was needed to set up and use a data warehouse
cloud server to enable the analysts to analyze the data collected simultaneously. We chose a star schema as 
our data model and loaded the database from MySQL to the MariaDB cloud server. In this project, 
we used a Hybrid Database for both transactional operation and analytics operation, 
which simulates a real-time OLTP data input process and the auto-replication engine replicates the new data in the
transactional database to the analytical database. This setup enables transactional data to feed to the data warehouse 
in real- time. The results will help people living in the USA to have healthy options. In the future with gathering
more data, we will find more trends in fast food meals.

### Step by step of this project:

1. Data source: [menustat](http://www.menustat.org/#/home).
2. Exploring the data with Jupyter Notebook.
3. Designing the schema. 'menu_data_EER.drawio'
4. Data cleansing, extract, and transform. 'data_cleansing_extract_transform.ipynb'
5. Setup row store and column store design, then load data. 'load_data_mariadb_cloud.ipynb'
6. Example analytical queries. 'database_analysis_queries.ipynb'
7. Report of the results. 'Final_Report.pdf' in the 'Report' folder.

### How to connect to MariaDB?
The function used to Connecting to mariaDB is in the'database_analysis_queries.ipynb' file. 
In order to protect our database, the IPs of group members are in white list of connections. 
Please feel free to contact 'Taoli Zhen', the creator of the database, for any connection issues.

#### Disclaimer:
This was a MS data analytics course project done by a team of five with me being the team lead.
All the codes included in this repository are done by myself.
