# Rockbuster_Project
A data analytics project based on a sample database of a fictitious DVD rental company “Rockbuster Stealth” using SQL queries as a part of Data Analytics course at CareerFoundry.

## Objective
Rockbuster Stealth is a movie rental company that formally had stores around the world. Because of the stiff competition from streaming services, the management is planning to use the existing movie licenses to launch an online video rental service to stay competitive. The objective of this study is to develop insights to help with the launch strategy for the new online video service.

## Data 
Open source tutorial data from PostgreSQL available [here](https://www.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip).

## Tools
- SQL - to retrieve data from relational database management system (RDBMS) and analyze the data, available [here](https://github.com/Smologonova/Rockbuster_Project/blob/main/SQL%20Queries).
- Excel – to analyze, find insights and prepare charts, available [here](https://github.com/Smologonova/Rockbuster_Project/blob/main/queries_and_outputs.xlsx).
- Tableau - to turn insights into interactive data visualization, available [here](https://public.tableau.com/app/profile/iryna.smologonova/viz/Rockbuster_16542998273360/Revenuebycountry?publish=yes).

## Result 
[Rockbuster Stealth Presentation Slides](https://github.com/Smologonova/Rockbuster_Project/blob/main/Presentation%20slides_Rockbuster%20Stealth.pdf)
- Start the streaming service by piloting in top 3 countries – India, China and United States by total revenue and number of customers as they account for 25% of all revenue and customer base. 
- Add to inventory movies: ratings PG-13 & NC 17 generating the most revenue and genres Comedy, New & Sports producing more revenue per film. 
- Implement online acquiring customer loyalty program by launching a bonus system.

## Key takeaways
- A bubble chart is a solution to visualize three metrics – number of transactions, revenue and average revenue per number of transactions. It allowed to include the addition of a third dimension as a bubble size/color to emphasize the most popular genres.
- Common Table Expressions (CTE) is more readable than subqueries and can be reusable. However, subqueries and CTE  have pros & cons and the choice between them should be made on a case-by-case basis.
- SQL ranking functions allowed me to define top 20 movies with the highest revenue in a simple way and made my query more readable.  RANK()/DENSE_RANK() functions are great for sequencing and comparing data across various factors. 
