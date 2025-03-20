# Chicago Data Analysis with SQLite

## Overview
This project provides a Python Jupyter Notebook to analyze three datasets related to the city of Chicago using SQLite. You will learn how to:
- Understand and explore three datasets.
- Load datasets into SQLite database tables.
- Execute SQL queries to extract insights.

## Datasets Used
This project leverages three datasets from the City of Chicago's Data Portal:

### 1. Socioeconomic Indicators in Chicago
- This dataset includes six socioeconomic indicators and a hardship index for each Chicago community area from 2008 to 2012.
- [Dataset Description](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2)
- [Download CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCensusData.csv)

### 2. Chicago Public Schools
- Contains school-level performance data from the 2011-2012 school year.
- [Dataset Description](https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t)
- [Download CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoPublicSchools.csv)

### 3. Chicago Crime Data
- Includes reported crime incidents in Chicago from 2001 to present (excluding the most recent seven days).
- [Dataset Description](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)
- [Download CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoCrimeData.csv)

## Technologies Used
- **Python** (for data analysis and database operations)
- **Pandas** (for data manipulation and CSV handling)
- **SQLite** (for database storage and querying)
- **SQL** (for extracting insights from the database)
- **Jupyter Notebook** (for interactive analysis)

## How to Use
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install pandas sqlite3
   ```
3. Open the Jupyter Notebook and follow the instructions to load datasets and run SQL queries.
4. Execute SQL queries to explore and analyze the data.

## Notes
- Use the provided dataset links instead of directly accessing the Chicago Data Portal.
- The provided datasets are preprocessed for easier database integration.
- Run the initial code cell to avoid `prettytable` default error.

## License
This project is open-source and available for educational purposes.

---
Contributions and feedback are welcome!

