# Customer-Satisfaction-Analysis-on-Airline-Data
Project Overview

This project focuses on analyzing customer satisfaction levels based on data from the cleaned_air dataset. The dataset contains information about customer demographics, flight details, and service ratings, allowing us to uncover patterns and insights that impact customer satisfaction. The analysis aims to help the airline identify areas for improvement and develop strategies to enhance customer experience.
________________________________________
# Dataset Description

The cleaned_air dataset is sourced from a MySQL database and contains the following key attributes:
1.	Customer Demographics:
o	Customer ID
o	Gender
o	Age
o	Customer Type (Loyal/Disloyal)
2.	Flight Details:
o	Type of Travel (Business/Personal)
o	Class (Economy, Eco Plus, Business)
o	Flight Distance
o	Departure/Arrival Delay in Minutes
3.	Service Ratings (1 to 5 scale):
o	Inflight Wifi Service
o	Leg Room Service
o	Baggage Handling
o	Inflight Entertainment
o	Cleanliness
o	Check-in Service
4.	Customer Satisfaction:
o	Satisfaction (Satisfied/Neutral or Dissatisfied)
________________________________________
# Project Objectives

1.	Perform exploratory data analysis (EDA) to uncover insights and trends.
2.	Visualize the relationship between customer satisfaction and key variables such as demographics, travel type, and service ratings.
3.	Identify factors that significantly influence customer satisfaction.
4.	Provide actionable recommendations to improve customer experience.
________________________________________
# Analysis and Visualizations

The project includes the following visualizations to interpret customer satisfaction trends:
1.	Satisfaction Levels by Gender: Understanding how satisfaction varies between male and female customers.
2.	Satisfaction by Customer Type: Comparing satisfaction rates between loyal and disloyal customers.
3.	Satisfaction by Travel Type: Analyzing differences in satisfaction for business versus personal travel.
4.	Age Distribution by Satisfaction: Examining how age impacts customer satisfaction.
5.	Satisfaction Levels by Travel Class: Comparing satisfaction levels across Economy, Eco Plus, and Business classes.
6.	Correlation Heatmap: Identifying relationships between service ratings and satisfaction levels.
7.	Flight Distance vs. Satisfaction: Exploring how flight distance affects satisfaction.
8.	Impact of Delays on Satisfaction: Analyzing the effect of departure and arrival delays.
9.	Cleanliness vs. Satisfaction: Understanding the impact of cleanliness ratings on customer experience.
10.	Check-in Service Influence: Assessing how check-in service ratings correlate with satisfaction.
11.	Delay Distribution: Visualizing the percentage of customers affected by delays.
________________________________________
# Technologies Used

1.	Python Libraries: 
o	pandas: Data manipulation and preprocessing.
o	matplotlib and seaborn: Data visualization.
o	sklearn: Machine learning for feature importance analysis.
2.	MySQL: Data extraction from the database.
3.	Jupyter Notebook: Interactive environment for coding and visualization.
________________________________________
# How to Run the Project

1.	Prerequisites:
o	Install the necessary Python libraries using the following command: 
o	pip install pandas matplotlib seaborn scikit-learn
o	Ensure access to the cleaned_air dataset in MySQL.
2.	Steps:
o	Extract the data from MySQL into a CSV file (cleaned_air.csv).
o	Load the dataset into a Jupyter Notebook.
o	Run the provided Python code to execute all visualizations and analyses.
________________________________________
# Insights from the Analysis

1.	Loyal customers report significantly higher satisfaction levels compared to disloyal customers.
2.	Business travelers are generally more satisfied than personal travelers.
3.	High ratings for inflight entertainment, cleanliness, and check-in service positively correlate with satisfaction.
4.	Long delays have a strong negative impact on customer satisfaction.
5.	Passengers in Business Class report the highest satisfaction levels.
________________________________________
# Strategic Recommendations

1.	Improve the economy class experience by enhancing services like seating, entertainment, and overall comfort.
2.	Focus on minimizing flight delays through better operational planning and scheduling.
3.	Personalize services based on customer demographics and preferences.
4.	Retain loyal customers through exclusive rewards and superior service offerings.
5.	Invest in employee training to improve service quality, particularly in cleanliness, inflight entertainment, and check-in processes.
________________________________________
# Conclusion from the Analysis

1.	Satisfaction Levels Vary by Customer Demographics: Gender and age play a role in determining satisfaction levels. Loyal customers tend to have higher satisfaction rates compared to disloyal customers.
2.	Type of Travel Impacts Satisfaction: Business travelers generally report higher satisfaction compared to those on personal travel, likely due to different service expectations and priorities.
3.	Service Features Influence Satisfaction: Features like inflight entertainment, cleanliness, and check-in service significantly affect customer satisfaction. High ratings in these areas correlate with higher satisfaction levels.
4.	Delays Are a Major Dissatisfaction Factor: Long departure and arrival delays are strongly associated with lower satisfaction, as seen from the analysis of delay data.
5.	Class of Travel Correlates with Satisfaction: Business and premium economy class passengers report higher satisfaction than economy class passengers, likely due to better service offerings.
________________________________________
# Strategic Recommendations

1.	Enhance Economy Class Experience: Focus on improving services in the economy class, such as better seating, inflight entertainment, and complimentary services, to boost satisfaction for a larger customer base.
2.	Reduce Delays with Operational Improvements: Implement stricter on-time performance measures, such as optimizing ground operations and better scheduling, to minimize delays and improve satisfaction.
3.	Personalize Customer Experience: Use insights from customer demographics (e.g., age, gender, and travel type) to personalize services and promotions, catering to specific needs and preferences.
4.	Focus on Loyal Customer Retention: Continue to prioritize loyal customers by offering rewards, exclusive perks, and superior service to maintain their high satisfaction levels.
5.	Invest in Service Training: Enhance employee training programs to improve service quality, especially in critical areas like inflight entertainment, cleanliness, and check-in services, ensuring consistent customer satisfaction across all touchpoints.





