# IST3134 – Large-Scale Traffic Accident Analysis Using Apache Spark

## Project Overview

This project implements a Big Data Analytics solution using Apache Spark to analyse the US Accidents dataset. The analysis focuses on accident distribution by state, accident severity, and weather conditions.

## Dataset

The project uses the US Accidents dataset from Kaggle:

https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

The original dataset is not uploaded to this repository because of its large file size. It can be downloaded from the Kaggle source above.

## Technologies Used

- Python
- PySpark
- Apache Spark
- Spark RDD
- Spark SQL
- Spark DataFrame
- Google Colab
- Google Drive

## Analyses Performed

### 1. Accident Distribution by State

MapReduce is used to count the number of accidents recorded in each US state.

### 2. Accident Severity Analysis

MapReduce is used to calculate the number of accidents for each severity level.

### 3. Weather Condition Analysis

MapReduce is used to calculate accident frequencies for different weather conditions.

## Implementation Approaches

Three Spark-based approaches are implemented:

1. RDD MapReduce
2. Spark SQL
3. Spark DataFrame

The RDD implementation explicitly demonstrates the Map and Reduce stages, while Spark SQL and DataFrame operations provide alternative approaches for comparison.

## Source Code

The complete implementation is provided in:

`IST3134_US_Accident_Analysis.ipynb`

The notebook includes:

- PySpark configuration
- Spark session creation
- Dataset loading
- Data inspection
- Data cleaning
- MapReduce implementation
- Spark SQL analysis
- Spark DataFrame analysis
- Result verification
- Output generation
- Spark execution-time measurement

## Output Files

The generated analysis results are provided in:

- `State_Analysis.csv`
- `Severity_Analysis.csv`
- `Weather_Analysis.csv`

## Execution Environment

The project was implemented and executed using Google Colab with Apache Spark and PySpark.
