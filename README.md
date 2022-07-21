# DATA SAFETY PROJECT

----
# Introduction
This project is contains the dataset of work accident in the XYZ LIMITED COMPANY.The management of XYZ LIMITED COMPANY intends to reduce the accident occurence at the company's faculty.To do this important decision must be made by looking at the data of past incident occurrence,asking important question to know how to prevent future incident occurrence or reduce it to the bare minimum.

![image](https://user-images.githubusercontent.com/107173369/180140943-7b39461a-2f12-4b22-9619-eeff7ccc8546.png)
---
# PROBLEM STATEMENT 
The managerial questions needed to be answered are the following :

The total numbers of workers who have had accident since 2020 till date.

Total cost incurred due to accident ( Workers health related cost ).

Total days lost (worker away from work or delayed work) due to accident.

How many incident occur in depatrment

Incurred cost during the month by due to the treatment of workers based on their work category

incurred cost by the year 

Total numbers of workers by gender

Total number of incident occurred in each categories of worker 

# DATA SOURCING 

The data for this project was sourced from 

https://www.contextures.com/xlsampledata01.html#safety

the writeup of XYZ LIMITED is a fictional company.

# DATA CLEANING

The first step of of cleaning this data is to change the format of the DATE column from general to date format. Then, after that custom formating of the date column is done changing the data from m/d/yy to d/m/yy

 A new column is added to the dataset to set to group the data from the age group column into categories ( Experienced worker,Interns,New worker,New workers,Professional) for easy analysis and representation. This was done using the IF function 
 
 Another column was added to the data set to reference the month number to month name CHANGE MONTH COLUMN FROM NUMBER FORMAT TO LETTER FORMAT EG 1 = JAN 
 
 ![image](https://user-images.githubusercontent.com/107173369/180157191-00b4de81-6561-4dc3-8585-4665916f0455.png)

# DATA ORGANIZING

To derive answer to the managerial question,pivot table was drawn in other to summerise our data into answe our questions to draw conclusion
![image](https://user-images.githubusercontent.com/107173369/180159358-e4d6f8da-8d3d-44ff-83ee-be3fc24bc48a.png)

# DATA VISUALIZATION
The data of the project was visualize to summerize the answer to our data set for easy assimilation of the management team for fast decision making prpcess
![image](https://user-images.githubusercontent.com/107173369/180160822-ff38bc04-49a2-46b9-8a83-7c7d77701758.png)

# FINDINGS FROM THE DATA SET

After the data has been analysed carefully to derive answer for the management team , we find out the following;

The total number of workers who have that accident during work is 514 from 2020 till the data of this analysis

The sum of $ 717,795 was incurred as a result of treatment of worker's accident

The total days lost in the span of 3 years due to accident is 378.5 days (.5 being half of the day)

--- more answers to the management questions are visualize in the dashboard.

# RECOMMENDATION
From the insights derived, we can say there id not much  gap difference between the occurence of the type of incident.No incident type take priority than the order due the not clear cur=t differences.All preventive measures and safety eqipment should be deployed for the workers.

looking at the workers category by number of occurence, during the period of 3 years,the New workers category are the most affected though there is no much difference to experienced workers ( 26 occurrence difference).This data do not cover why but perphaps because they perform more of the work than the other categories of workers. whatever the case they sshould be given priority.

it is glaring that we have more men to women who have had accident, this is obiviously because of the population of men to women in the workforce.

The company has been improving in minimizing the level of accident risk at work since 2020.this ia commendable. WE CAN STILL DO BETTER.
