# Data Visualization Final Project

## Data

Initially, the data I chose to visualize for my project was information about food orders and deliveries from NYC restaurants, specifically those that go through the delivery app Foodhub. The link to the github gist I created for this data is: https://gist.github.com/jjlaber/054bd0ea2181f10aa2c7813264e50dee

With further consideration, however, I decided to visualize historical data about bank failures in the US. I decided that this data was more relevant to current events and may be more useful to visualize. The link to the github gist I created for this data is: https://gist.github.com/jjlaber/5e97519bf57c60fbe2ac9895119263b1

## Initial Plan

With my first dataset, I planned to create visualizations to help answer the following questions:

 * Which are the most popular cuisine types ordered?
 
 * Is there a correlation between delivery/preparation time and customer ratings?
 
 * Which restaurants receive the most orders? Which restaurants earn the most money from orders?
 
 * Are food orders/deliveries more common on weekends or weekdays?
 

## Initial Sketches
 
In order to plan these visualizations, I created some concept sketches.

My first sketch was my initial plan for the piechart, displaying the most popular cuisine types by number of orders. This would help answer the first question, identifying which cuisine types are more popular than others. 

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/1841f24238a98bf95499516966c145c421599a6b/Screenshot%202023-02-19%20190503.png)

My second sketch was a scatterplot showing the relationship between both delivery and preparation time and customer rating. The hope was that this visualization would help display a correlation between the two variables, and possibly give delivery workers insight onto how delivery time can impact ratings. However, the data did not comply, so this visualization was scrapped.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/1841f24238a98bf95499516966c145c421599a6b/Screenshot%202023-02-19%20190316.png)

The next sketch was a simple barchart, which would display wether food orders are common on weekdays vs. weekends. 

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/1841f24238a98bf95499516966c145c421599a6b/Screenshot%202023-02-19%20191148.png)

Lastly, this sketch was another barchart, that would display the top 5 most "popular" restaurants, both in terms of number of orders placed and total spent. This would help restaurants identify their top competitors.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/1841f24238a98bf95499516966c145c421599a6b/Screenshot%202023-02-19%20190241.png)


## Initial Visualizations

The first visualization I focused on creating was the pie chart. Upon doing further research, I decided to create a donut chart as this would be more easily interpretable by the audience. The donut chart I created shows the most popular cuisine types by the number of total orders. Each cuisine type is specified by its own unique color and identified in the legend.

