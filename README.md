# YouTube Trending Videos Analysis Project 📊

## Introduction and Objectives 🎯

This project aims to analyze YouTube trending videos data to gain insights into video popularity, viewer engagement, and other key aspects. The project utilizes the dataset available on [Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new) containing information about various attributes of YouTube videos.

## Team Members 👥

1. Rayan Aloufi: (Responsibilities)
2. Khalid Alhumaidan: EDA and Data cleaning.
3. Hussam: (Responsibilities)

## Dataset Overview and Source 📈

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new). It includes information about video details, such as video ID, trending date, title, channel, category, views, likes, dislikes, comment count, and more.

## Data Preparation and Cleaning 🧹

The following steps were taken to prepare and clean the dataset for analysis:

- Unnecessary columns were dropped.
- Categories were obtained from the JSON dataset.
- Data was merged with category information.
- Rows with 0 likes and 0 dislikes were removed.
- Dates were formatted and transformed as needed.
- Data was normalized using Min-Max scaling.
- A sample subset of the data was created for further analysis.

## Charts and Insights 📊

The analysis includes various charts to visualize trends and relationships within the data:

1. Average Views per Category 📈
2. Distribution of Views 📊
3. Likes vs. Dislikes Scatter Plot 📈
4. Number of Videos per Category 📊
5. Likes, Dislikes, and Comments Box Plot 📊
6. Pair Plot of Numerical Columns 📊
7. Average Likes for Videos with and without Disabled Comments 📊
8. Average Dislikes for Videos with and without Disabled Comments 📊
9. Distribution of Videos by Category (Pie Chart) 📊
10. Correlation Matrix (Heatmap) 📊
11. Trends in Views over Time (Line Chart) 📈
12. Trends in Likes and Dislikes over Time (Line Chart) 📈

## WordCloud of Video Titles (Extra) 💬

A WordCloud was generated from the unique video titles to visualize the most common words used in video titles.

## Pandas Profiling 📋

Additionally, a Pandas Profiling report was generated to provide a comprehensive overview of the dataset.

For detailed code and explanations, please refer to the Python code provided in this repository.
