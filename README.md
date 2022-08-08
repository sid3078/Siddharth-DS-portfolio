# Siddharth-DS-portfolio
I did Post Graduate course in Data Sceince from University of Texas. This potfolio showcases projects completed by me during the program.

# Project 1 : Re-cell Used Phone Pricing Analysis

Buying and selling used phones and tablets used to be something that happened on a handful of online marketplace sites. But the used and refurbished device market has grown considerably over the past decade.The rising potential of this comparatively under-the-radar market fuels the need for an ML-based solution to develop a dynamic pricing strategy for used and refurbished devices. ReCell, a startup aiming to tap the potential in this market, want you to analyze the data provided and build a linear regression model to predict the price of a used phone/tablet and identify factors that significantly influence it.

Data Dictionary

    brand_name: Name of manufacturing brand
    os: OS on which the device runs
    screen_size: Size of the screen in cm
    4g: Whether 4G is available or not
    5g: Whether 5G is available or not
    main_camera_mp: Resolution of the rear camera in megapixels
    selfie_camera_mp: Resolution of the front camera in megapixels
    int_memory: Amount of internal memory (ROM) in GB
    ram: Amount of RAM in GB
    battery: Energy capacity of the device battery in mAh
    weight: Weight of the device in grams
    release_year: Year when the device model was released
    days_used: Number of days the used/refurbished device has been used
    normalized_new_price: Normalized price of a new device of the same model in euros
    normalized_used_price: Normalized price of the used/refurbished device in euros




![image](https://user-images.githubusercontent.com/110747132/183455722-dc91cefa-1664-4687-a5e9-8525a62c99a7.png)

![image](https://user-images.githubusercontent.com/110747132/183455913-7f6acbc1-c43f-47d9-8873-c813ed74ac87.png)

Key Findings:-
- We can see that RMSE on the train and test sets are comparable. So, our model is not suffering from overfitting. MAE indicates that our current model is able to predict price within a mean error of 0.18 units on the test data. Hence, we can conclude the model "ols_3" is good for prediction as well as inference purposes.

- For business my recommendations Surprisingly 5G has a negative coefficinet RAM, main camera, and screensize are very important parametrs for phone pricing. They impact the pricing positivively and are very significant Normalised new prices are ofcourse positively linked This machine learning model can predict used phone prie pretty accurately. Still human intervention is suggested for final checks.



# Project 2 : E-New Express

This project used statistical analysis, a/b testing, and visualization to decide whether the new landing page of an online news portal (E-news Express) is effective enough to gather new subscribers or not. The simulated dataset has certain important metrics such as converted status and time spent on the page that will help to conclude the effectiveness of the new landing page. Apart from that, the dependence of conversion on the preferred language will also be analyzed in this project.

Data Dictionary

    user_id - Unique user ID of the person visiting the website
    group - Whether the user belongs to the first group (control) or the second group (treatment)
    landing_page - Whether the landing page is new or old
    time_spent_on_the_page - Time (in minutes) spent by the user on the landing page
    converted - Whether the user gets converted to a subscriber of the news portal or not
    language_preferred - Language chosen by the user to view the landing page

![image](https://user-images.githubusercontent.com/110747132/183462549-4fcbdd41-cbea-4f49-880a-33ad04cb436e.png)
![image](https://user-images.githubusercontent.com/110747132/183463044-2f9748cb-91b2-4baa-8b05-7d74ea38c000.png)
![image](https://user-images.githubusercontent.com/110747132/183462943-0d6ea9fb-4c8f-47ef-ae26-ffa2a86c21b9.png)


Key Findings:-

- The users spend more time on the new page.
    -This indicates that the outline & recommended content of the new page is more likely to keep customers engaged long enough to make a decision to subscribe
- The conversion rate for the new page is greater than the conversion rate of the old page
    -This indicates that the new page is more likely to gather new subscribers than the existing page
- The conversion status is independent of the preferred language
- The time spent on the new page does not differ with the language of the content
    - This indicates that irrespective of the language, the outline & recommended content of the new page are engaging
- It is recommended that the news company uses the new landing page to gather more subscribers
    =The business logic would be to design a page that people spend time in, conversion will follow




# Project 3 : FoodHub Data Analysis

The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. They want to analyze the data to draw some actionable insights for the business. As a Data Scientist in this company I am required to work on some of the key questions that need to be answered. I performed the data analysis to find answers to these questions that will help the company to improve the business.

Data Dictionary

    order_id: Unique ID of the order
    customer_id: ID of the customer who ordered the food
    restaurant_name: Name of the restaurant
    cuisine_type: Cuisine ordered by the customer
    cost_of_the_order: Cost of the order
    day_of_the_week: Indicates whether the order is placed on a weekday or weekend
    rating: Rating given by the customer out of 5
    food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. 
    delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. 


![image](https://user-images.githubusercontent.com/110747132/183268450-93a3118b-ed68-4dd4-a22c-986973bfea5b.png)
![image](https://user-images.githubusercontent.com/110747132/183268792-d785141e-b05c-4c95-b8ab-4f82e52c8fa3.png)

Key Findings:-
- The restaurants fulfilling the criteria to get the promotional offer are: 'The Meatball Shop', 'BlueRibbon Fried Chicken', 'Shake Shack' and 'Blue Ribbon Sushi'.
- The net revenue generated on all the orders given in the dataset is around 6166.3 dollars.
- Approximately 10.54 % of the total orders have more than 60 minutes of total delivery time.
- The mean delivery time on weekdays is around 28 minutes whereas the mean delivery time onweekends is around 22 minutes.
- Around 80% of the orders are for American, Japanese, Italian and Chinese cuisines. Thus, it seems that these cuisines are quite popular among customers of FoodHub. 
