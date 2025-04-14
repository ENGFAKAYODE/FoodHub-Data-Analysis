
# Foodhub Data Analysis

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

---

## GENERAL OVERVIEW
This project focuses on analyzing customer behavior and satisfaction at Foodhub, an online food delivery platform. By leveraging a customer review dataset, the project aims to uncover insights about the key drivers of customer satisfaction and provide actionable strategies for business improvement.

---

## OBJECTIVE
The main objectives of this analysis are to:
- Identify factors influencing customer satisfaction and dissatisfaction.
- Understand customer sentiment through exploratory and statistical analysis.
- Uncover potential business areas that require optimization for enhanced service delivery.

---

## SKILLS DEMONSTRATED
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Visualization using Python libraries
- Data Manipulation
- Insight generation and business recommendation
- Jupyter Notebook Documentation

---

## DATA SOURCE
The dataset used for this project was obtained from [Foodhub](https://foodhub.com) . It contains detailed records of customer reviews, delivery status, ratings and feedback across multiple orders. The data contained 1898 rows and 9 columns.
![image](https://github.com/user-attachments/assets/7fdd39ab-bd59-4043-9745-f240e92020fd)


---

## DATA TOOLS
- **Python**
- **Pandas** – for data manipulation and analysis
- **Matplotlib & Seaborn** – for data visualization
- **NumPy** – for numerical operations
- **Jupyter Notebook** – for code implementation and documentation

---

## EXPLORATORY DATA ANALYSIS
The dataset underwent a thorough EDA process which included:
- Analyzing missing values and convert data types
- Replacing values
- Exploring customer ratings and feedback patterns
- Visualizing relationships between variables such as delivery time, food preparation time and satisfaction level
- Examining customer demographics and their correlation with satisfaction

---

## QUESTIONS ANSWERED
- What is the minimum, average, and maximum time it takes for food to be prepared once an order is placed? : *20 mins, 27.37 mins, 35 mins*
- How many orders are not rated? : *736*
- Distribution of Cost of order
  <table> <tr> <th style="text-align:center">Histogram</th> <th style="text-align:center">Box Plot</th> </tr> <tr> <td align="center"><img src="https://github.com/user-attachments/assets/8de345d7-4924-4985-8c8c-f4f96be40901" width="400"/></td> <td align="center"><img src="https://github.com/user-attachments/assets/43d9506b-f60f-41c3-8b46-ced7caaed2b8" width="400"/></td> </tr> </table>
- Distribution of rating
  <table> <tr> <th style="text-align:center">Histogram</th> <th style="text-align:center">Box Plot</th> </tr> <tr> <td align="center"><img src="https://github.com/user-attachments/assets/377a4862-5983-42c1-bfa3-6533d2a178a6" width="400"/></td> <td align="center"><img src="https://github.com/user-attachments/assets/6ad63d09-bfcf-40f1-bae5-a4521cf1d275" width="400"/></td> </tr> </table>

 

## DATA ANALYSIS
The analysis revealed:
- Key factors that impact customer ratings include delivery time, food preparation duration, and customer service responsiveness.
- High ratings were often associated with on-time deliveries and quick food preparation.
- Negative reviews frequently mentioned delays and poor customer communication.

---

## RECOMMENDATION
Based on the insights drawn:
- **Optimize Delivery Operations:** Reduce delivery time by partnering with efficient logistics or offering predictive delivery time estimates.
- **Enhance Customer Communication:** Implement proactive customer service updates on order status.
- **Monitor & Improve Food Prep Time:** Set internal benchmarks to reduce prep time without compromising food quality.
- **Gather More Feedback:** Encourage customers to leave detailed reviews to help pinpoint specific service areas needing attention.
