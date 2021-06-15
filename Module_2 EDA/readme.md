Module 2: Exploratory Data Analysis
The project’s goal is to track the impact of living conditions of students of the age group  15-22 on their math performance in order to identify students at risk at an early stage.
You can do this using the model  predicting the results of the state examination in mathematics for each student of the school. The obtained resulta help determining the parameters of the future model, conduct an intelligence analysis of the data and compile a report based on its results.
An approximation model should be built to predict exam mark for each student. To get a training sample it's necessary to select important features from given dataset stud_math.xls.”
 
The stages of the project work:
The dataset analysis, including general view of the table,
Rename the columns to more convenient and standard view names, 
Analysis of each column for empty values, incorrect values, etc. based on the cleared data, identify the correlation of characteristics.
 
Final conclusions:
There are not too many NaN values in the dataset. But some of them were found in the score column, therefore it was important to delete them as our study is based on the math examinations of the students and the future approximation model "score". 
There are only 2 columns that are numerical in the dataset--age and absences.
There were found 3 outliers in whole dataset: 40 in 'father’s education', which I have replaced for 4 as I believe it’s a typo, than father´s education -1 in 'family relationships' which I have replaced for 1 as I believe it’s a typo as well. 
And finally 22 in age, which I have not change or delete as this age is within our focus group. 
The column studytime and studytime, granular had a negative correlation; therefore I have deleted it from the dataset. 
As we can see on the basis of correlation and statistical analysis the following features have statistically significant differences, these are sex, age, address', mother’s education', mother’s job, failures, paid, higher, romantic, absences. 

Answers to self-reflection questions:
 
1. What was your role in the team?
No team, no team work…
 
2. What part of your job were you most satisfied with?
The project result in general.
 
3. What didn't work out for you? What else is worth working on? 
I had some problems planning the work order. 
 
4. What interesting and useful things did you learn in this module?
I was good to refresh my knowledge of statistic after so many years. Also Exploratory Data Analysis is a great tool to work in! 
 
 
5. What is the main result of this project?
The project itself, I´ve gained new skills to analyse main features in dataset and use them for further approximation model building.
 
6. What skills can you already apply in your current work?
None at present time.
 
7. Do you plan to study additional materials on the project topic?
That’s for sure. 
    