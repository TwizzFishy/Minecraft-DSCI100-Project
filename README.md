# Predicting Minecraft Newsletter Subscription

## Introduction

The goal of this project is to analyze the relationship between player characteristics and their likelihood of subscribing to a Minecraft-related newsletter. Understanding these predictors can help inform targeted recruitment strategies for the research team managing the Minecraft server project.

## Question

**Can play experience, hours logged, and gender predict the likelihood of subscribing to a Minecraft newsletter?**

This question is motivated by the need to identify which types of players are most engaged with the server and community, as indicated by their choice to opt into further communication via the newsletter. The response variable of interest is `newsletter subscription status` (yes or no), and the explanatory variables are:

- `play experience` (e.g., beginner, experienced)
- `hours logged` (total time spent playing)
- `gender` (as recorded during signup)

## Project Plan

To answer this question, I will follow the data science workflow outlined below:

1. **Data Loading and Preparation**
   - Load `players.csv` and `sessions.csv`
   - Merge datasets on a common key (e.g., player ID)
   - Clean data: handle missing values, check data types, remove duplicates
   - Create new features (e.g., total hours played)

2. **Exploratory Data Analysis (EDA)**
   - Generate summary statistics for key variables
   - Visualize distributions and relationships (e.g., bar plots, boxplots)

3. **Modeling**
   - Use logistic regression to model the probability of newsletter subscription
   - Evaluate model accuracy and interpret coefficients
   - Consider including alternative models if time permits

4. **Results and Interpretation**
   - Present key findings with plots and tables
   - Discuss assumptions, limitations, and implications

5. **Conclusion**
   - Summarize main takeaways
   - Suggest practical applications and future directions for research

This project will be fully implemented in R and conducted within a Jupyter Notebook, using code cells for all computation and markdown cells for clear explanation and interpretation.
