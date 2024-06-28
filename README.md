# Social Buzz Dashboard
## Introduction





This project contains a **Tableau Dashboard** that provides a detailed analysis and visualization of the Social Buzz dataset, focusing on survival rates, passenger demographics, and key insights.
## Datasets
Below are the details of the Key Columns of the Dataset used for the Dashboard :
- PassengerId: Unique identifier for each passenger.
- Survived: Indicates survival (1) or death (0) of the passenger.
- Pclass: Passenger's class (1st, 2nd, 3rd).
- Name: Full name of the passenger.
- Sex: Gender of the passenger.
- Age: Age of the passenger in years.
- SibSp: Number of siblings/spouses aboard the Titanic.
- Parch: Number of parents/children aboard the Titanic.
- Ticket: Ticket number.
- Fare: Fare paid for the ticket.
- Cabin: Cabin number of the passenger.
- Embarked: Port where the passenger boarded (C, Q, S).
## Data Cleaning

**Missing Values:** The below features had the missing values:
- *Cabin* : I have replaced the Null values with a new Label "Unknown".
- *Embarked* : I have deleted the Null values as it was just 2 among the entire dataset.
- *Age* : As the Age feature has some relationship with Passenger Class, I have replaced the Age with the median w.r.t. each Passenger Class.



**Outliers Values:** The below features had the Outliers values:
- *Age* : This feature follows Normal Distribution. So, I have used the Standard Deviation Method to handle Outliers.
- *Fare* : This feature follows Right Skewed Distribution. So, I have used the Inter Quantile Range Method to handle Outliers.


<img width="300" height="300" alt="box plot" src="https://github.com/Naimuddin74667/Titanic_Dashboard/assets/71082094/3d131067-8c84-48c0-a929-fa94de928930">
<img width="450" height="350" alt="Outliers" src="https://github.com/Naimuddin74667/Titanic_Dashboard/assets/71082094/2f299a66-e010-4bc4-a7ae-678057f722cc">




## Titanic Dashboards
<p align="center">
  <img width="660" height="440" align='centre' alt="Dashboard Image" src="https://github.com/Naimuddin74667/Titanic_Dashboard/assets/71082094/25d6b29f-beae-4dd7-9f27-95e2c0cccd4a">
</p>



- In this dashboard, we can see the details and analyze the number of passengers who Survived or Died, based on multiple parameters and filters. Also, we can view it as Gender.
- We can see the number of passengers per the Passenger Classes (1st, 2nd and 3rd). 
- We can even view the number of passengers Embarked from which location.
- We can observe the rate of survival passengers by Age group.
- A breakdown of the number of passengers embarked by family size. This would allow you to see if there was any correlation between family size and survival rate.

Information about the total number of passengers on board, the number of survivors, and the number of passengers who died.
Links to your data sources. This would allow others to verify your findings and reproduce your analysis.

