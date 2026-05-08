# PRODIGY_DS_02
In this task, I performed data preprocessing and exploratory data analysis using the Titanic dataset. The goal of this task was to clean the dataset, handle missing values, and discover meaningful insights using visualizations.

 Dataset Used:-
The dataset contains three files:

* **train.csv** – training dataset for analysis
* **test.csv** – testing dataset
* **gender_submission.csv** – sample prediction file

Steps Performed:
**1. Data Loading**

* Imported the dataset using Pandas.
* Checked dataset structure using `.head()`, `.info()` and `.describe()`.

**2. Data Cleaning**

* Handled missing values in the **Age** column using mean imputation.
* Filled missing values in the **Embarked** column using mode.
* Removed the **Cabin** column due to excessive missing values.
* Verified that the dataset contains no null values.

**3. Exploratory Data Analysis (EDA)**
Performed visual analysis using Matplotlib and Seaborn:

* Survival count visualization
* Survival comparison by gender
* Passenger class vs survival
* Age distribution of passengers
* Correlation heatmap of numerical features

Tools & Libraries Used:
* Python
* Pandas
* Matplotlib
* Seaborn
* Google collab notebook

Outcome:
This task helped in understanding the importance of data cleaning and how visualizations can reveal patterns such as survival differences based on gender, age, and passenger class.
