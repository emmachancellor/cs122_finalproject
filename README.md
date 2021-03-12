### cs122_finalproject

# **Moving to Chicago and Don't Know Where to Live?**

## **Project Description**
Well, look no further! Our program allows users to rank on a 1-5 scale (1 not important -  5 very important) their preferences on number of nearby grocery stores, parks, health centers, CTA train stops, CTA bus stops, and the level of crime they are looking for in a neighborhood. After answering their neighborhood preferences, they will receive a list of the top five zip codes that match their community preferences. The user can learn more about a particular zip code: median income, number of schools, and life expectancy. From here the user will be able to find properties for sale in their matched community. The user will input the number of bedrooms they are looking for in a property as well as the relative price range the would like on a scale of 1-5, 1 being least expensive and 5 being most expensive. After inputting this information, the user will recieve the top two property matches in each of the five matched zip codes. The user will then be able to better visualize their potential community and where community resources are located by selecting one of their matched zip codes to view a map of the zip code with various plot options. Finally, 

## **Visualization** 
Users of the final product will be prompted to input a variety of information such as age, sex, income and locational data. The Matplot library and the Seaborn library will be used to display a plot with income as the independent variable and life-expectancy as the dependent variable. The fitted-model will take in additional parameters that the users has inputted and will be depicted on the plot. On the bottom of the plot a slider will allow the user to change their income level and see in real time how income changes could affect their estimated life-expectancy. The feasibility of adding sliders for non-continuous variables such as age and race will be explored with the possibility of changing the displayed independent variable on the graph. In addition, a map of Chicago centered on the user’s location will display the nearest health centers within a specified radius. This will likely be achieved with the Matplotlib, Cartopy, and Geopandas libraries.   

## **Approximate Methodology**
We can use linear regression to get our best estimates for this problem. Some of the variables we might consider are listed above in the “Project Description” section. We can start by comparing simple linear regression models then see how considering more variables impacts the accuracy and potential overfitting. Perhaps truer to real life, we would consider interaction effects between certain variables in an attempt to improve the overall model. 

## **Project Goal**
Through this project, we hope to provide an engaging platform for individuals to observe how many societal factors may affect one’s life expectancy. We hope to further elucidate factors that may provide greater contextualization for what recent research and reporting has termed the “life expectancy” gap across the city of Chicago.
