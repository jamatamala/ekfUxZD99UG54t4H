## Project ekfUxZD99UG54t4H

###### Background:

ACME is one of the fastest growing startups in the logistics and delivery domain. ACME works with several partners and makes on-demand delivery to its customers. During the COVID-19 pandemic, ACME is facing several different challenges and everyday ACME is trying to address these challenges.

ACME thrives for making its customers happy. As a growing startup, with a global expansion strategy, ACME knows that it needs to make its customers happy and the only way to do that is to measure how happy each customer is. If ACME can predict what makes its customers happy or unhappy, ACME can then take necessary actions.

Getting feedback from customers is not easy either, but ACME does its best to get constant feedback from its customers. This is a crucial function to improve ACME's operations across all levels.

ACME recently did a survey to a select customer cohort. This project relies on a subset of this data. 

###### Data Description:

Y = target attribute (Y) with values indicating 0 (unhappy) and 1 (happy) customers
X1 = my order was delivered on time
X2 = contents of my order was as I expected
X3 = I ordered everything I wanted to order
X4 = I paid a good price for my order
X5 = I am satisfied with my courier
X6 = the app makes ordering easy for me

Attributes X1 to X6 indicate the responses for each question and have values from 1 to 5 where the smaller number indicates less and the higher number indicates more towards the answer.

###### Goal(s):

Predict if a customer is happy or not based on the answers they give to questions asked.

###### Problem description:

Before defining a strategy to achieve the goal of the project, it is worth describing the nature of the problem.

Predicting customer happines: The first thing to note is that the dependent variable is binary. Therefore we are facing a classification problem. In other words, we will be predicting whether, given the explanatory variables, a consumer is happy or not. 

In this first stage of the analysis I will use all the variables included in the database. 

One thing to note is that the explanatory variables range from 1 to 5. Therefore, to avoid bias in the results, I will standardize the variables. This also serves an additional purpose because one can assume that a consumer is happy when he/she receives an above expected (or average) quality of service and unhappy when he/she receives less.



In general, one can assume that a customer will be satisfied each time his expectations are exceeded or each time his expectations are fully met.

The first dimension is probably the most important during the growth stage of a company, in which acquiring new customers is of fundamental importance. The second dimension is probably more important to ensure the loyalty of existing customers.

In any case, given that there are multiple features of a product or service that affect customer satisfaction, and given that each of these features has a different cost to the company, it is vital to understand which features are most important to a customer. In this way the company can focus on these features.

That said, I will not only focus on predicting customer satisfaction, but also on identifying which features of ACME's service customers value most.

However, it is important to mention that customer satisfaction is a dynamic problem. Therefore, the analysis I perform in this project is only valid around the time the data was collected or for as long as the characteristics of the market and consumers do not change significantly.

For example, this means that a consumer's satisfaction will depend on his previous experiences, but also on his experience with competitors. The data is a cross-section sample, and therefore it is impossible to assess the influence of these elements on a consumer.

###### Methodology:

The analysis is divided into different stages, detailed below. Both the data and the code are available in the repository.
