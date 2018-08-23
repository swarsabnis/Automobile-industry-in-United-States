# Automobile industry in United States
<p>The goal of this project is to understand key performance indicators for automobile industry in US. The dataset consisted of 48 car brands and in total 915 different  car models in United States between 1990 and 2017. This dataset includes parameters -- miles per gallon, engine type, fuel type used, horsepower, number of cylinders and vehicle style.
<p>This dataset was used to understand key performance indicators (KPI) for cars used in US. Initial analysis consisted of analyzing different factors that impact Miles per Gallon( MPG) of any given car model. Next step was to find popularity of different car brands in past 5 years and  diving deep into what factors led to change in the popularity of brands like BMW. 
<p>Electric vehicles (EV) are currently ramping their presence in automobile industry. Visualized EV sales over the years and mapped different public charging stations across states to identify potential growth for EV in US automobile market.</p>

### Dependencies:

#### Python Packages used:
<ol>
	<li>pandas</li>
	<li>numpy </li>
	<li>matplotlib</li>
	<li>seaborn </li>	
	<li>plotly</li>
</ol>

### Datasets used:
<p> Note: Due to huge data size, we havent kept a dataset folder. Datasets can be found here:
<ul><li><a href="https://www.kaggle.com/jeanmidev/smart-meters-in-london">Dataset from Kaggle</a></li>
<li><a href="https://data.london.gov.uk/dataset/smartmeter-energy-use-data-in-london-households"> Tariff rates</a></li></ul></p>


<ol type="decimal">
<li>data.csv: Contains information about cars used in United States from 1990 to 2017.It includes information like Engine type, Miles per Gallon, Popularity, MSRP for each Model.</li>

<li>pev_sales.csv: Contains information about sales of electric cars in United States from 2011 to 2016 for different brands and models. </li>

<li>fuel_stations.csv: Contains information about charging stations across United States. Includes information about fuel type, longitude, latitude of charging staions.</li>
</ol>



## Table Of Contents:

####  
<a href="http://nbviewer.jupyter.org/github/swarsabnis/Automobile-industry-in-United-States/blob/master/Jupyer_Notebooks/Automobile_industry_US.ipynb">Exploratory data analysis and visualizations</a>

#### [Inline Visualization](#viz-anchor)

#### [Summary](#summary-anchor)
#### [Next Steps](#nextstep-anchor)



### <a id='viz-anchor'></a>Inline Visualizations


<p>Energy usage is very high during evening hours, less during day time and mean energy usage dips down to the lowest during late night hours. This pattern remains same irrespective of their tariff rates (high, normal, low). Also, it is seen that less energy is consumed when high rates are charged.</p>

 
   

<p>  Above bar chart shows sales trend for electric cars in United States from 2011 to 2016. As seen, there is a steady growth in overall sales for electric cars with few brands having major share in the sales growth. Tesla, BMW and Nissan are the key players in EV market and tend to grow almost every year. BMW improvement in EV sales has directly impacted its popularity as shown in earlier graph. Nissan has been a steady player, its EV models introduced right from 2011 with a very substantial market share. Tesla's 20 times sales growth from 2011 to 2016 is quite impressive. </p>



#![Weather](https://github.com/swarsabnis/Analysis_of_Smart_meter_London/blob/master/Images/weather.png)
	
<p>Above geo map shows public charging stations for electric cars present across US in 2017. It currently seems that electric cars have imprinted its presence mostly along the east and west coasts of US. But there is still a big chunk of scope in the central states, which seems to be a potential market for electric car industry. </p>



### <a id='summary-anchor'></a>Summary

<p> Automobile industry is ever evolving where new inventions keep industry striving for newer, more efficient and magnificient cars.
  
<p> Automobile KPI's explained:

<ul>
	<li>MPG impacted by engine type
	<li>MPG impacted by number of cylinders
  <li>Horsepower impacted by number of cylinders in car engine</li></ul>
</p>

###  <a id='nextstep-anchor'></a> Next Steps

some visualizations could be plotted for the following :
<ol>
	<li> Performance based on different style of car( Coupe/Sedan/Van)
	<li>Self driving cars and its performance
	<li> US automobile market compared to other nations</li></ol>




