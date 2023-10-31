# IBM Data Science Methodology and CRISP-DM


## IBM Data Science Methodology
Foundational methodology, a cyclical, iterative data science methodology developed by John Rollins, consists of 10 stages, starting with Business Understanding and ending with Feedback.

![Alt text](./img/data_science_methodology.jpg)


## 1. Business Understanding
The Business Understanding phase is a critical starting point for any data science project. It involves gaining a comprehensive understanding of the business problem and the objectives to be achieved. This step includes identifying key stakeholders and clearly defining the context in which the problem exists.

![Alt text](./img/01-Business_Understanding.png)

## 2. Analytic Approach
In this phase, you decide on the most effective analytic approach to solve the problem identified in the Business Understanding phase. It involves selecting the appropriate data analysis techniques and algorithms to obtain the desired answers.

![Alt text](./img/02-Analytical_Approach.png)

## 3. Data Requirements
The Data Requirements phase entails identifying the data needed to support the analysis process. This might involve specifying what data is required, where it comes from, and how it will be collected.

## 4. Data Collection
Data Collection is the process of gathering the data identified in the previous phase. This includes cleaning, transforming, and preparing the data to be ready for analysis. Ensuring data accuracy and completeness is crucial.

![Alt text](./img/03-Data-Requirement-and-Collection.png)

## 5. Data Understanding
In this phase, you explore the data to gain a deeper understanding of it. This involves visualizing the data, identifying patterns, significant relationships, and trends within the data. The Data Understanding stage encompasses all activities related to constructing the data set and answers the question as to whether the data you collected represents the problem to be solved. During this stage, scientists might use descriptive statistics, predictive statistics, or both.

## 6. Data Preparation
Data Preparation is the phase where data is readied for analysis. This can include feature engineering, handling missing data, and normalizing or standardizing the data. The goal is to obtain high-quality data ready for modeling.

![Alt text](./img/04-Data-Understanding-and-Preparation.png)

## 7. Modeling
The Modeling phase is where you construct analytical or predictive models. You select the appropriate algorithms and train the models. In this phase, it's also crucial to define how model performance will be evaluated. 

## 8. Evaluation
The Evaluation phase involves assessing model performance against business objectives. Evaluation metrics are used to determine the effectiveness of the models. If models do not meet the objectives, optimization or modifications may be necessary.

![Alt text](./img/05-Modeling-to-Evaluation.png)

## 9. Deployment
Deployment is the phase where the developed models or solutions are implemented in a production environment. This step involves putting the solutions in place so that they can be used by those who need them.

## 10. Feedback
The Feedback phase involves continuously monitoring model performance in production. Gathering feedback from users and identifying potential real-world issues or challenges is essential.

## 11. Iteration
Iteration is an important step where, if necessary, you go back to previous phases to make improvements or adapt to changing business needs. This iterative cycle helps keep models and solutions up-to-date and relevant.

![Alt text](./img/06-Deployment-to-Feedback.png)

##  CRISP-DM: Cross-Industry Standard Process for Data Mining

![Alt text](./img/CRISP-DM_Process_Diagram.png)

CRISP-DM is a framework that defines a structured process for addressing data mining and data analysis projects. This process is divided into six main phases:

1. **Business Understanding:** In this phase, you seek to understand the business problem you want to solve and how data analysis can contribute to achieving business objectives.

2. **Data Understanding:** Here, you gather and explore the available dataset, aiming to understand its structure, quality, and content.

3. **Data Preparation:** This phase involves data cleaning, transformation, and feature engineering to prepare the dataset for analysis.

4. **Modeling:** In this phase, you select and build appropriate data analysis models, such as machine learning models.

5. **Evaluation:** You assess the performance of the models and select the best model based on predefined metrics.

6. **Deployment:** Finally, you implement solutions based on the results of data analysis in the business context and monitor the results over time.
