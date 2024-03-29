# Data Professional Survey | Power BI

###

This dashboard presents insights derived from a survey within the data profession, exploring factors such as geographical distribution, programming language preferences, average salary by job title, average salary by gender, salary satisfaction rating , and other relevant metrics.

<br>

![image](https://github.com/TendaiPhikiso/Data-Professional-Survey-PowerBI/blob/main/PowerBI-Dashboard.png)

###

## Data Cleaning 
Before delving into data insights, the initial step involved addressing various structural errors within the provided dataset using Power Query. This included column pruning, where unnecessary columns were removed, and utilizing the 'Split Column' feature to restructure multiple columns like 'What Industry do you work in?' and 'Which Title Best Fits your Current Role?' to make the data suitable for analysis. Additionally, a key task was converting salary ranges to a numerical representation. This process entailed extracting numerical values from the salary range and converting them into a numeric format to facilitate the calculation of the average salary.

By thoroughly cleaning the data, the integrity of the dataset was maintained, creating a solid foundation for meaningful analysis.

## Data Visualisation - Case Study Questions

Delving into the specifics of our survey data, a noteworthy observation is the presence of <b>650</b> survey takers with an average age of 30, rounded.

### 1.What is the geographical distribution of survey takers?

![image](https://github.com/TendaiPhikiso/Data-Professional-Survey-PowerBI/assets/57633068/f71f95df-5f7e-48a2-a1b0-5238b7d1a40d)
Examining the tree map provides a visual representation of the countries from which survey participants originate: Canada, India, the United Kingdom, and the United States. Upon interacting with the tree map in Power BI, we have identified that out of 630 participants, 5.08% are from Canada, 11.59% from India, 6.35% from the United Kingdom, and a significant 41.43% from the United States. The remaining 35.56% falls into the 'Other' category.

### 2. How difficult is it to break into the data industry?
![image](https://github.com/TendaiPhikiso/Data-Professional-Survey-PowerBI/assets/57633068/69359426-cdbd-4084-91cf-34af81350562)

The pie chart indicates that survey takers have different views on getting into the data industry. 42.7% find it neither easy nor difficult, while 24.76% consider it difficult, 21.27% find it easy, 6.98% difficult, and 4.29% very easy. The distribution indicates a diversity of perspectives on the difficulty of entering the data industry. Understanding these varied perceptions is crucial for individuals aspiring to break into the data world, as it provides insights into the challenges and opportunities they might encounter, helping them make informed decisions and better navigate their career paths.

### 3. What is the rating of work/life balance for survey takers and how satisfied are they with their salary?

![image](https://github.com/TendaiPhikiso/Data-Professional-Survey-PowerBI/assets/57633068/b6ae8366-b3d6-4747-9963-683124e9992b)

Upon analyzing the gauge chart, it’s evident that there is a significant difference between the average rating for work/life balance (5.74/10) and salary satisfaction (4.27/10). The higher work/life balance rating implies that, on average, respondents view this aspect positively. However, the lower salary satisfaction rating suggests that respondents may feel their current compensation levels do not align with the value they place on their contributions.

### 4. What is the average salary based on gender?
![image](https://github.com/TendaiPhikiso/Data-Professional-Survey-PowerBI/assets/57633068/9c186988-7be9-4f75-b0c4-7fbe798cc185)

The ring donut chart illustrates average salaries by sex, revealing a minimal difference between genders. Females have an average salary of $55,000, while males closely follow with $53,000, indicating a narrow gap in earnings.

### 5. what is the average salary based on job title?
![image](https://github.com/TendaiPhikiso/Data-Professional-Survey-PowerBI/assets/57633068/35245a99-94eb-4e7d-a77b-9735a529e4e9)

The bar chart provides a clear overview of data roles & their avg salary, with Data Scientist leading at an average of over 80K, followed by Data Engineer and Data Architect, both averaging over 50K. This information is valuable for understanding the salary distribution across various data roles, highlighting the top-paying positions in the field.

### 6. What is the top favourite programming language?
![image](https://github.com/TendaiPhikiso/Data-Professional-Survey-PowerBI/assets/57633068/e83fc5f3-c245-4b96-a95e-57af19fcba3c)

The chart highlights Python as the top favourite language with a vote of over 300, R programming language follows with a vote of over 80. These two languages distinctly stand out as the preferred programming choices due to their extensive use in the field of data.

## Data Source
The data used in this project is sourced from Alex Freberg. 
