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

## Data Cleaning
**Removing Unwanted Values:** The below features are not useful for analysis:
- *URL* : Provide the web address where the content is stored or accessed is not useful for analysis.
- *User ID* :  Gives a unique identifier for the user who interacted with the content and it's not useful.

**Dropping Missing Values:** 
- *Type* features has 980 missing values i.e. 0.04% of the total data.

**Handling Duplicate Entries & Remane:** 
- *Category* features has some values that are same but due to minor differences it got duplicated.

## Dataset Relationship
Reactions Dataset is the main dataset and also has the relationship with Reaction Type and Content.
<img width="402" alt="Dataset Relation" src="https://github.com/Naimuddin74667/Social_Buzz_Dashboard/assets/71082094/03f7de20-87ec-4a5f-a479-fda511b9c537">

## Social Buzz Dashboards
<p align="center">
  <img width="660" alt="Social Buzz Dashboard" src="https://github.com/Naimuddin74667/Social_Buzz_Dashboard/assets/71082094/85c20b57-83f9-42a6-9f4b-1e44fab69871">
</p>



- In this dashboard, we can see the details and analyze the number of passengers who Survived or Died, based on multiple parameters and filters. Also, we can view it as Gender.
- We can see the number of passengers per the Passenger Classes (1st, 2nd and 3rd). 
- We can even view the number of passengers Embarked from which location.
- We can observe the rate of survival passengers by Age group.
- A breakdown of the number of passengers embarked by family size. This would allow you to see if there was any correlation between family size and survival rate.

Information about the total number of passengers on board, the number of survivors, and the number of passengers who died.
Links to your data sources. This would allow others to verify your findings and reproduce your analysis.

