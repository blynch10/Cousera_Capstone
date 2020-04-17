# Cousera_Capstone
Capstone Project for Cousera IBM Data Science Course
This file is for the capstone project that was completed for the IBM Data Science Course

# Introduction

There is no worse feeling than showing up to a early morning meeting with your stomach grumbling.  Tensions are already high and being hangry isn't going to help anyone.  In this problem, we are going to suppose that someone arrives via train at 30th St. Station in Philadelphia, PA.  His train gets there slightly early.  His meeting is at 10 am, but the train arrives around 8 am.  He hasn't had anything to eat yet, but would really like to know where to go to find a good bagel shop.  Reviews are incredibly important to him and he will only go somewhere if it is highly rated. He'd like to know what are some good options for bagel places nearby.
This project works to solve that question by using the Foursquare API in addition to the a pandas, folium, and numpy library.  The goal of this project is to find the bagel places that are close to 30th St. Station, evaluate how they are rated, and plot them on a map to show our hungry user what his options are.  In this project, any bagel shop that does not have any ratings recorded on the Foursquare API will not be considered.  The final map will have call-out bubbles that will show the name of the bagel shop, its rating on Foursquare, and the distance (in miles) from 30th St. Station.

# Data

This project will call on Foursquare to provide locations of bagel shops in the specified vicinity.  From the large set of data that will be initially gathered, the name, address, and coordinates of each shop will be stored.  Foursquare will again be utilized to find the ratings of each bagel shop.  This data will compiled with the earlier data to create a complete data set.  In addition to these values,  a distance between the bagel shop and 30th St. Station will be calculated using a mathematical model.  The folium library will be used to plot the points on a map and show the options.  The name of each shop, the rating from Foursquare, and the distance from 30th St. Station will be shown in the pop-up marker for each bagel shop.
