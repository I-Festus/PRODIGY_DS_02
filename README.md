# PRODIGY_DS_02
# Titanic Analysis
The RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after it collided with an iceberg during its maiden voyage from Southampton to New York City.

# Project Overview
There were an estimated 891 passengers and crew aboard the ship, and more than 500 died, making it one of the deadliest commercial peacetime maritime disasters in modern history. 

The RMS Titanic was the largest ship afloat at the time it entered service and was the second of three Olympic-class ocean liners operated by the White Star Line. The Titanic was built by the Harland and Wolff shipyard in Belfast. Thomas Andrews, her architect, died in the disaster.

# Objectives
The aim of this project is to determine what factors contributed to the chances of survival, and what can we learn from the historical event. Through our investigation, we hope to gain a deeper understanding of the people who perished on the Titanic and reflect on the lessons we can learn from historical data to inform our understanding of the present and future.

The tool used for this analysis was Python (Jupyter Notebook).

# Data Source
This data was gotten from kaggle https://www.kaggle.com/c/titanic/data
Ensure that train.csv is in the working directory

# Data
This data contains;

- Survival (0=No, 1=Yes)
- Passenger Class (Pclass) [1=1st Class, 2=2nd Class, 3=3rd Class]
- Sex = Sex of Passenger
- Sibsp = Number of Siblings and spouses onboard the titanic
- Parch = Number of parents and children aboard the titanic
- Ticket = ticket number
- Cabin = Cabin number
- Embarked = Point of embarkation [C = Cherbourg, Q = Queenstown, S = Southampton]

# Insights

![image](https://github.com/user-attachments/assets/b21d740d-e426-47f4-a767-455bf4d14357)

- The majority of individuals are around **age 30**, as shown by the peak in the chart.  
- The age distribution is roughly **normal** in shape, with a central peak and tapering tails.  
- There are **fewer individuals** below age 10 and above age 70.  
- The distribution is **slightly right-skewed**, with a longer tail toward older ages.  
- The spread shows most ages fall between **20 and 40**.  

![image](https://github.com/user-attachments/assets/c9ebe587-0726-4bfe-9b47-feb7e8ce288d)

- **More males survived** compared to females, as indicated by the taller bar for males.  
- The number of female survivors is **significantly lower** than male survivors.  
- Gender seems to have had an impact on survival rates, with **males forming the majority of survivors**.

![image](https://github.com/user-attachments/assets/957a4966-1836-49e8-bc87-cfa51ab71f36)

- **Pclass 3** has the highest number of passengers, exceeding **500**.  
- **Pclass 1 and 2** have significantly fewer passengers, each around **200**.  
- The majority of passengers traveled in **Pclass 3**, indicating it was the most common class.  

![image](https://github.com/user-attachments/assets/3ec684a4-4c1e-473e-ae7f-f057101858aa)

- Most fares are below **100**, with a few outliers above **300**.  
- Majority of passengers are aged **20-50**.  
- Higher fares are linked to younger individuals.  
- Survival (darker points) does not show a strong pattern with age or fare.


![image](https://github.com/user-attachments/assets/46f9ad00-0f26-41f8-9484-db3c46d00d7e)

- There are significantly more **male passengers** (over 500) compared to females.  
- The number of **female passengers** is approximately **300**, making them the minority.  
- Males constituted the **majority** of passengers in this dataset.

![image](https://github.com/user-attachments/assets/b6ec2fe0-2a02-4621-92b4-29a47ec5e04d)

- **Pclass 1** has the highest survival rate, with more survivors than non-survivors.  
- **Pclass 2** shows nearly equal numbers of survivors and non-survivors.  
- **Pclass 3** has the lowest survival rate, with significantly more non-survivors than survivors.  
- Passengers in **Pclass 1** had a better chance of survival compared to lower classes.  

# Conclusion
The Titanic analysis reveals that survival was influenced significantly by gender and class. Women and passengers in **Pclass 1** had higher survival rates, while **Pclass 3** and males faced greater risks. Age and fare showed weaker correlations to survival, but younger passengers with higher fares tended to have slightly better outcomes. This highlights the unequal impact of the disaster across demographic groups.

# Contact
- Linkedln: http://www.linkedin.com/in/festus-ijabani-159585293
- Email: ijabanifestus01@gmail.com
