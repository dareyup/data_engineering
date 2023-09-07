# Objective 
To perform the ETL process by extracting local data, transforming it using Python and load into PostgreSQL

# Technologies Used 
- Database: PostgreSQL
- Language: Python (Pandas, NumPy)

# Data Architecture
https://user-images.githubusercontent.com/81607668/237030996-a92947af-5e9b-42be-8a34-9b4073f6e7ef.png![image](https://github.com/dareyup/data_engineering/assets/88558602/e291584c-e311-4331-9dd9-1d1b0b139ff8)

# ETL Process
1. Data is extracted from [Kaggle](https://www.kaggle.com/datasets/starbucks/starbucks-menu) locally
2. The [starbucks_menu_db.ipynb](https://github.com/dareyup/data_engineering/blob/main/Starbucks%20Menu/starbucks_menu_db.ipynb) initiates a connection to PostgreSQL and creates the database with auto-commit
3. Tables are created with columns and data types
4. Cleaned data is inserted into new tables 
