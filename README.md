# Foodhub Data Analysis
https://github.com/ENGFAKAYODE/FoodHub-Data-Analysis/blob/main/food%20agg.jpg

## TABLE OF CONTENT
- [GENERAL OVERVIEW](#general-overview)
- [OBJECTIVE](#objective)
- [SKILLS DEMONSTRATED](#skills-demonstrated)
- [DATA SOURCE](#data-source)
- [DATA TOOLS](#data-tools)
- [EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)
- [QUESTIONS ANSWERED](#questions-answered)
- [DATA ANALYSIS](#data-analysis)
- [RECOMMENDATION](#recommendation)


## GENERAL OVERVIEW
The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.

The app allows the restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

## OBJECTIVE
The main objectives of this analysis are to:
- Identify factors influencing customer satisfaction and dissatisfaction.
- Understand customer sentiment through exploratory and statistical analysis.
- Uncover potential business areas that require optimization for enhanced service delivery.

## SKILLS DEMONSTRATED
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Visualization using Python libraries
- Data Manipulation
- Insight generation and business recommendation
- Jupyter Notebook Documentation

## DATA SOURCE
The dataset used for this project was obtained from [Foodhub](https://foodhub.com) . It contains detailed records of customer reviews, delivery status, ratings and feedback across multiple orders. The data contained 1898 rows and 9 columns.
![image](https://github.com/user-attachments/assets/7fdd39ab-bd59-4043-9745-f240e92020fd)

## DATA TOOLS
- **Python**
- **Pandas** – for data manipulation and analysis
- **Matplotlib & Seaborn** – for data visualization
- **NumPy** – for numerical operations
- **Jupyter Notebook** – for code implementation and documentation

## EXPLORATORY DATA ANALYSIS
The dataset underwent a thorough EDA process which included:
- Analyzing missing values and convert data types
- Replacing values
- Exploring customer ratings and feedback patterns
- Visualizing relationships between variables such as delivery time, food preparation time and satisfaction level
- Examining customer demographics and their correlation with satisfaction

## QUESTIONS ANSWERED
- What is the minimum, average, and maximum time it takes for food to be prepared once an order is placed? : *20 mins, 27.37 mins, 35 mins*
- How many orders are not rated? : *736*
  
 ### Univariate analysis
- Distribution of Cost of order
  <table> <tr> <th style="text-align:center">Histogram</th> <th style="text-align:center">Box Plot</th> </tr> <tr> <td align="center"><img src="https://github.com/user-attachments/assets/8de345d7-4924-4985-8c8c-f4f96be40901" width="400"/></td> <td align="center"><img src="https://github.com/user-attachments/assets/43d9506b-f60f-41c3-8b46-ced7caaed2b8" width="400"/></td> </tr> </table>
- Distribution of rating
  <table> <tr> <th style="text-align:center">Histogram</th> <th style="text-align:center">Box Plot</th> </tr> <tr> <td align="center"><img src="https://github.com/user-attachments/assets/377a4862-5983-42c1-bfa3-6533d2a178a6" width="400"/></td> <td align="center"><img src="https://github.com/user-attachments/assets/6ad63d09-bfcf-40f1-bae5-a4521cf1d275" width="400"/></td> </tr> </table>
- Distribution of Food preparation time
  <table> <tr> <th style="text-align:center">Histogram</th> <th style="text-align:center">Box Plot</th> </tr> <tr> <td align="center"><img src="https://github.com/user-attachments/assets/18637962-448f-42be-8fd3-096178161a8d" width="400"/></td> <td align="center"><img src="https://github.com/user-attachments/assets/c3df2c0a-6333-48c8-8804-cd9d0f349f85" width="400"/></td> </tr> </table>
- Distribution of Delivery time
  <table> <tr> <th style="text-align:center">Histogram</th> <th style="text-align:center">Box Plot</th> </tr> <tr> <td align="center"><img src="https://github.com/user-attachments/assets/62d8a5d9-f3aa-44f3-8111-aa15e5e6f9f5" width="400"/></td> <td align="center"><img src="https://github.com/user-attachments/assets/f3e59da8-beec-42a5-99e0-aa19fd2a1a9f" width="400"/></td> </tr> </table>
- Observations on cuisine type:
  *There are 14 cuisine types ['Korean', 'Japanese', 'Mexican', 'American', 'Indian', 'Italian',
       'Mediterranean', 'Chinese', 'Middle Eastern', 'Thai', 'Southern',
       'French', 'Spanish', 'Vietnamese']*
  ![image](https://github.com/user-attachments/assets/8143a088-8672-4d88-a84f-529f116fdcc6)


- Observations on day of the week:
  ![image](https://github.com/user-attachments/assets/78099051-d01b-4f68-a027-e0a8fcb815af)
- No of Restaurants: *178*
- No of Customers: *1200*
- No of Orders: *1898*
- Which are the top 5 restaurants in terms of the number of orders received? *Shake Shack                  (219),
The Meatball Shop            (132),
Blue Ribbon Sushi            (119),
Blue Ribbon Fried Chicken     (96),
Parm                          (68)*
- Which is the most popular cuisine on weekends? *American    (415)*
- What percentage of the orders cost more than 20 dollars? *29.2%*
- What is the mean order delivery time? *24.16*
- The company has decided to give 20% discount vouchers to the top 3 most frequent customers. Find the IDs of these customers and the number of orders they placed:
  *Customer 52832    (13),
Customer 47440    (10),
Customer 83287     (9)*

### Multivariate analysis
- Cost of order vs cuisine_type
  ![image](https://github.com/user-attachments/assets/db05f5da-cb67-467b-b533-8f5a70d53f26)
- Cuisine vs Prep time
  ![image](https://github.com/user-attachments/assets/8795e5bf-2ce0-44ea-a808-f0b73643a946)
- The company wants to provide a promotional offer in the advertisement of the restaurants. The condition to get the offer is that the restaurants must have a rating count of more than 50 and the average rating should be greater than 4. Find the restaurants fulfilling the criteria to get the promotional offer:
  * ['Blue Ribbon Fried Chicken', 'Blue Ribbon Sushi', 'Shake Shack', 'The Meatball Shop']*
- The company charges the restaurant 25% on the orders having cost greater than 20 dollars and 15% on the orders having cost greater than 5 dollars. Find the net revenue generated by the company across all orders: *The company's net revenue is $ 6166.303*
- The company wants to analyze the total time required to deliver the food. What percentage of orders take more than 60 minutes to get delivered from the time the order is placed? (The food has to be prepared and then delivered.): *10.53%*
- The company wants to analyze the delivery time of the orders on weekdays and weekends. How does the mean delivery time vary during weekdays and weekends: *Mean delivery time during weekdays 22.47 seconds
, Mean delivery time during weekends 28.34 seconds*

## INSIGHTS
1. Deliveries take more time on weekends
2. 80% of the time, food gets delivered less that 60 minutes from the time it was ordered 
3. The company's net revenue is $ 6166.303
4. Restaurants eligible for the promotional offer 
 ['Blue Ribbon Fried Chicken', 'Blue Ribbon Sushi', 'Shake Shack', 'The Meatball Shop']


## RECOMMENDATION
Based on the insights drawn:
1. It must be ensured that more delivery persons are available on weekends
2. Marketing should be enhanced for Vietnamese, Spanish and Korean cuisines because they underperformed compared to others, 
a survey for customers also be conducted to understand customer's preferences
3. Special discount for returning customers should be introduced, the most frequent customer has just 13 orders, followed by another with 10 orders indicating limited repeat business.
