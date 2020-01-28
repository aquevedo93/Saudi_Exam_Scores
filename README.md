# Saudi Exam Scores

Data scraped to be used to analyze the impact of a teacher subsidy program.

## Web Scraping 

Python scripts using web scraping techniques, including packages such as `Selenium` and `bs4`, to automate data extraction, transformation, and cleaning of Saudi exam data for all private schools in the country. Each jupyter notebook corresponds to a unique combination of the following features: 

* Type of Exam (Capabilities or Achievement)
* School Type (Boy or Girl)
* Exam Specialization (Scientific or Theoretical)
* School Type (Private, in this case)

The 'Cleaning_Appending' notebook brings all datasets together and adds relevant columns. The resulting dataset is named `'exam_scores_complete.csv'` and can be found in the data folder along with the individually scraped data sets. 

## Data

Data from the National Center for Assessment: https://www.qiyas.sa/en/Pages/default.aspx 

