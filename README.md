# IBM Data Science Capstone Project
![Screenshot 2022-10-12 at 10 42 48](https://user-images.githubusercontent.com/115578389/195306159-f07aed76-d4be-4916-8c8e-0b4fffd09834.png)
## Project Introduction
###### 
SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars. Among all components, the first stage does most of the work and is much larger and more expensive than second stage. Sometimes the first stage does not land. Sometimes it will crash. Other times, Space X will sacrifice the first stage due to the mission parameters like payload, orbit, and customer.

Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. In this capstone project, we investigate the landing outcomes and relevant factors that affect the performance by using data science methodology. 

## Methodology
######
**Data Collection**
- Data collection with an API https://api.spacexdata.com/v4/
- Web Scraping https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches

**Data Wrangling** 
- Data Wrangling using API https://api.spacexdata.com/v4/
- Replace the Nulls inside 'PayloadMass' with its mean value
- Convert 'landing_outcomes' to numerical values

**Explortary Data Analysis**
- EDA with Data Visualization 
- EDA with SQL

**Interactive Visual Analysis**
- Build an interactive map with Folium
- Build a dashboard with Plotly Dash

**Predictive Analysis**
- Train the Models and perform Grid Search for each model
- Calculate the accuracy on the test data 
- Determine the model with best accuracy

**Final Report**
- [Winning Space Race with Data Science](https://github.com/JanetZhang128/SpaceX_Project/blob/main/Winning%20Space%20Race%20with%20Data%20Science.pdf).
