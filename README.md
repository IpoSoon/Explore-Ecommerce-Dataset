# [SQL] Explore Ecommerce Dataset
## I. Introduction
This project contains an eCommerce dataset that we will explore using SQL on [Google BigQuery](https://cloud.google.com/bigquery). The dataset is based on the Google Analytics public dataset and contains data from an eCommerce website.
## II. Requirements
* [Google Cloud Platform account](https://cloud.google.com)
* Project on Google Cloud Platform
* [Google BigQuery API](https://cloud.google.com/bigquery/docs/enable-transfer-service#:~:text=Enable%20the%20BigQuery%20Data%20Transfer%20Service,-Before%20you%20can&text=Open%20the%20BigQuery%20Data%20Transfer,Click%20the%20ENABLE%20button.) enabled
* [SQL query editor](https://cloud.google.com/monitoring/mql/query-editor) or IDE
## III. Dataset Access
The eCommerce dataset is stored in a public Google BigQuery dataset. To access the dataset, follow these steps:
* Log in to your Google Cloud Platform account and create a new project.
* Navigate to the BigQuery console and select your newly created project.
* In the navigation panel, select "Add Data" and then "Search a project".
* Enter the project ID **"bigquery-public-data.google_analytics_sample.ga_sessions"** and click "Enter".
* Click on the **"ga_sessions_"** table to open it.
## IV. Exploring the Dataset
In this project, we will write 08 query in Bigquery base on Google Analytics dataset
### Query 01: Calculate total visit, pageview, transaction and revenue for January, February and March 2017 order by month

* SQL code
![image](https://user-images.githubusercontent.com/101726623/235141283-3f640e8c-237f-4100-b734-f0383a999560.png)

* Query results
![image](https://user-images.githubusercontent.com/101726623/235141359-1648197b-6339-42ca-b2a2-3dce9f39283b.png)

### Query 02: Bounce rate per traffic source in July 2017

* SQL code
![image](https://user-images.githubusercontent.com/101726623/235142111-5df9bb05-f29c-49e5-a1d8-3f7187667874.png)

* Query results
![image](https://user-images.githubusercontent.com/101726623/235142182-87c47ea0-4cae-41b8-8204-f17d774914d3.png)

### Query 3: Revenue by traffic source by week, by month in June 2017

* SQL code
![image](https://user-images.githubusercontent.com/101726623/235142542-556901cf-2087-4c72-94d4-0372546ad77d.png)

* Query results
![image](https://user-images.githubusercontent.com/101726623/235142590-e0fec692-794c-4247-a659-433ce605c158.png)


## V. Conclusion
