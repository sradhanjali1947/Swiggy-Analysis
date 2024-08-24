# Swiggy Data Analysis Project 🎁

<p align="center">

  ![Made With Python](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/badges/made-with-python.svg) <br>
  ![Juputer Notebook](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/badges/jupyter-notebook.svg)
  ![Numpy](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/badges/numpy.svg)
  ![plotly](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/badges/plotly.svg)
  ![Pandas](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/badges/pandas.svg)
  ![Seaborn](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/badges/seaborn.svg)
  ![Miniconda](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/badges/mini-conda.svg)
  
</p>  

<p align="center">
  <img src="https://github.com/striver005/Swiggy-Data-Analysis/blob/master/swiggy_images/swiggy_image.png">
</p>

# Problem Statements
Food industries are having important reflection of the economy from past few decades. In this project, we are analyzing the various aspects with different use cases which covers many aspects of Swiggy Food Delivery Service. It helps in not only understanding the meaningful relationships between attributes, but it also allows us to do our own research and come-up with our findings.

Analysis of the following is performed in this Project:

    1. Distribution of 'Rating'.
    2. Area-wise Analysis in terms of 'Rating' and 'Cost_for_Two (₹)' on BTM, HSR, & Koramangala Area.
    3. Analyse "Approx Cost of 2 People" vs "Rating". Find out the relationship between them.
    4. Analyze Affordable/Budgeted and Highest Rated Restaurants of Bangalore.
    5. Top 15 Cheapest & Highest Rated Restaurants with Approx. Cost for 2 People.
    6. Top 15 Expensive & Highest Rated Restaurants with Approx. Cost for 2 People.
    7. Area-wise Cuisines Analysis & Distribution of Cuisines in BTM, HSR, & Koramangala (Bangalore) Restaurants.
    8. Most preferred Cuisines by the Customers.

#  Data Analysis
In the datasets Following features (columns) are given:

1. Shop_Name : Name of the Shop/Restaurants.
2. Cuisine : Name of the different Cuisines provided by Restaurants.
3. Location : Restaurant Area/Location.
4. Rating : Rating given by the Customers out of 5.
5. Cost_for_Two (₹) : Approx. Cost of Two people w.r.t. Restaurants.

Out of the 5 features  2 are Continuous and 3  are Categorical features.


# Process-Flow:
![Process Flow](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/swiggy_images/architecture_of_swiggy.png)


# Technologies:
##  Tools Used
* Jupyter Notebook is used as IDE. 
* Pandas is used for Data Manipulation & Pre-processing.
* For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
* GitHub is used as version control system.
![Tools-Used](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/swiggy_images/tools_used.png)


# Some Visuals Of the Project:
![Visual 1](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/img/cost%20vs%20rating.png)
![Visual 2](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/img/highest_rated_and_affordable_restaurants.png)
![Visual 3](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/img/Overall%20Analysis%20of%20Cuisines%20-%20pie.png)
![Visual 4](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/img/top%2015%20cheapest%20but%20highest%20rated%20restaurants.png)
![Visual 5](https://github.com/striver005/Swiggy-Data-Analysis/blob/master/img/top%2015%20expensive%20but%20highest%20rated%20restaurants.png)

# Conclusions

    In this analysis project, we have been analyzed several different use cases for the given dataset t o make better business decisions and help analyze customer trends and satisfaction, which can lead to new and better products and services. It has been found that – 
    •	In BTM Area: Most of the Restaurants has 4.0 to 4.2 Rating and Approx. Cost for Two People lies between 200 to 350. (Max. Cost goes up to 600)
    •	HSR: Most has 4 or above Rating and Approx. Cost for Two People lies between 300 to 400. (Max. Cost goes up to 800)
    •	Koramangala: Most has 4.0 to 4.3 Rating and Approx. Cost for Two People lies between 200 to 350. (Max. Cost goes up to 600)
    With this we can conclude the Most Costly Area is HSR. 

    - We have also analyzed that, we have Total "82" which are the "Budget Restaurants" as well as they are "Affordable". 
    - On top of that, we have found-out, Most of the Affordable/Budgeted Restaurants are having Excellent Rating as well. Like, For Approx. Cost of "200", "150", "250", and "450", the Ratings were "4.8", "4.6", and "4.5" respectively. 
    - This might be because Most of the people prefer Affordable/Budget-Restaurants which also provides good quality of Cuisines. 
    - And On the other hand, there are few Expensive Restaurants who doesn't have that much Rating and they are Expensive too. 
    - Those Restaurants Costs around "600" to "800" for Two People are having the Ratings in between '4.0' to '4.1' which is too less as compared to Affordable/Budgeted Restaurants.

    In addition to that, we have also performed Analysis on the Cuisines w.r.t. different Areas/Location and We have found-out:
    •	In BTM Area, Most of the Restaurants sell "Chinese" which is around '17.1%' followed by "North Indian" & "South Indian" Cuisines which are around '15.2%' & '9.52%'. So, we can also infer that Most of the people are fond of these Cuisines.
    •	In HSR Area, "North Indian" Cuisines are dominated by around '14.3%' followed by "Chinese" & "South Indian" Cuisines '9.52%' & '9.52%' Restaurants respectively.
    •	In Koramangala Area, "Chinese" Cuisines are dominated by around '10.3%' followed by "North Indian" & "South Indian" Cuisines '9.66%' & '7.59%' Restaurants respectively.
    •	Furthermore, we have also been analyzed Cheapest/Expensive & Highest Rated Restaurants with Approx. Cost for 2 People and many more.
