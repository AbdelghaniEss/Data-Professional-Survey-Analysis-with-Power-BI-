# Professional Survey Data Analysis with Power BI

## Project Overview
This project focuses on analyzing professional survey data using **Power BI** to gain insights into respondents' demographics, work conditions, preferences, and more. Initial data cleaning and transformation were conducted in **Jupyter Notebook** before importing the cleaned dataset into Power BI.

## Process Outline

### Step 1: Data Preparation in Jupyter Notebook
1. **Data Import**: The raw dataset, titled **Power BI - Final Project.csv**, was imported into Jupyter Notebook for preprocessing.
2. **Column Management**: Irrelevant columns were removed to simplify the dataset, retaining only those essential for analysis.
3. **Standardization and Renaming**: Several columns were renamed for readability, and multiple values were standardized to ensure consistency across responses.
4. **Data Transformation**: Categories were consolidated, and responses with similar meanings were grouped to reduce redundancy and enhance analysis quality.
5. **Final Output**: After thorough data cleaning, the transformed dataset was saved as **Data Professional Survey.csv** for import into Power BI.

### Step 2: Data Analysis in Power BI
With the cleaned dataset in CSV format, analysis and visualizations were conducted in Power BI to explore key insights into various aspects of the professional survey data.

## Key Tools
- **Jupyter Notebook** for data cleaning and preparation.
- **Power BI** for data visualization and detailed analysis.

## File Structure
- **Power BI - Final Project.csv**: The original survey dataset in CSV format.
- **Data Professional Survey.csv**: The cleaned and standardized dataset in CSV format, ready for Power BI analysis.



### Additional Data Cleaning in Power BI

After importing the cleaned CSV into Power BI, I performed two additional data adjustments directly in Power BI:

1. **Job Title Standardization**: In the column `Q1-Current Job Title`, I used Power BI's "Replace Values" function to standardize remaining job titles that were missed during the initial cleaning process in Jupyter. Specifically, this included consolidating `sr. supply chain analyst` under the **Business Intelligence & Analytics** category.

2. **Country Field Adjustment**: In the column `Q11 - Which Country do you live in?`, entries labeled as 'other (please specify)' were replaced with a blank value to address the lack of identifiable country information.

3. **Handling Blank Values in Q6 Columns**: For all columns starting with **Q6**, blank values were replaced with `0` and the data type was converted from **text** to **decimal number** to enable accurate numerical analysis.

These updates ensure further consistency and clarity for analysis within Power BI.

