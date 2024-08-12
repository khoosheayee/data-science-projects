# Revolutionizing Bus Routes: A Data-Driven Approach 

## Project Overview
In bustling urban environments, optimizing travel efficiency while maintaining public safety is crucial. This project creates a model to propose alternative bus routes that minimize exposure to high-risk areas, thereby enhancing safety and efficiency.

## Contents
- `Revolutionizing Bus Routes. A Data-Driven Approach.ipynb`: Jupyter notebook containing the data analysis and modeling code.
- `DS project _Revolutionizing Bus Routes-A Data Driven Approach _Shea Yee.pdf`: Project report summarizing the findings and methodologies.

## Project Value Proposition
1. **Public Bus Commuters**: The model offers optimized bus routes tailored to different scenarios, enhancing travel safety and efficiency.
2. **Government and Bus Operators**: Collaborating with government agencies and bus operators to integrate the model into existing systems can significantly improve scheduling and routing. This partnership aims to create a more efficient and effective public transit system.

## Methodology
The proposed solution employs a dual approach to optimize bus routes effectively. First, unsupervised machine learning techniques are applied to identify and cluster COVID-19 high-risk areas. Second, a supervised machine learning model forecasts passenger volume at specific locations and times. These combined models generate alternative bus routes that reduce exposure to high-risk zones and high passenger volume areas while minimizing travel distance.

1. **Data Collection**: 
   - This project utilizes seven datasets sourced from:
     - **Singapore Ministry of Health (MOH)**: Provides detailed COVID-19 case data.
     - **Land Transport DataMall**: Includes passenger volume data for train stations and lists of MRT and LRT stations with geographic coordinates.
     - **Land Transport Authority (LTA)**: Offers details on public bus routes and a list of bus stops with geographic coordinates.
   - Datasets are obtained from Kaggle and Data.gov.sg.

2. **Data Preparation**: 
   - Datasets are merged to consolidate relevant features into a single dataframe for machine learning model development.
   - Data cleaning involves removing unnecessary columns and addressing inconsistencies.
   - Feature engineering includes extracting geographic coordinates using `geopy.geocoders` and encoding categorical features for regression model training.

3. **User Interface Development**: 
   - A user interface is developed using the Tkinter library, allowing users to input travel information (Day, Time, Start Point, End Point).

4. **Model Development & Performance Assessment**: 
   - Three sub-models are developed:
     - **Unsupervised Learning**: Techniques such as KMeans, DBSCAN, and hierarchical clustering are used to identify COVID-19 clusters by latitude and longitude. The most effective clustering model is selected based on density.
     - **Supervised Learning**: Models including Linear Regression, Lasso Regression, Decision Trees, Random Forest, Gradient Boosting, K-Nearest Neighbors, and Neural Networks are employed, with the best model chosen based on performance metrics.
     - **Route Generation**: A third sub-model generates all possible bus routes based on user inputs.

5. **Models Integration**: 
   - The final model integrates the three sub-models to generate optimal public bus routes for various scenarios:
     - Minimize distance without considering COVID-19 high-risk areas.
     - Minimize distance while reducing exposure to COVID-19 high-risk areas.
     - Minimize distance while avoiding both COVID-19 high-risk areas and high passenger volume zones.


## Insights
This project has developed a model that enhances the public bus system by suggesting safer and more flexible routes for commuters. By leveraging unsupervised learning to identify hazardous clusters and supervised learning to predict passenger volumes, the model provides a comprehensive approach to optimizing bus routes.
