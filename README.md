# Zomato-data-analysis

## Project Overview
This project is a simple data analysis of the Zomato company, focusing on exploring and visualizing data from a Zomato dataset. The project is done using Python, leveraging libraries like Pandas, Matplotlib, Seaborn, and others to brush up on data analysis and visualization skills.
This project analyzes the Zomato dataset to derive insights about the restaurants listed on the platform. Key aspects include:
- Restaurant types and their distribution
- Online ordering trends
- Relationship between restaurant types and delivery availability
- Couple order analysis
- Rating range analysis

The project uses the following Python libraries:
- **Pandas**: For data manipulation and analysis
- **Matplotlib**: For basic plotting and visualizations
- **Seaborn**: For advanced visualizations and heatmaps
- **Jupyter Notebook**: For running the analysis


## Key Insights

### 1. **Restaurant Type Distribution**
   - The majority of restaurants fall under the `Dining` category, followed by `Cafes`, `Buffets`, and `Others`.
   
   ![Screenshot 2024-09-27 202246](https://github.com/user-attachments/assets/17ddaa08-ad97-4130-8538-478ee25560b6)

   **Conclusion**: Most restaurants in the dataset are categorized as dining restaurants, which indicates that sit-down dining experiences are more prevalent in this dataset.

### 2. **Rating Distribution**
   - Most restaurants received ratings between 3.5 and 4.0, with a few outliers.
   
  ![Screenshot 2024-09-27 202525](https://github.com/user-attachments/assets/fd69544c-a4dd-48df-ae12-bffe79f63b2c)

   **Conclusion**: The majority of restaurants received ratings in the 3.5-4.0 range, indicating a fairly positive customer response.

### 3. **Cost Preferences for Couples**
   - The preferred approximate cost for two people is around ₹300, followed by a price range of ₹200 to ₹500.
   
  ![Screenshot 2024-09-27 202707](https://github.com/user-attachments/assets/4e1bfc23-e2e7-452f-aa8c-93c5a1b3a8a4)

   **Conclusion**: Couples typically prefer restaurants where the average cost for two people is around ₹300, making it the most popular price range.

### 4. **Impact of Online Orders on Ratings**
   - Restaurants with online ordering systems generally received higher ratings compared to those without online ordering options.
   
![Screenshot 2024-09-27 202830](https://github.com/user-attachments/assets/53d2fd19-eef6-4bae-9ef4-01acd02b6aac)

   **Conclusion**: Restaurants offering online orders received higher ratings, suggesting that online ordering convenience positively influences customer satisfaction.



### 5.**Popularity Based on Restaurant Type**
   - `Dining` restaurants have received significantly more votes compared to `Buffets`, `Cafes`, and `Others`.
   
   ![Screenshot 2024-09-27 202417](https://github.com/user-attachments/assets/54141868-0b39-4f7a-8ff5-f12bdc7a26d7)

   **Conclusion**: Dining establishments are leading in popularity according to customer votes, suggesting that these types of restaurants are preferred over others.


### 6. **Impact of Online Orders Across Different Dining Types**
   - Dining type 3 (most likely representing traditional dine-in restaurants) shows a high frequency of not offering online orders.
   - Conversely, there is an indication that cafes (possibly represented by dining type 5) have more instances of offering online orders.
   
  ![Screenshot 2024-09-27 202931](https://github.com/user-attachments/assets/63eefd45-a7d9-4925-95fc-9caa1a2495c3)

   **Conclusion**: Traditional dine-in restaurants tend to not offer online ordering as frequently as other types such as cafes do. This could suggest a preference for in-person dining experiences at these establishments while highlighting convenience through digital platforms for more casual or quick-service venues like cafes.

## Recommendations

Based on the insights gathered from the Zomato data, here are some actionable recommendations for restaurant owners and managers:

1. **Focus on Dining Experiences**: Since the majority of restaurants are categorized as dining, restaurant owners should invest in improving the sit-down dining experience. Enhancing ambiance, service quality, and menu variety can attract more customers to this category.

2. **Improve Online Order Systems**: Restaurants with online order capabilities generally received higher ratings. It is recommended that restaurants that do not yet offer online orders should consider implementing this feature to improve customer satisfaction and attract a larger audience.

3. **Target Price Range Around ₹300**: Since a large number of customers prefer restaurants where the average cost for two is around ₹300, restaurants should consider offering menu options that cater to this price range. This will help in attracting couples and price-sensitive customers.

4. **Focus on Customer Feedback for Ratings**: As most restaurants have ratings between 3.5 to 4.0, there is room for improvement. Restaurant owners should actively seek customer feedback and address any areas of improvement to boost ratings and customer loyalty.

5. **Optimize Marketing for Cafes and Buffets**: While dining is the most common category, cafes and buffets have a significant presence as well. Restaurants in these categories should focus on niche marketing strategies, like promotions, offers, or loyalty programs, to attract more customers.
   quently as other types such as cafes do. This could suggest a preference for in-person dining experiences at these establishments while highlighting convenience through digital platforms for more casual or quick-service venues like cafes.



## Data Structure

The dataset used in this project contains several key columns that provide valuable information about each restaurant. The primary columns include:

- **name**: The name of the restaurant.
- **online_order**: Indicates whether the restaurant accepts online orders (Yes/No).
- **book_table**: Indicates whether the restaurant allows table booking (Yes/No).
- **rate**: The average rating of the restaurant.
- **votes**: The number of votes the restaurant has received.
- **approx_cost(for two people)**: The approximate cost for two people dining at the restaurant.
- **listed_in(type)**: The type of restaurant (e.g., Buffet, Cafes, Dining, etc.).

The data is structured in a tabular format, making it easy to manipulate and analyze using Python's powerful data analysis libraries.

Example of the dataset structure:

| name              | online_order | book_table | rate | votes | approx_cost(for two people) | listed_in(type) |
|-------------------|--------------|------------|------|-------|-----------------------------|------------------|
| Jalsa             | Yes          | Yes        | 4.1  | 775   | 300                         | Dining           |
| Spice Elephant    | Yes          | No         | 4.1  | 787   | 200                         | Dining           |
| San Churro Cafe   | Yes          | No         | 3.8  | 918   | 300                         | Cafes            |
| Addhuri Udupi Bhojana | No       | No         | 3.7  | 166   | 150                         | Dining           |
| Grand Village     | No           | No         | 3.8  | 123   | 200                         | Dining           |

This structure allows for comprehensive analysis and visualization of various aspects of the restaurant data, leading to actionable insights and recommendations.
