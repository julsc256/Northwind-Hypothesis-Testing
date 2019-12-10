# Insights into Northwind
### Focus on Revenue
___

## An Introduction
___

For this project, I had to work with the Northwind database--a free, open-source dataset created by Microsoft containing data from a fictional company. The goal of the project was to test my ability to gather information from a real-world database and use my knowledge of statistical analysis and hypothesis testing to generate analytical insights that can be of value to the company. 

### Northwind database schema:

![](Northwind_ERD_updated.png)

## The Goal
___

The project was to query the database to get the data needed to perform a statistical analysis. In this statistical analysis, I needed to perform hypothesis tests to answer the following questions:

1. Does discount amount have a statistically significant effect on the quantity of a product in an order? If so, at what level(s) of discount?
   
2. Do suppliers from some regions generate more revenue than others? Is the revenue different for the different types of categories being supplied? Is the average revenue from a supplier in a certain region different depending on the category that it is supplying?
    
3. Do employees from USA or the UK generate more revenue? Do some employees generate more revenue than others? If so, which employees? Does their title affect their sales in any way?
    
4. Do some categories of product sell more during certain seasons? If so, which categories?
  

## The Steps
___
#### For each question you'll find in the 'Technical Notebook':
- A definition of the hypothesis. 
- An exploration of the given SQL data focusing on the question.
- A test of the hypothesis using Mann Whithney U test or ANOVA.
- An interpertation of the findings with suggestions.