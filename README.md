# HR-DATA-ANALYSIS
The project involved cleaning and processing HR data to ensure accuracy and readiness for analysis, facilitating informed decision-making within the organization.
HR Data Cleaning and Processing

Introduction:
In this report, we document the steps taken to clean and process HR data for further analysis. The dataset provided contained information about employees, including attributes such as age, department, salary, job satisfaction, etc. Our objective was to prepare the dataset for analysis by removing inconsistencies, handling missing values, and ensuring data quality.

1. Data Cleansing:
We followed a systematic approach to clean the dataset:

1.1. Removed Unnecessary Columns:
Columns like EmployeeCount, EmployeeNumber, and StandardHours were identified as unnecessary for analysis as they contained constant values or unique identifiers. Therefore, these columns were removed from the dataset.

1.2. Renamed Columns:
To improve readability and clarity, column names were modified. For instance, "Attrition" was renamed to "LeftCompany" to better reflect the information it represents.

1.3. Eliminated Redundant Entries:
Duplicate rows were checked and removed from the dataset to ensure data integrity and avoid bias in analysis.

1.4. Sanitized Specific Columns:
Categorical columns were examined to ensure consistency and meaningful values. This step aimed to standardize formats and fix any inconsistencies in the data.

1.5. Eliminated NaN Values:
Missing values (NaN) were handled appropriately by either replacing them with suitable values or removing the corresponding rows containing NaN values.

1.6. Additional Changes:
Further adjustments were made as necessary to ensure the dataset's readiness for analysis. This included standardizing data formats, encoding categorical variables, and performing outlier detection and removal.

2. Implementation:
Following the above steps, the dataset was cleaned and processed. A summary of the actions taken is as follows:

Removed unnecessary columns: EmployeeCount, EmployeeNumber, and StandardHours.
Renamed columns: Improved readability and clarity of column names.
Eliminated redundant entries: Removed duplicate rows from the dataset.
Handled missing values: Removed rows with NaN values to maintain data integrity.
Verified the dataset: Ensured columns and data types are appropriate for analysis.
The cleaned dataset now consists of 32 columns and 1470 rows, ready for further analysis.

3. Export Cleaned Data:
The cleaned dataset was exported to a CSV file named "HR_Data_Cleaned.csv" for future use and sharing.

4. MySQL Code for Loading Data:
To facilitate database storage and retrieval, MySQL code was provided to create a database table and load the cleaned data into it.

Conclusion:
In conclusion, the HR dataset has been successfully cleaned and processed, making it suitable for in-depth analysis and insights generation. By ensuring data quality and integrity, we have laid the foundation for meaningful exploration of employee-related trends, patterns, and relationships within the organization. This cleaned dataset can now serve as a valuable resource for HR analytics and decision-making processes.
