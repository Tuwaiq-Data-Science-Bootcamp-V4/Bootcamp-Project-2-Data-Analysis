# Data Preprocessing and Analysis

## Smartphones data analysis
### Introduction 


A system to provide an overview of all smart with accurte details for each phone, our dataset offers a thorough compilation of data on all the most recent cellphones that are currently on the market.


We **aim** to provide a clear vision about latest smartphones and their specifications, and ti give the users the ability to overview about all the smartphonr in the market.

### Dataset Overview
This dataset contain numbers of smart phones available in markets, each entry includes essential attributes such as smartphone model, brand, operating system, display size, processor, RAM, internal storage, camera details, battery capacity, connectivity options, additional features, and market price.


[Dataset Source](https://www.kaggle.com/datasets/abhijitdahatonde/real-world-smartphones-dataset)



### About EDA steps:
- Handling missing values
  ```python
  df['fast_charging'].fillna('',inplace=True)
  df.fillna({'avg_rating':0},inplace=True)
  df['os'].fillna('NAN',inplace=True)
  df.dropna(subset=['processor_speed','battery_capacity'],inplace=True)
  ```

  
- Combine resolution_height and resolution_width camera_resolution

  ```python
  df['camera_resolution']=df['resolution_height'].astype(str)+" x "+df['resolution_width'].astype(str)
  ```
  
- Dropping column resolution_height and resolution_width after combining them into camera_resolution column
  ```python
  df.drop(['resolution_height', 'resolution_width'], axis=1)
  ```
 - Chainging the price from INR to USD
    ```python
    df['price']=np.round((df['price']*0.012))
    ```
 - Dropping some unneeded columns
    ```python
    df.drop(['processor_brand', 'num_cores','primary_camera_front'], axis=1,inplace=True)
    ```


### Final ten insights
**The answers to our 10 queries were our insights**, so the 10 queries is :
1. How common are 5G-enabled phones compared to others phones?
2. Which five brands are the priciest compared to five least expensive brands ?
3. What is the average price for the highest capacity batteries?
4. Which operating system for each brandes used?
5. How many smartphones have one of these capabilities or the ability to fast charge when 5G is available?
6. How does the relationship between a smartphones price and its battery_capacity differ between Apple and Samsung?
7. How does the processor speed of smartphones relate to their prices?
8. How the distribution of screen sizes change in different smartphone brand?
9. What is the average rating of brands?
10. What is the highest battery capacity by brands?





                                                                                                                                                                                                                                                                                                                                          



                                                       


| Team members   | Responsibilities |
|---|---|
|  Taif Ali Alshamrani  | EDA, creating 3 charts  |
|  Rakan Mohammed Almuwainie| EDA, creating 3 charts  |
|  Razan Alqahtani  | EDA, creating 4 charts |


