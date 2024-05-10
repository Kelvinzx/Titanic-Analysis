# Titanic-Analysis

## Table of Content

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploring Data Analysis](#exploring-data-analysis)
- [Results and Findinds](#results-and-findings)
- [Insights Gained](#insights-gained)
- [Conclusion](#conclusion)
  
### Project Overview
To analyze the Titanic dataset and extract valuable insights regarding 
passenger demographics, survival rates, and other relevant factors.

<img width="635" alt="Survival Analysis" src="https://github.com/Kelvinzx/Titanic-Dataset/assets/147884934/0cc744b6-5d7c-48d0-8814-b82768c00cb0">

<img width="621" alt="Demographics" src="https://github.com/Kelvinzx/Titanic-Dataset/assets/147884934/716eda9d-3404-4242-88e9-6917b887c81d">

<img width="623" alt="Family Size" src="https://github.com/Kelvinzx/Titanic-Dataset/assets/147884934/1e77c8e5-6735-4ab9-aba0-35cafdee4bc0">

<img width="613" alt="Fare" src="https://github.com/Kelvinzx/Titanic-Dataset/assets/147884934/18d85d56-0aaf-4cf2-bf23-245afd599a75">




### Data Source

Titanic passenger data: The primary dataset used for this project is the "titanic.csv" file, containing detailed infromation about the passengers that boarded the ship.

### Tools 
- Excel - The data was provided in an Excel CSV format
  -  [download here](https://drive.google.com/file/d/1CeDs4T3Z-IrC4dbxEVe8SyGf5K-z_l6B/view?usp=sharing)
- Power BI - Data Cleaning - Data Analysis - Creating Reports

### Data Cleaning and Preparation

In the initial data preparation phase, i performed i performed the following tasks:
1. Data loading and inspections
2. Handling missing values and outliers
3. Data cleaning and formating using DAX

### Exploring Data Analysis

EDA involves exploring the passengers demographics to answer the following questions

1. Data Modeling:
- Define relationships between different tables (e.g., Passenger, Ticket, Fare).
- Create calculated columns or measures to enrich the dataset with additional 
insights.
2. 🧑‍🤝‍🧑Survival Analysis:
- Calculate the overall survival rate of passengers.
- Analyze survival rates based on factors such as gender, age, and passenger 
class.
3. Demographic Analysis:
- Explore passenger demographics using visualizations like bar charts and pie 
charts.
- Analyze the distribution of age, gender, and passenger class among the 
passengers.
4. 👪Family Size Analysis:
- Investigate the impact of family size (SibSp and Parch) on survival rates.
- Visualize survival rates for passengers traveling alone versus those with family 
members.
5. 💰Fare Analysis:
- Explore fare distribution based on passenger class

### Results and Findings

- Survival Rates:
  
The overall survival 
rate was approx. 
38.38%
-Females had 
higher survival rate 
(74%) than 
male(19%)
-Passengers below 
18years had the 
highest survival rate
-First class 
passengers had the 
highest survival rate

- Demographic Distribution:

Most passengers 
were adults, with a 
smaller proportion 
being children & 
seniors.
-More male 
passengers than 
female passengers.
-Most passengers 
were in 3rd class

- Family Size Impact:
  
Solo travelers had
a lower survival 
rate(30.35%) 
compared to those 
traveling with 
family(50.56%)

- Fare Distribution:
First-class 
passengers had the 
highest median 
fare, followed by 
second-class and 
third-class 
passengers.

- Embarkation Port Analysis:
Passengers 
embarking from 
port C (Cherbourg) 
had the highest 
survival rate, 
followed by port Q 
(Queenstown), and 
port S 
(Southampton) had 
the lowest survival 
rate.

### Insights Gained

- Socioeconomic Status and Survival

 One of the key insights from the Titanic data set is the strong relationship between a passenger's socioeconomic status, as measured by their ticket class, and their chances of survival. Passengers in first class had a significantly higher survival rate compared to those in lower classes, highlighting the disparities in access to resources and opportunities during the disaster.

- Gender Differences in Survival

Another notable finding is the gender-based differences in survival rates. The data shows that women had a higher survival rate than men, likely due to the societal norms and protocols at the time that prioritized the evacuation of women and children first. 

- Importance of Family Ties

 According to the Titanic data set, passengers who were traveling with family members like spouses or children had a better chance of surviving than those who were traveling alone. This emphasizes the significance of social connections and support networks in times of crisis.

### Conclusion

The Titanic dataset is like a treasure trove for researchers in data science and machine learning. It helps us understand why some passengers survived the Titanic disaster while others didn't. We've learned a lot about how factors like social status and gender play a role. Moving forward, we can use this data to explore things like where people were from or what jobs they had to see how these affected their chances of survival. We also need to think about the fairness of what we find. Plus, the lessons we learn can be applied to making emergency plans better today. So, in simple terms, this dataset is a goldmine for learning from the past and making things safer in the future.


 


