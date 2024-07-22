# Crime Analysis

## Project Overview
This project seeks to address the challenge of optimizing law enforcement resource allocation and improving public awareness of crime trends. By utilizing natural language processing (NLP) and clustering techniques, we aim to identify crime hotspots and trends over time, thereby aiding law enforcement and public information efforts.

## Contents
- `Crime Analysis.ipynb`: Jupyter notebook containing the data analysis and modeling code.
- `DS project_ Shea Yee_ Crime Analysis_ 13 July 2024.pdf`: Project report summarizing the findings and methodologies.

## Methodology
1. **Data Collection**: 
   - This historical dataset contains 13,087 press releases from the Department of Justice's (DOJ) website, sourced from [Justice.gov](https://www.justice.gov/news).
   - The dataset is retrieved from [Kaggle's Department of Justice 2009-2018 Press Releases Dataset](https://www.kaggle.com/datasets/jbencina/department-of-justice-20092018-press-releases).

2. **Data Preprocessing**: 
   - NLP techniques were used to extract 'location' and 'crime type' from press releases.
   - Data cleaning followed the NLP step to remove minority rows with None values.

3. **Exploratory Data Analysis (EDA)**: 
   - Analysis of crime rates over the years and insights gathered from the data.

4. **Modeling**: 
   - Unsupervised machine learning techniques such as KMeans, DBSCAN, and hierarchical clustering were used to cluster by 'latitude' and 'longitude'.

## Insights
In summary, this project has developed and applied advanced methodologies for analyzing crime data, focusing on NLP and clustering techniques. By leveraging these methods, we are able to effectively identify geographical crime clusters and trends over time. These insights can significantly enhance law enforcement strategies by facilitating more targeted resource allocation and empowering proactive measures to combat crime effectively.

## Value Proposition
1. **Resource Allocation**: Efficient deployment of police resources to high-crime areas.
2. **Public Awareness**: Transparent communication about crime trends and increased community vigilance and safety.
