# SC1015-Mini-Project-Airline-Passenger-Satisfaction

Welcome to our project on analyzing customer satisfaction data for an airline company! We are a team of three from Nanyang Technological University - Yaxin, Nivedha, and Chaw Kay. The dataset for this project is obtained from Kaggle and contains the data sourced from a survey conducted by airlines on the satisfaction level of passengers/customers based on various factors. With 25 columns such as Age, Gender, Travel class, Arrival and Departure delays, and features that influence customer satisfaction level such as On-board service, Cleanliness, Seat comfort, and Baggage handling, we aim to identify critical factors that impact passenger satisfaction with airline services and provide insights to improve customer service and maintain customer loyalty.






## Background

Passenger satisfaction is a critical factor for the success of any airline. Satisfied passengers are more likely to become loyal customers, provide positive reviews, and recommend the airline to others. On the other hand, dissatisfied passengers may switch to other airlines or share negative feedback, which can impact an airline's reputation and bottom line. Therefore, understanding the factors that influence passenger satisfaction is essential for airlines to improve their services and maintain customer loyalty.

## The Research Question

Our goal is to provide suggestions to the airline company on which categories of services are mainly affecting customer satisfaction and which areas need improvement to attract new customers and retain loyal ones. Through our analysis, we aim to identify significant variables, patterns, and trends that could impact customer service in the aviation industry. Our approach involves creating a classification model from the flight satisfaction survey data to answer the following research question:

"What patterns, trends, and significant variables can be identified from analyzing the airline passenger satisfaction dataset that impact passenger satisfaction levels? Specifically, what are the critical factors that have a significant impact on passenger satisfaction with airline services to improve customer service and maintain customer loyalty in the aviation industry?"

| Procedure | Related Information|
| ---------------- | ---------------- |
| Data Preparation  | Remove unnecessary column , Handle outliers, Check balance of the dataset,Replace rating '0' with mean, Split the dataset into different generations |
| EDA  | Gender, Customer Type, Pre-boarding and onboarding, Age, Class Type |
| Machine Learning  | Decision tree, Random forest, Grid-search, LGBM Classifier by using LazyPredict  |


## Data Cleaning 
Data preparation is a crucial step before conducting exploratory data analysis (EDA) to ensure that the data is clean and relevant. The process involves removing unnecessary columns such as the "ID" column, handling missing values, addressing outliers and checking the balance of the dataset to avoid bias. Upon examining the outliers in the arrival and departure delays, we found it surprising that this variable was not a top predictor for passenger satisfaction levels. So, we decided to look into deeper and analyze whether passengers were still satisfied despite experiencing a delay or if delays had a negative impact on their satisfaction levels.

In addition, we replaced the 0 rating values with the mean rating value to handle the situation where '0' means the rating is not applicable. Lastly, to gain insights into different generations, the dataset is splitted according to different generational groups.

## Visualisation- EDA

In our exploratory data analysis (EDA), we focus on understanding passenger satisfaction levels in different categories such as gender, customer type, pre-boarding and onboarding, age, and travel class type. The purpose of this data visualization is to identify any differences in satisfaction levels across these categories and to better understand what factors impact passenger satisfaction.

By examining these categories, we can gain valuable insights into the factors that influence passenger satisfaction levels and help airlines to improve the overall customer experience for all passengers. Our analysis will include visualizations such as bar charts, scatter plots, and heat maps to provide a clear understanding of the relationships between these categories and passenger satisfaction.

Overall, our goal is to provide a comprehensive analysis of passenger satisfaction levels across different categories and provide actionable insights for airlines to improve the overall customer experience.

## Insights
    As for Gender  has no significant impact on satisfaction as both men and women are equally concerned about the same factors. Analysis shows that the airline has a high percentage of returning passengers, but there is still a high level of dissatisfaction among both first-time and loyal customers.


## Machine Learning





