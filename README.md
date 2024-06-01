IMDb Movies Analysis Project
This repository contains the analysis of the IMDb movies dataset to investigate the factors influencing the success of a movie on IMDb. The success is defined by high IMDb ratings, which is crucial information for movie producers, directors, and investors.

Dataset Description
The dataset contains information about various movies and includes the following details:

Total Rows: 5043
Total Columns: 28
IMDb registered users can cast votes on released titles, and these individual votes are aggregated to summarize a single IMDb rating, reflecting the popularity of a movie among the public.

Objective
To identify the factors that influence a movie's success on IMDb, the dataset was cleaned, analyzed, and various statistical methods were applied to derive insights.

Approach
Data Cleaning:

Removed unnecessary columns that are not required for the analysis.
Cleared rows containing any null values, reducing the dataset to 3884 rows.
Removed duplicate movies using the remove duplicates function.
Tech Used:

Microsoft Excel
Analysis:

Movie Genre Analysis: Analyzed the distribution of movie genres and their impact on the IMDb score.
Movie Duration Analysis: Examined the distribution of movie durations and identified the relationship between movie duration and IMDb score.
Language Analysis: Determined the most common languages used in movies and analyzed their impact on IMDb scores.
Director Analysis: Identified the top directors based on their average IMDb score and analyzed their contribution to the success of movies using percentile calculations.
Budget Analysis: Explored the relationship between movie budgets and their financial success, and identified the movies with the highest profit margin.
Key Findings
The maximum number of movies belong to the Drama genre.
Movies with durations between 100-120 minutes have the highest frequency, but the highest average IMDb scores are found in movies with durations of 221-240 minutes.
The majority of movies are in English (95% of the dataset), with Italian movies having the highest standard deviation in IMDb scores.
Steven Spielberg has directed the maximum number of movies (25), but Tony Kaye has the highest average IMDb score.
"Avatar" has the maximum profit, while "Paranormal Activity" has the highest profit percentage, indicating potential data anomalies.
Conclusion
This project provided valuable insights into the factors influencing movie success on IMDb. It highlighted the importance of data cleaning, the use of tables for analysis, and dealing with databases for desired outcomes.
