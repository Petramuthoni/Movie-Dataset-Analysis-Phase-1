# Movie-Dataset-Analysis-Phase-1
# Overview
This project involves exploratory data analysis on two box office company movie datasets ,that is, movie revenues and TMDB movie datasets.
# Business Understanding
Microsoft is coming up with movie studio.The aim of this project is to generate actionable insights that Microsoft could use as a guide when producing their own movies to maximize on profit.Microsoft would like to know the type of movies they should consider producing.
# Data Understanding and Analysis
The budgets dataset contains movies financials such as production budget, worlwide gross and domestic gross.
The TMDB dataset contains each movies metadata such as movie title, genre, release date, popularity, vote count to say the least. 
Combining the two datasets into one generates a dataset with 26855 rows and 15 columns
The merged dataset had its own shortcomings such as null values in some rows, incorrect datatypes in the financial columns and unnecessary columns that were not useful for the exploratory analysis
The data cleaning and preparation process involved dropping the unnecessary columns, filling the financial nulls with the mean as well as correcting the financials columns datatypes
After data cleaning, the dataset had 26855 rows and 13 columns.
# Data Analysis Visuals
Research Question 1 (Do movies with high vote_average have high popularity?)
![image](https://github.com/Petramuthoni/Movie-Dataset-Analysis-Phase-1/assets/45505577/b763bd8b-0221-402d-a6b2-cd86dd61b999)
Research Question 2: How did film budgets change from each decade on average?
![image](https://github.com/Petramuthoni/Movie-Dataset-Analysis-Phase-1/assets/45505577/3a933560-a41e-4a97-840f-1ac3041e05d2)
Research Question 3 (Which movies had the highest movie budgets?)
![image](https://github.com/Petramuthoni/Movie-Dataset-Analysis-Phase-1/assets/45505577/5f54949f-a24a-4e22-829a-99e7ed863818)

# Findings
movies that has high vote counts were the most popular movies.

The budget needed to produce movies is bound to increase every decade

The the top three movies with the highest budget are 9 Songs, Beverly Hills Cop and Anatomy of a Murder.These movies are mainly belong to action and drama genres



