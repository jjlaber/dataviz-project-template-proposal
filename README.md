# Data Visualization Final Project

## Data

Initially, the data I chose to visualize for my project was information about food orders and deliveries from NYC restaurants, specifically those that go through the delivery app Foodhub. Here is the link to the dataset source: https://www.kaggle.com/datasets/ahsan81/food-ordering-and-delivery-app-dataset. The link to the github gist I created for this data is: 

With further consideration, however, I decided to visualize historical data about bank failures in the US. I decided that this data was more relevant to current events and may be more useful to visualize. 

## Initial Plan

With my first dataset, I planned to create visualizations to help answer the following questions:

 * Which are the most popular cuisine types ordered?
 
 * Is there a correlation between delivery/preparation time and customer ratings?
 
 * Which restaurants receive the most orders? Which restaurants earn the most money from orders?
 
 * Are food orders/deliveries more common on weekends or weekdays?
 
In order to plan these visualizations, I created some concept sketches.

My first sketch was my initial plan for the piechart, displaying the most popular cuisine types by number of orders. This would help answer the first question, identifying which cuisine types are more popular than others. 

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/1841f24238a98bf95499516966c145c421599a6b/Screenshot%202023-02-19%20190503.png)

My second sketch, once iterated, is a scatterplot showing the relationship between both delivery and preparation time and customer rating. The hope is that this visualization will help display a correlation between the two variables, and possibly give delivery workers insight onto how delivery time can impact ratings.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/1841f24238a98bf95499516966c145c421599a6b/Screenshot%202023-02-19%20190316.png)

This next sketch is a simple barchart, which will display wether food orders are common on weekdays vs. weekends. 

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/1841f24238a98bf95499516966c145c421599a6b/Screenshot%202023-02-19%20191148.png)

Lastly, this sketch is another barchart, that will display the top 5 most "popular" restaurants, both in terms of number of orders placed and total spent. This can help restaurants identify their top competitors.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/1841f24238a98bf95499516966c145c421599a6b/Screenshot%202023-02-19%20190241.png)



I’ve created a proof of concept visualization of this data. It's a donut chart that shows the most popular cuisine types by the number of orders. Each cuisine type is specified by its own unique color and identified in the legend. 

[![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/fca93ab2d206aa49461d26c0b070ffc8fb12b54d/Screenshot%202023-02-19%20184712.png)](https://vizhub.com/curran/eab039ad1765433cb51aad167d9deae4)


## Sketches



## Open Questions

I am concerned about the difficulty of creating a toggle button that will filter the data. I am also worried that the scatterplot may not show a clear correlation, and in that case I may have to consider another visualization in its place.

## Milestones
Week 7 - Find way to effectively display counts + labels on pie chart

Week 8 - Create barcharts without filter toggles

Week 9 - Create scatterplot/create new idea for that visualization

Week 10 - Implement toggle feature on barchart

Week 11 - Implement toggle feature on scatterplot/new visualization

Week 12 - Work on adding additional visualization components if necessary

Week 13 - Work on visualization aesthetics (color + text themes) 

Week 14 - Finalize visualizations

## Future Work

There were definitely many tasks and visualizations that I did not get to through the duration of this project, mainly due to the fact that I decided to switch my data halfway through. In the future, I believe my project could be improved by the following:

1. Merging the 1934-2020 and 2001-2023 data in order to create a continuous timeline that would include the most recent bank failures.

2. Adding more interactivity and animations when visualizations change.

3. Creating a map to display the number of bank failues by state.
