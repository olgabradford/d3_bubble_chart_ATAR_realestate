To see visualization in the browser check [this link](http://bl.ocks.org/olgabradford/43ae6795b8081f3bacd18dd54c585917)  

##Design
This chart shows a story about how median house price in Perth is related to how well students study in government high schools (ATAR score) and percentage of students who continue education in Universities (ATAR participation).
I combined two chart types: bubble chart and bar chart. Bubble chart is good to display 3 variables at once.   
X axis is for Perth median house prices. I found data only for 2 years, 2015 and 2017.
There was a slight reduction in price on an average price of a house in Perth, with an exception of a few suburbs
Y is for ATAR score, and its maximum is 100.  
I chose unbounded value for X and bounded value for Y since it's easier to view on wide screens like PC screen.  
I chose Bubble plot since it is good for displaying linear relationship between X and Y.   
Legend includes regions on Perth, so users can filter the data by clicking on any region.  
Grouping by region is good for visualization because we may cluster suburbs by region.  
Bar plot on the right hand side runs automatically after page is loaded.  
Years run from 2015 and 2017 change in house prices in 2 years.  
Size of bar shows total of median house prices in Perth in particular year. 
Categorical variable "region" displayed in contrast colours to make the difference between groups clear.  

## The story  

My story comes from https://www.myschool.edu.au/ and school rankings available online and statistics on median house prices from REIWA https://reiwa.com.au/the-wa-market/perth-suburbs-price-data/
In this visualization I wanted to show how success of kids in government schools related to the median house prices in catchment area of a particular school.
ATAR score is a measure of academic success of a particular student, schools are very proud if average ATAR score is high in comparison to other schools. Other, probably even more important number is a percentage of students who do ATAR subjects in a particular school, which mostly describes academic enviroment in school. Generally in "expensive suburbs" more students are doing ATAR subjects which is a pathway to Univesity degree. This number varies from 90% to less than 20%.



##Resources
The data source for this visualization is [here](https://www.myschool.edu.au/
https://reiwa.com.au/the-wa-market/).  
http://dimplejs.org/  
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.axis  