[![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/fca93ab2d206aa49461d26c0b070ffc8fb12b54d/Screenshot%202023-02-19%20184712.png)](https://vizhub.com/jjlaber/df931fe5e8e94515aac0b3305185ce97)

The next visualizations I focused on creating were the barcharts I sketched above. The first barchart I created was the chart displaying the number of orders on Weekdays vs. Weekends. After learning how to include a dropdown menu, I altered the visualization so that users could view either the total number of orders or total amount spent by day of the week.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/barchart1.png)
(https://vizhub.com/jjlaber/b05792b06de540e28165129e77f03691)

The second barchart I created was the top 5 restaurants by total number of orders. I never ended up implementing a toggle feature for this chart, so it only displayed the restaurants by the number of orders as opposed to also the cost. I also was never able to fix my issue of the bar values not appearing to be accurate. 

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/barchart2.png)
(https://vizhub.com/jjlaber/cda48dc839ed4beda666eb7275fed1b3)

The next visualization I attempted to create was the scatterplot displaying the relationship between delivery time and customer rating. However, I quickly discovered that the data did not show any semblance of a correlation. I also implemented an interactive legend to see if this would help show a difference in the rating based on the day of the week, but this appeared to be hard to interpret. 

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/scatterplot.png)
(https://vizhub.com/jjlaber/917f54c257d0404fb01733fe5a6a3e47)

For the next visualization I created, I did not use the previous Foodhub dataset. Because I wanted experience with creating a cloropleth map, I chose a dataset that included location information. I chose a dataset that had information on the air quality in different areas around the world. The link to the github gist I created for this data is: https://gist.github.com/jjlaber/9ae194a636c4c98351760e241d8a9dd3. I ended up plotting the air quality value for each country in 2021, with the darker colors indicating a higher value.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/map.png)
(https://vizhub.com/jjlaber/559adac5c58343d2878e4580789512f2?edit=files&file=viz.js)

The last visualization I created using the Foodhub dataset was a treemap. For this visualization, I aimed to show the top restaurants by the average rating they received in Foodhub orders. I found this to be an interesting and unique way to display hierarchal data, and it was interesting setting up the groundwork for this visualization.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/treemap1.png)
(https://vizhub.com/jjlaber/58bc16207f06490390ab00a83a60cdbe)

After creating my initial visualizations, I decided I wanted to work with data that was more relevant to current events. After discovering interesting visualizations about the US bank failures that were created after the Silicone Valley Bank Failure, I was inspired to create some of my own. 

## New Data and Questions
For US Bank Failure data, I found two main datasets that I was interested in using. I found a dataset with information on failures from 2001-2023 (https://gist.github.com/jjlaber/fabaa04f42e2a65efc1791b59e55d05a) and then another with information on failures from 1934-2020 (https://gist.github.com/jjlaber/5e97519bf57c60fbe2ac9895119263b1). 

In order to make the data usable, I had to perform a good amount of data cleaning on the first dataset. Initially, 'Bank Name, City, and State' wer organized in one column. In order to use the location data later, I split these entries based on the last two commas. I also had to go in by hand to fix a few mistakes, as the data was not consistently entered.

After performing this datacleaning, I properly loaded both of the datasets into github, making sure that numeric attributes were convered from string to numeric values. 

The questions I aimed to answer with these new datasets were:

* What has been the trend of the number of bank failures from 1934-2023?

* Which bank failures have had the greatest estimated loss?

* How do the losses involved in the bank failures trend over time?

* Is there a specific transaction type that is connected to a majority of bank failures?


## New Visualizations

Once I prepared these new datasets, I chose to recreate my previous visualizations, this time using the bank failure data. 

I first focused on recreating my donut chart. This time, I aimed to display the distribution of different transaction types across all US bank failures. I also decided to use a simpler color scheme so that the data could be easily interpreted.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/donutchart.png)
(https://vizhub.com/jjlaber/085fca0b8d32438799f9bbf1df731ccd)

I then wanted to recreate the treemap, this time displaying the ranking of banks by total estimated loss, asset value, and desposit value (all in USD). In order to display bank ranking by these different values, I implemented a dropdown menu so that the user could toggle between them. I chose the same color scheme as for my previous chart, and I began to think about how the visualizations would look like in the final ensemble. One issue I found, however, was that many bank names were too long, so they were cut off or went off of the page.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/treemap2.png)
(https://vizhub.com/jjlaber/e3d38218868f42b2bc0d72c80f28f57d)
 
The third visualization I decided to create was a line chart displaying the number of bank failures over time, as well as the total estimated loss over time. It was interesing to see the trend of bank failures over time. However, I do wish I was able to merge this with the more recent data (2020-2023), as it would be interesting to see that most recent spike.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/linegraph.png)
(https://vizhub.com/jjlaber/dc15f069ca174813b5877dec3d99a151)

As we geared towards the end of the course, I began to combine my visualizations into the final "ensemble", or collection of all of the visualizations on one page. I first created a page where I included the donut chart as well as the treemap.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/first_ensemble.png)
(https://vizhub.com/jjlaber/b877eca7cffe4efea4d609b4a97f794d)

## Final Ensemble

When it came to creating my final ensemble, I chose to make a few changes. First off, in order to make the visualizations more appealing, I chose a different color scheme. I also chose to use a darker blue background to highlight the lighter colors in the color scheme. I also centered the visualizations, as I thought this appeared to be more aesthetic. Overall, I am very proud of what I was able to create.

![image](https://github.com/jjlaber/dataviz-project-template-proposal/blob/0378387e01927bcedb8619be6a74f21f5c8e4076/final_ensemble.png)
(https://vizhub.com/jjlaber/7c4616c3dbdf4017ad4e5376a524ea2b)


## Future Work

There were definitely many tasks and visualizations that I did not get to through the duration of this project, mainly due to the fact that I decided to switch my data halfway through. However, I was proud of what I was able to accomplish with little prior knowledge of HTML and Javascript before starting the course. 

In the future, I believe my project could be improved by the following:

1. Merging 1934-2020 and 2020-2023 data in order to create a continuous timeline that would include the most recent bank failures.

2. Adding animations when visualizations change.

3. Creating a map to display the number of bank failues by state.

4. Create time filters that would alter all visualizations simulataneously.
