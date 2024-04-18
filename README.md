## Instacart Vegetarian User Purchase Behaviour
<p align="center">
  <img src="https://github.com/musairshad/Instacart-user-analysis/blob/main/Images/VegNews.jpeg?raw=true" width="400" height="300" alt="Description of Image">
</p>




### Business problem
In the competitive grocery market, understanding vegetarian customer behavior is crucial for targeted promotions and product recommendations. We aim to leverage machine learning to predict whether a vegetarian user is ordering a specific food product for the first time (0) or re-ordering a familiar item (1).
This will enable us to:
- Personalize recommendations: Recommend new and relevant food products to vegetarian users based on their past purchases (re-orders) and overall buying trends.
- Optimize promotions: Design targeted promotions for first-time vegetarian purchases of specific products, potentially attracting new customers or encouraging them to try new items.
- Improve customer experience: Enhance customer satisfaction by offering personalized recommendations and relevant promotions, leading to increased loyalty and repeat business.
By predicting re-orders vs. first-time purchases for vegetarian users, we can gain valuable insights into their buying habits and personalize our marketing strategies to drive sales and customer engagement.

### Data Understanding

- Data Source :https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis?select=order_products__prior.csv 
  
- Publicly available on Kaggle
- Contains over 5 million instances of orders made via Instacart grocery shopping app
- Indicates the frequency of order placements
- Specifies whether orders were reordered or not
### Data Exploration and cleaning
Combined four datasets (products, aisles, orders, departments) and filtered for food-related orders. Managed missing values in "days_since_prior_order" by removing rows with missing values. The dataset shows a slight imbalance, with more re-orders than initial orders.

### EDA
#### Top 10 most ordered food products in merged dataset
<p align="center">
  <img src="https://github.com/musairshad/Instacart-user-analysis/blob/main/Images/Top%2010%20food%20products.png?raw=true" width="400" height="300" alt="Description of Image">
</p>

#### First time order and reordered in merged dataset
<p align="center">
  <img src="https://github.com/musairshad/Instacart-user-analysis/blob/main/Images/number%20of%20food%20related%20orders%20and%20reorders.png?raw=true" width="400" height="300" alt="Description of Image">
</p>
#### Distribution of days since prior order

<p align="center">
  <img src="https://github.com/musairshad/Instacart-user-analysis/blob/main/Images/days%20since%20prior%20order.png?raw=true" width="400" height="300" alt="Description of Image">
</p>

Most frequent reorders are between 4-8 days

#### Vegetarian User analysis
<p align="left">
  <img src="https://github.com/musairshad/Instacart-user-analysis/blob/main/Images/top%2020%20first%20time%20orders.png?raw=true" width="400" height="300" alt="Description of Image">
</p>
<p align="right">
  <img src="https://github.com/musairshad/Instacart-user-analysis/blob/main/Images/top%20first%2020%20items%20for%20first%20time%20order.png?raw=true" width="400" height="300" alt="Description of Image">
</p>

