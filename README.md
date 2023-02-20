# Data Visualization Project

## Data

The data I propose to visualize for my project is information about food orders and deliveries from NYC restaurants, specifically those that go through the delivery app Foodhub. Here is the link to the dataset source: https://www.kaggle.com/datasets/ahsan81/food-ordering-and-delivery-app-dataset

## Prototypes

I’ve created a proof of concept visualization of this data. It's a donut chart that shows the most popular cuisine types by the number of orders. Each cuisine type is specified by its own unique color and identified in the legend. 

[![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/fca93ab2d206aa49461d26c0b070ffc8fb12b54d/Screenshot%202023-02-19%20184712.png)](https://vizhub.com/curran/eab039ad1765433cb51aad167d9deae4)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * Which are the most popular cuisine types ordered?
 
 * Is there a correlation between delivery/preparation time and customer ratings?
 
 * Which restaurants receive the most orders? Which restaurants earn the most money from orders?
 
 * Are food orders/deliveries more common on weekends or weekdays?

## Sketches

My first sketch was my initial plan for the piechart, displaying the most popular cuisine types by number of orders. This would help answer the first question, identifying which cuisine types are more popular than others. 

[![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/fca93ab2d206aa49461d26c0b070ffc8fb12b54d/Screenshot%202023-02-19%20184712.png)](https://vizhub.com/curran/eab039ad1765433cb51aad167d9deae4)



My second sketch, once iterated, is a scatterplot showing the relationship between both delivery and preparation time and customer rating. The hope is that this visualization will help display a correlation between the two variables, and possibly give delivery workers insight onto how delivery time can impact ratings.

[![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/fca93ab2d206aa49461d26c0b070ffc8fb12b54d/Screenshot%202023-02-19%20184712.png)](https://vizhub.com/curran/eab039ad1765433cb51aad167d9deae4)

This next sketch is a simple barchart, which will display wether food orders are common on weekdays vs. weekends. 

[![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/fca93ab2d206aa49461d26c0b070ffc8fb12b54d/Screenshot%202023-02-19%20184712.png)](https://vizhub.com/curran/eab039ad1765433cb51aad167d9deae4)

Lastly, this sketch is another barchart, that will display the top 5 most "popular" restaurants, both in terms of number of orders placed and total spent. This can help restaurants identify their top competition.

[![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/fca93ab2d206aa49461d26c0b070ffc8fb12b54d/Screenshot%202023-02-19%20184712.png)](https://vizhub.com/curran/eab039ad1765433cb51aad167d9deae4)



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
