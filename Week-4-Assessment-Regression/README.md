# Week 4 Assessment - Regression Analysis

## Problem Statement
This assessment focuses on applying regression/classification analysis using Orange Data Mining to understand employee attrition and identify patterns that help explain whether an employee is likely to leave or stay.

## Tool Used
- Orange Data Mining

## Model Used
- Logistic Regression

## Target Variable
- Attrition / Employee status: Left or Stayed

## Model Evaluation Summary
The Logistic Regression model was evaluated using recall values for both classes.

- Recall for Left: 0.738
- Recall for Stayed: 0.760

## Interpretation
The model is able to identify employees who left with a recall of 0.738. This means the model correctly captures a good portion of actual employees who left.

The recall for employees who stayed is 0.760, which means the model is also reasonably good at identifying employees who stayed.

Since both recall values are close to each other, the model performance appears fairly balanced. It is not only focusing on one group, but is learning patterns for both employees who left and employees who stayed.

## Business Insight
From a business point of view, this type of model can help HR teams identify employees who may be at risk of leaving. This allows the organization to take early action through engagement, retention discussions, career planning, or manager support.

## Key Learning
Through this assessment, I learned:
- How to define a target variable
- How to build a Logistic Regression model in Orange
- How to evaluate model performance using recall
- How to interpret model results in business language
- Why model evaluation is important before making business decisions
