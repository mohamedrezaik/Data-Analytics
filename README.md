# Data-Analytics
This repository has some projects on data analytics.
## price prediction and statistical analysis:
  - It answers some question:
  - Question 1: Load in the provided dataset 20to22NYC.csv and summarize the basic statistics. Specifically your code should answer:
      - What are the feature types and their basic statistics (using describe(include='all'))
      - How many features have missing values?
      - What are the patterns of missing values and potential missing data reason for the top-3 most missed features.
  - Question 2: Check the normality of the target variable, i.e., 'SALE PRICE', using both graphical and statistical test methods.
  - Question 3: Design hypothesis test to answer the following two questions:
      - "Has the NYC real estate market changed following the declaration of the COVID-19 pandemic in March of 2020?"
      - "Do properties in Manhattan sell at higher prices than properties elsewhere?"
      - For each question, you need to give the null hypothesis $H_0$ and alternative hypothesis $H_1$
  - Question 4: Perform a multiple linear regression analysis on the given data, considering impact of missing values. Note, you need to properly transfer categorical features to numerical features first. Report the features that are significant relevant to sale price based on the results of your regression model. 

## topic_modeling:
  - to view the complete visualized version [click_here](https://nbviewer.org/github/mohamedrezaik/Data-Analytics/blob/main/topic_modeling.ipynb)
  - Question 1: Load in the provided dataset and summarize the basic statistics. Specifically your code should answer:
    - What are the feature types and their basic statistics?
    - How many features have missing values?
  - Question 2: Preprocess the abstracts of the papers in the provided data corpus. Apply bertopic on the abstracts and explain the topics you received and discuss the quality of the topics and determine what is the best topic number for abstracts you found out.
  - Question 3: Compare the topics learned by BERTopic with the original categories of the papers. For instance, you can pick one popular category, such as cs.CV, and check how those papers belong to this category are cateogrized by your topic model learned in previous step.
  - Question 4: Redo the topic modeling using the same method, but only on the papers tagged by the category you chcked in Q3. For instance, in Q3, you pick cs.CV, then in Q4, you first filter data by category = cs.CV and then apply the topic modeling on the selected documents. Compare your topics found and your results from Q3.
