# Hospital Y Records Analysis for the Year 2022
![Image Alt Text](/visualizations/readme_image.jpg)




Photo Credits:pixabay.com


Hospital Y has sought assistance in analyzing their records for the year 2022 to make informed decisions. The dataset provided by Hospital Y is in Excel format and consists of four worksheets named 'Visit Tbl', 'Invoice Tbl', 'Diagnosis Tbl', and 'Data Dictionary'. Our objective is to answer the questions provided by the hospital using pandas data frames.

## Questions to Address
1. How many visits did Kimathi Street and Pipeline medical centers have between May 2022 and September 2022?

2. What was the most common diagnosis in 2022 for Tassia and Embakasi branches combined?

3. Which payor was the most profitable (in absolute numbers) for Hospital Y in 2022, assuming a gross average margin of 30% per visit?

4. What was the average spend per visit for visits with a diagnosis of acute gastritis?

5. How many unique patients experienced a blended healthcare approach (physical visits and virtual care) at Hospital Y in 2022?

6. What was the Net Promoter Score (NPS) for Q3 2022?

7. What proportion of visits were second visits?

8. What percentage of visits in April 2022 occurred within 30 days of the preceding visit by the same patient?

## Data Analysis Approach
To gain a comprehensive view of the data, we will combine the information from the 'Visit Tbl', 'Invoice Tbl', and 'Diagnosis Tbl' worksheets into a single dataframe. We will exclude the 'Data Dictionary' worksheet as it does not contain relevant data for our analysis. The 'VisitCode' column, present in all three worksheets, will serve as the key to merge the data effectively. By merging the datasets, we can answer our questions based on the integrated information.

## Dependencies
The analysis was conducted using Python library Pandas.

#### Please note that this README provides an overview of the analysis approach and the questions to be addressed. The answers to the questions are presented in the Jupyter Notebook.

## Folder Structure

|- data/

    |- BI_Analyst_Assessment_Data_2023.xlsx
    
|- analysis/

    |- Health Assessment for Hospital Y
    
|- README.md


Feel free to explore the analysis and contribute to this repository. Happy analyzing!




