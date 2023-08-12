# Global Youtube Statistics

## Team Member

| Team Member | Responsibilities |
|-------------|-----------------------------------------------------| 
| Abdullah Alturki  | EDA , two chart for  Data Visualization , mrakdown  file             |
| Raghad Alghofaili | Data collection  , EDA , two chart for  Data Visualization  , organize the final file ipynb                |
| Alaa Alsalman| Data collection , three chart for  Data Visualization  | 
| Anwar Almutlaq   | EDA ,  three chart for  Data Visualization                  |

## Introduction

In today's digital landscape, YouTube stagings as a dominant force, shaping the way we consume, create, and share content worldwide. With billions of users and an immense volume of videos, YouTube's influence spans industries and cultures. However, navigating this vast data ocean to comprehend YouTube's intricate impacts and emerging trends necessitates a systematic and rigorous analysis.

## Problem Statement
The meteoric rise of YouTube has engendered a complex landscape that poses significant challenges in untangling its intricate dynamics. As content creators, marketing professionals, and data analysts endeavor to leverage its massive potential, there is an urgent demand for detailed insights that can inform effective, data-driven strategies. The primary hurdle resides in distilling meaningful patterns and trends from the extensive constellation of available data and metrics.

## Objectives

The primary goal of this project is to conduct a thorough analysis of global YouTube statistics, with a specific focus on the following objectives:

1. **Exploration of Key Metrics** : A deep dive into essential metrics such as views, subscribers, engagement rates, and beyond, to demonstrate trends and discrepancies across various Countries and content categories.

2. **Identification of Influential Factors**: The seclusion and examination of elements that donate to the success of YouTube content, including variables such as video view, frequency of subscribers, and content genre.

3. **Uncovering of Geographic Patterns**: A thorough investigation into how user behaviors and importance diverge across geographical locales, shedding light on cultural influences.

4. **Provision of Insights for Stakeholders**: The delivery of actionable insights to authorize content developers, marketers, researchers, and any individuals or entities desiring anyone aiming to navigate the dynamic world of YouTube.

## Dataset Overview and Source

- **Description**: This dataset contains information about various YouTube channels and their statistics for the year 2023. It includes data on subscribers, video views, earnings, content details, and channel characteristics.

- **Number of Entries (Rows)**: 987 entries.

- **Number of Columns (Features)**: 21 columns.

- **Column Details**:

  - *rank: Rank of the YouTuber.*
  - *Youtuber: Name of the YouTuber.*
  - *subscribers: Number of subscribers the YouTuber has.*
  - *video views: Total number of video views for the YouTuber.*
  - *category: Category or genre of the content.*
  - *Title: Title of the content.*
  - *uploads: Number of uploads by the YouTuber.*
  - *Country: Country associated with the YouTuber.*
  - *video_views_rank: Rank based on video views.*
  - *channel_type_rank: Rank based on the channel type.*
  - *video_views_for_the_last_30_days: Video views in the last 30 days.*
  - lowest_monthly_earnings: Lowest monthly earnings for the YouTuber.
  - highest_monthly_earnings: Highest monthly earnings for the YouTuber.
  - lowest_yearly_earnings: Lowest yearly earnings for the YouTuber.
  - highest_yearly_earnings: Highest yearly earnings for the YouTuber.
  - created_year: Year in which the channel was created.
  - created_month: Month in which the channel was created.
  - created_date: Date in which the channel was created.
  - subscribers_per_video: Average number of subscribers per video.
  - channel_age_months: Age of the channel in months.
  - channel_age_category: Categorical representation of channel age.

- **Missing Data**: The dataset not have any missing values after we apply EDA .

- **Memory Usage**: The dataset approximately 163.1 KB of memory.

- **Source**: The dataset from Kaggle and can be accessed using the following link: [Global YouTube Statistics 2023](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023).

## Insights from Dataset
1. It is clear that United State has most number of channels, it has more than 300 channels.
2. Entertaiment category is the most channel type on Youtube however, travel&Event is the least type.
3. Examine the correlation between video views and subscribers to identify a positive relationship that can be utilized in linear regression analysis.
4. Utilizing a box plot that incorporates category and creation year reveals that creators across different categories predominantly initiated their channels post-2015, with a majority not exhibiting outliers.
5. with pie chart the highest channel in terms of the age of the channel is YouTube
6. with bar chart the country with the least video uploads out of the ten is the United States
7. The country with the highest video uploads out of the ten is India with scatter plot , and Most of the number of uploads is between 0 and 30,000

8.  Youtube is a platform for documenting things through videos, as evidenced by the fact that People & Blogs is the third most popular category.
9. Entertainment and music are the most popular industries throughout most of the continent.
10. Entertainment would be one of the highest-paying categories given the number of subscribers that these channels bring to YouTube, but as it turns out, it pays less than a lot of other, less popular categories.



