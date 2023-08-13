# Data Analysis Project: Company Call Analysis

## Introduction

In this data analysis project, conducted by:
- Mohammed Alharbi : Data Collection , Data Descreption and Markdown.
- Saeed Qahhas : Data Visualization.
- Sadeem Fihrah : EDA and Pandas Profiling. 

We have thoroughly analyzed call data within the company using Python's data analysis libraries. The project addressed a challenge faced by the company's communication department, which struggled to gain meaningful insights from the call records. Our analysis aimed to visualize call patterns, identify trends, and optimize communication strategies.

## Problem Statement

The communication department within the company was struggling to understand call patterns due to complex and unclear call data. The existing call records lacked insights, making it difficult to optimize communication strategies. The communication department sought a data analysis solution to assist them in:

- Visualizing call volume trends over time.
- Identifying peak call hours and days.
- Recognizing call durations and patterns.

## Dataset

The dataset used for this analysis contained information about calls within the company. It included fields like call timestamp, caller name, receiver name, call duration, and the departments.

## Tools and Libraries Used

We employed the following tools and libraries for this analysis:

- using python in jupyter platform
- pandas
- matplotlib.pyplot
- numpy
- seaborn
- datetime
- pandas profiling

## Insights
1. The majority of the calls in the dataset have been answered Which is 54 percent of the total calls
2. The pie chart shows a relatively balanced distribution between answered and unanswered calls
3. The pie chart shows a relatively balanced distribution between answered and unanswered calls
4. Answered Calls Duration ranges from 0 to 1,700 seconds
5. We can observe that the majority of call durations are relatively short, with a few longer duration calls
6. The line plot shows the trend of total income calls over time.
7. You can identify the points where the total income call volume reaches its highest peaks these peak periods can  provide valuable information about the factors that contribute to increased call volume, such as marketing campaigns, promotions, or seasonal demand.
8. Similarly, you can identify periods where the total income call volume is relatively low
9. The chart highlights periods when call frequency is particularly high or low. These periods may correspond to specific events, marketing campaigns, or external factors that influence call volume.
10. Financial accounting receive the highest call volumes 
11. The bar chart highlights the top 5 departments with the highest call volumes These departments are likely to have a significant impact on customer service, as they handle a substantial number of calls.
12. Departments with higher mean numeric values indicating superior performance.
13. Departments with lower mean numeric values suggesting areas for improvement.
14. We can observe which departments have higher or lower counts of calls compared to others.
15. The donut chart shows that the proportion of calls are equal
16. Call types with higher median values indicate a longer "Ring_time_per_second" on average.

## Approach

1. **Import Required Libraries**: We imported necessary Python libraries for data manipulation, analysis, and visualization.

2. **Load and Preprocess Call Data**: The call dataset was loaded into a pandas DataFrame. We converted the call timestamps to datetime format and extracted relevant date and time components. Unnecessary columns were removed from the dataset.

3. **Exploratory Data Analysis (EDA) on Calls**: We calculated basic statistics of the call data. A line plot was created to visualize the daily call volume trends over time, helping us identify general call activity trends.

4. **Insights and Visualizations**: Peak call hours were identified by determining the most common call times. Calls were segmented based on departments to understand call volume distribution.

5. **Conclusion**: Our analysis provided insights into call volume trends, peak hours, and department-specific patterns. We highlighted how optimizing communication strategies based on these insights could enhance the communication department's efficiency.
