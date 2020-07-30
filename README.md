# codechef-phase2
Exploratory Data Analysis

I have performed Task 3 from the given data science questions. In this task, I have conducted an EDA on the given coronavirus dataset using Python in a Jupyter Notebook. Libraries used: Pandas, NumPy, matplotlib and seaborn.

Steps followed:
Understanding the data- I went through the dataset to understand how the data is provided and what analysis I can perform
Data cleaning- A crucial step in data analysis. After deciding the analysis to be performed I removed the columns that will not be contributing to the study.
Descriptive analysis- To describe the basic features of the dataset and obtain a summary of the data. From this analysis I concluded the following:
-total no. of rows: 148365
-total no. of columns(after cleaning): 4
-none of the columns can store null values
-total number of countries covered in our dataset: 188
Plotting the data- I have created two visualisations based on different aspects of data

Total number of deaths: In a recent interview with Fox News, Donald Trump claimed that the USA had the lowest mortality rate in the world, however, neither did the data with       the reporter nor the data with him suggested this. This gave me the idea to study the number of deaths in each country and display the top 10 to see the worst-affected      nations. 
Conclusion: From the data plot, it is concluded that the USA has the highest number of deaths and India is at number 6 among the 188 countries in our dataset.

Situation in India: Ever since the national lockdown was lifted we have seen a drastic increase in the number of cases so much that states are again headed for the lockdown to control the situation. I compared the situation in India from May 2020 to July 2020 in terms of daily number of confirmed cases, deaths and recoveries. 
Conclusion: The data plot gave the expected results. The increase in the number of daily confirmed cases is 509.585%(for the two given dates) which a drastic increase showing that the situation in India is not under control. The death rate is good as the number of deaths being reported on both dates is below 5000. There is an improvement in the number of daily recoveries.

I would like to thank CodeChef SRM for providing me the opportunity to conduct this analysis.
