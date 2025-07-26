![mind](mentalhealth.jpg)
# Mental Health Analysis of University Students

This project explores the mental health of international and domestic students at a Japanese university, based on a 2018 survey. The analysis investigates the relationship between student type, length of stay, and key mental health indicators like depression, social connectedness, and acculturative stress.

# Analysis Overview

This notebook uses PostgreSQL to analyze the students dataset to test the findings of a study suggesting that international students have a higher risk of mental health difficulties. The primary question explored is:


How does the length of stay affect the mental health of international students?

The analysis filters the data to focus exclusively on international students. It then groups these students by their length of stay (in years) and calculates several key metrics for each group:

Count of students: To understand the sample size for each duration of stay.

Average depression score (PHQ-9): To measure levels of depression.

Average social connectedness score (SCS): To assess feelings of belonging.

Average acculturative stress score (ASISS): To quantify the stress of adapting to a new culture.

The results are ordered by the length of stay to observe any trends or correlations between how long a student has been in the country and their mental well-being.

# Technologies Used

PostgreSQL
