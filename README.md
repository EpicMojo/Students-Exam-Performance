# Students-Exam-Performance
The purpose of this project is to find the factors that affect students' reading and writing exam performances the least and most. There are 8 scatter plots and a heatmap. 4 of the 8 plots compare reading scores to genders, types of lunches, test preparedness, and parental levels of education, while the other 4 plots compare writing scores to the same four variables. The heatmap displays the correlation values between all of the variables.

The datasest was collected from Aman Chauhan on Kaggle. The dataset contains 1,000 students' math, reading, and writing test scores as well as the variables that could affect their performance (gender, race/ethnicity, parental level of education, lunch type, and test preparation course completion). Here's the link: https://www.kaggle.com/datasets/whenamancodes/students-performance-in-exams

'gender' = 'male' or 'female' values

'parental level of education' = amount of formal education the parent(s) have had

'lunch' = type of lunch provided by school ('standard' or 'free/reduced')

'test preparation course' = whether or not student took a course to prepare for test

'reading score' = value of student's score on reading test

'writing score' = value of student's score on writing test

There are no null values or outliers in this dataset nor are there any other known errors within the dataset or with the process of collecting the raw data. The 'gender' column only contains 'male' and 'female' values, excluding any other possible gender.

This dataset was downloaded from a user on Kaggle (Aman Chauhan) and processed by deleting the 'math score' and 'race/ethnicity' columns. These columns were deleted because the math scores did not fit the focus of the project and the race/ethnicity of the students were made anonymous. The reading and writing scores were compared to the same variables (gender, parental level of education, lunch type, and test preparation course completion) using linear regression analysis. Each type of test has their own set of plots (4 plots for each type of test). After the plots were made, a heatmap was created to show the correlation between all of the features. The average value of correlation was then sepparately calculated for the 'gender', 'parental level of education', 'lunch', and 'test preparation course' columns.
