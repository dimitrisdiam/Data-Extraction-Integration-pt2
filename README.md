# Data Integration & Preparation Project - 2

## Overview
This project is part of an academic course on Data Integration & Preparation, focusing on profiling relational data, entity resolution, and data preparation techniques. It utilizes various data manipulation and matching techniques to ensure data quality and usefulness.

## Team Members
- Dimitrios Diamantidis
- Johan Hensman
- Nicky Schilperoort 

## Project Structure

### Task 1: Profiling Relational Data
- Analysis of the `accident_index` to count unique accident occurrences in 2022.
- Statistical profiling of the `age_of_casualty` column including minimum, maximum, mean, median, and standard deviation calculations.
- Identification and counting of null values and analysis of data correlation.

### Task 2: Entity Resolution
- Utilization of pandas to manage dataframes, along with functions to normalize and preprocess data.
- Implementation of various string matching techniques (Levenshtein, Jaro, Gap) to calculate similarities between records.
- Development of an entity resolution approach using composite similarity scores and a recognition system for matching records above a similarity threshold.
- Optimization discussions and execution time comparisons between two distinct methods, emphasizing the effectiveness and efficiency of data processing techniques.

### Task 3: Data Preparation
- Correlation analysis among several medical test result columns after addressing data quality issues, such as erroneous zero entries.
- Application of data cleaning methods, including the replacement of zero values with NaN and subsequent imputation with mean values.
- Reevaluation of correlations post-cleanup to assess the impact of data preparation on data integrity and analysis reliability.

## Technologies Used
- Python
- Libraries: Pandas, PyStringMatching
