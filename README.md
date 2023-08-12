# Data Preprocessing and Analysis

## Smartphones data analysis
### Introduction 


A system to provide an overview of all smart with accurte details for each phone, our dataset offers a thorough compilation of data on all the most recent cellphones that are currently on the market.


We **aim** to provide a clear vision about latest smartphones and their specifications, and ti give the users the ability to overview about all the smartphone in the market.

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


### Final 10 insights
**The answers to our 10 queries were our insights**, so the 10 queries is :
1. How common are 5G-enabled phones compared to others phones?

     Most of the smartphone have 5G feature .

3. Which five brands are the priciest compared to five least expensive brands ?

     Vertu is the most expensive brand, and lyf is the least expensive brand.

3. What is the average price for the highest capacity batteries?

     In the least battery capacity the price was higher then dropped until tha battery’s capacity was more than 20000.

4. which operating system for each brandes used?

     Most of the smartphones brands use Android OS except Apple.

5. How many smartphones have one of these capabilities or the ability to fast charge when 5G is available?


     The majority of the smartphones provide 5G and faster charging features.


6. How does the relationship between a smartphones price and its battery capacity differ between Apple and Samsung?

     higher battery capacity tend to have lower prices.

7. How does the processor speed of smartphones relate to their prices?

     As the processor speed increases, the price generally increases.

8. How the distribution of screen sizes change in different smartphone brand?

     Many brands offer smartphones with screens of varying sizes.

9. What is the average rating of brands?

     Brands with higher bars have higher average ratings.

10. What is the highest battery capacity by brands?

     Brands with higher bars have higher maximum battery capacities, indicating the brands that provide smartphones with      larger batteries.






                                                                                                                                                                                                                                                                                                                                          



                                                       


| Team members   | Responsibilities |
|---|---|
|  Taif Ali Alshamrani  | EDA, creating 3 charts  |
|  Rakan Mohammed Almuwainie| EDA, creating 3 charts  |
|  Razan Alqahtani  | EDA, creating 4 charts |


