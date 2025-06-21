# Predicting Minecraft Newsletter Subscription

## Introduction

The goal of this project is to analyze the relationship between player characteristics and their likelihood of subscribing to a Minecraft-related newsletter. Understanding these predictors can help inform targeted recruitment strategies for the research team managing the Minecraft server project.

## Question

**How does player experience, hours logged on the game, and age predict the liklihood of being subscribed to the newsletter**

This question is motivated by the need to identify which types of players are most engaged with the server and community, as indicated by their choice to opt into further communication via the newsletter. The response variable of interest is `newsletter subscription status` (yes or no), and the explanatory variables are:
- `hours logged` (total time spent playing)
- `age` (as recorded during signup)
I will be blocking classification by player experience, one being expert (containing "Veteran" and "Pro" players), and the other being new players ("Beginner", "Amateur", and "Regular" players)

## Project Plan

To answer this question, I will follow the data science workflow outlined below:

1. **Data Loading and Preparation**
   - Load `players.csv` and `sessions.csv`
   - Merge datasets on a common key (e.g., player ID)
   - Clean data: handle missing values, check data types, remove duplicates

2. **Exploratory Data Analysis (EDA)**
   - Generate summary statistics for key variables
   - Visualize distributions and relationships

3. **Modeling**
   - Use knn classification to see which group has a higher chance of being predicted as a news letter subscriber
   - Evaluate model accuracy and interpret coefficients

4. **Results and Interpretation**
   - Present key findings with plots and tables
   - Discuss assumptions, limitations, and implications

5. **Conclusion**
   - Summarize main takeaways
   - Suggest practical applications and future directions for research

This project will be fully implemented in R and conducted within a Jupyter Notebook, using code cells for all computation and markdown cells for clear explanation and interpretation.
