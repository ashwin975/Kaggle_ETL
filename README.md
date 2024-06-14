# Kaggle_ETL

## Introduction:
The primary objective of this project is to create a robust data pipeline that facilitates the extraction of diverse datasets from Kaggle, processes and refines these datasets using Python and pandas, and stores the processed data in a PostgreSQL database for secure, scalable access. Finally, the data is dynamically visualized using Tableau, providing stakeholders with powerful, actionable insights through interactive dashboards.

## Tech Stack:

- ✅ Kaggle API: Utilized for accessing a wide range of datasets available on Kaggle
- ✅ Python and pandas: Allowing for efficient data cleaning, transformation, and preparation
- ✅ PostgreSQL: Chosen for its robustness and reliability as a relational database
- ✅ Tableau: enabling end-users to interact with the data through insightful dashboards

## 🏛️ Architecture:

![alt text](https://github.com/ashwin975/Kaggle_ETL/blob/main/Kaggle%20ETL.png)

## 𝍖 Data Extraction: 
- The pipeline begins with the Kaggle API, which is used to extract data. This is a common approach for accessing a vast range of datasets provided by Kaggle for various analytical purposes.
Chosen dataset with api - neuromusic/avocado-prices 

## 📝 Data Processing: 
- The extracted data is then processed using Python combined with the pandas library, a powerful duo for data manipulation and analysis. This stage typically involves cleaning, transforming, and preparing the data for loading into a database.
Once cleaned, server setup and connection was established with PostGres Local storage, it could also be deployed on cloud within postgres

## 💿 Data Storage: 
- The processed data is stored in a PostgreSQL server. PostgreSQL is a robust, open-source relational database system known for its reliability and feature set, making it an excellent choice for handling complex queries and large volumes of data.
EDA was carried out with postgres, ensuring consistent data types and addition of primary key column

## 📊 Data Visualization: 
- Finally, the data flows into Tableau, a popular visualization tool used to create interactive and shareable dashboards. Tableau's ability to connect directly to PostgreSQL allows for dynamic data exploration and visualization.

Overall, this workflow efficiently moves data from extraction through to visualization, enabling users to derive insights and make data-driven decisions effectively.

[Tableau Dashboard Link](https://public.tableau.com/app/profile/ashwin.singaram/viz/Avocados_17182429828380/PriceOverview)
