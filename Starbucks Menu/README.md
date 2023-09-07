# Objective 
To perform the ETL process by extracting local data, transforming it using Python and load into PostgreSQL

# Technologies Used 
- Database: PostgreSQL
- Language: Python (Pandas, NumPy)

# Data Architecture
<img width="591" alt="ETL Image" src="https://github.com/dareyup/data_engineering/assets/88558602/a742cd8b-24f6-4224-98ef-742de62d1c01">



# ETL Process
1. Data is extracted from [Kaggle](https://www.kaggle.com/datasets/starbucks/starbucks-menu) locally
2. The [starbucks_menu_db.ipynb](https://github.com/dareyup/data_engineering/blob/main/Starbucks%20Menu/starbucks_menu_db.ipynb) initiates a connection to PostgreSQL and creates the database with auto-commit
3. Tables are created with columns and data types
4. Cleaned data is inserted into new tables 
