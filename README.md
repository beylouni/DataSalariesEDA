#  Exploratory Data Analysis on Data-Related Jobs

## What is this project about?

<p align='center'> This project has the simple objective to explore data regarding data-related jobs in the world throughout the years of 2020, 2021 and 2022.
                    The years contemplated in this dataset were wisely chosen because, as we know, during the COVID-19 pandemic, these kind of jobs exploded in
                    demand, specially because of digital transformation. Also, it serves as a guideline to control the "Hype" around the data area, trying to show
                    how data jobs salaries per position, country, seniority level etc. behaved during this time interval. 
                    This dataset was extracted from https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries.</p>

## What kind of analysis were done?
<p align='left'> This project followed the "classical" approach to Exploratory Data Analysis, treating the dataset and, after everything is fine, getting statistical
                and analytic insights from it. Here, I'll briefly describe in two bullet points how I did each step:
                - Data Cleaning: first of all, we should look for invalid values in our dataset, such as nulls. More than that, we had an unnamed column that had to be deleted for sake of our analysis. We did this by utilizing Pandas' drop and dropna functions specified to this condition. Utilizing Pandas once more, it was possible to replace job title abbreviations to their full name. For example, SE turns to Senior.
                Also, a "find-replace" method was implemented utilizing country converter, a library that converts country's abbreviations to their full name. For example,
                BR turns to Brazil, UY to Uruguay and so on. This was done purely for readability purposes.  