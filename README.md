# Social Buzz Dashboard
## Introduction
This project contains a **Tableau Dashboard** that provides a detailed analysis and visualization of the Social Buzz dataset, focusing on survival Segments, Categories, Content type and key insights.
## Datasets
Below are the details of the Key Columns of the Dataset used for the Dashboard :

### Content Type Dataset:
Key Columns are :
- Content ID: A unique identifier for each content item.
- User ID: A unique identifier for the user who interacted with the content.
- Type: The type of content, e.g., "photo."
- Category: The category or context of the content, e.g., "Studying," "healthy eating."
- URL: The web address where the content is stored or accessed.
### Reactions Dataset:
Key Columns are :
- Content ID: A unique identifier for each content item.
- User ID: A unique identifier for the user who interacted with the content.
- Type: The type of emotion or state associated with the content.
- Datetime: The date and time when the interaction was recorded.
### Reaction Type Dataset:
Key Columns are :
- Type: The type of emotion or state.
- Sentiment: The emotional tone (positive, negative, or neutral).
- Score: The intensity or strength of the emotion, represented as a numerical value.
## Dataset Relationship
Reactions Dataset is the main dataset and also has the relationship with Reaction Type and Content.
<img width="402" alt="Dataset Relation" src="https://github.com/Naimuddin74667/Social_Buzz_Dashboard/assets/71082094/03f7de20-87ec-4a5f-a479-fda511b9c537">

## Data Cleaning
**Removing Unwanted Values:** The below features are not useful for analysis:
- *URL* : Provide the web address where the content is stored or accessed is not useful for analysis.
- *User ID* :  Gives a unique identifier for the user who interacted with the content and it's not useful.

**Dropping Null Values:** *Type* features has 980 missing values i.e. 0.04% of the total data.

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

