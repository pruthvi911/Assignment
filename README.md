# PySpark Earthquake Analysis

Introduction:
This PySpark application analyzes earthquake data stored in a MySQL database. It performs various analyses and answers specific questions related to earthquake occurrences.

Prerequisites:
Python and PySpark: Ensure you have Python installed, and install PySpark version 3.0 or later. You can install PySpark using pip install pyspark.

MySQL Database: Set up a local MySQL database and create a table named neic_earthquakes with the appropriate schema for your dataset.

Dataset: Download the earthquake dataset from the provided link and save it to your local directory.

Configuration:
Before running the application, make sure to configure the following parameters in the code:

MySQL Connection:
url: URL of your MySQL server.
user: Your MySQL username.
password: Your MySQL password.
Dataset Path:

Update the path to your dataset CSV file in the script.
Running the Application
Load Data to MySQL:

Run the script load_data_to_mysql.py to load the earthquake data into the MySQL database. This script uses PySpark to read the CSV file and push it into the neic_earthquakes table.
bash
Copy code
python load_data_to_mysql.py
Run Analysis:

Execute the main analysis script earthquake_analysis.py to answer the specified questions using PySpark.
bash
Copy code
python earthquake_analysis.py
View Results:

Review the output in the console for each analysis question.
Additional Notes
Column Names: Ensure that the column names used in the script match the actual column names in your dataset. Adjust the script accordingly.

MySQL Server: Make sure your MySQL server is running when executing the scripts that interact with the database.

Adjustments: Feel free to modify the code to suit your specific needs or extend the analyses.
