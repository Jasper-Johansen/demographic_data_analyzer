# Demographic Data Analyzer

This project aims to analyze demographic data from a dataset extracted from the 1994 U.S. Census database. The analysis focuses on understanding various demographic patterns, such as race distribution, average age, education levels, salary information, and more.

The dataset consists of **32,561 rows** and **15 columns**. The columns represent attributes of individuals, including their age, work status, education, marital status, occupation, and more.

### Columns:
- `age`
- `workclass`
- `fnlwgt`
- `education`
- `education-num`
- `marital-status`
- `occupation`
- `relationship`
- `race`
- `sex`
- `capital-gain`
- `capital-loss`
- `hours-per-week`
- `native-country`
- `salary
`
The project uses **Pandas** for data manipulation and analysis, and it's designed to answer several questions related to the data provided.

## Project Overview

The dataset contains information about adults from the U.S. Census, with attributes like age, race, education level, marital status, occupation, and salary.

### Key Questions Analyzed:
1. How many people of each race are represented in this dataset?
2. What is the average age of men in the dataset?
3. What percentage of people have a Bachelor's degree?
4. What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?
5. What percentage of people without advanced education make more than 50K?
6. What is the minimum number of hours a person works per week?
7. What percentage of people who work the minimum number of hours per week have a salary of more than 50K?
8. What country has the highest percentage of people who earn more than 50K, and what is that percentage?
9. Identify the most popular occupation for those who earn more than 50K in India.

## Requirements

- **Python 3.x**
- **Pandas** (install via `pip install pandas`)

## Output

```
Number of each race:
 race
White                 27816
Black                  3124
Asian-Pac-Islander     1039
Amer-Indian-Eskimo      311
Other                   271
Name: count, dtype: int64
Average age of men: 39.4
Percentage with Bachelors degrees: 16.4%
Percentage with higher education that earn >50K: 46.5%
Percentage without higher education that earn >50K: 17.4%
Min work time: 1 hours/week
Percentage of rich among those who work fewest hours: 10.0%
Country with highest percentage of rich: Iran
Highest percentage of rich people in country: 41.9%
Top occupations in India: Prof-specialty
```
