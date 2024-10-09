# Career Fair Data Analysis
This repository contains a Python script for processing and analyzing the registration data for the Fall 2024 Career Fair. The notebook utilizes the pandas library to clean, sort, and extract relevant information from the career fair registration data.

## Overview
The goal of this project is to:

* Clean the provided data by fixing formatting issues and protecting sensitive information.
* Sort employer names alphabetically, ensuring special characters do not affect sorting.
* Correct data inconsistencies such as booth numbers.
* Analyze and extract key information about employers, registrants, and their participation in the event.
**Note**: Sensitive information such as registrant details has been anonymized for this GitHub version.

## Key Features
1. Data Cleaning:

* Fixes formatting issues, such as extra spaces and incorrect data types.
* Anonymizes sensitive information like registrant names and contact details.
2. Sorting:

* Custom sorting logic that ignores punctuation and spaces while sorting employer names.
3. Analysis:

* Displays employer information, assigned booth numbers, and other relevant details.
* Extracts lists of employers with specific initiatives (e.g., DEI, neurodiversity, veteran hiring).
* Provides insights into payment statuses and amount due for participating employers.
4. Career Fair Insights:

* Displays advice for students, top things employers look for in resumes, and how employers measure success at career fairs.
## Data Sources
* Fall 2024 Career Fair FINAL Registration as of 10.2.24.csv: Contains the most updated registration data.
* F24 CF Booth Numbers.csv: Contains more information about relevant event data for Fall 2024.
## Requirements
* Python 3.x
* Pandas library (pip install pandas)
## Usage
To use the script, ensure the following files are in the same directory as the notebook:

1. Fall 2024 Career Fair FINAL Registration as of 10.2.24.csv
2. F24 CF Booth Numbers.csv
After loading the data, the notebook will clean and sort it, then display relevant insights as per the analysis described above.

## Data Protection
Sensitive information such as registrant names and emails has been replaced with placeholder values ('Registrant X', 'registrant@example.com') to ensure privacy.
