# Hybrid Recommendation System

<p align="center">
	<img src="https://www.researchgate.net/profile/Xiangjie-Kong-2/publication/330077673/figure/fig5/AS:710433577107459@1546391972632/A-hybrid-paper-recommendation-system.png" />

</p>

## Table of contents
* [General info](#general-info)
* [Dataset info](#dataset-info)
* [Project info](#project-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Developments](#developments)

## General info
Recommendation systems have been around us for quite some time now. Youtube, Facebook, Amazon, and many others provide some sort of recommendations to their users.   

Here, we explore the relationship between the pair of items (the user who bought Y, also bought Z). We find the missing rating with the help of the ratings given to the other items by the user.   

It was first invented and used by Amazon in 1998. Rather than matching the user to similar customers, item-to-item collaborative filtering matches each of the user’s purchased and rated items to similar items, then combines those similar items into a recommendation list.



## Dataset info
The dataset was provided by MovieLens, a movie recommendation service. It contains the rating scores for these movies along with the movies. It contains 2,000,0263 ratings across 27,278 movies. This data was created by 138,493 users between 09 January 1995 and 31 March 2015. This data set was created on October 17, 2016. Users are randomly selected. It is known that all selected users voted for at least 20 movies.
## Project info
Make an estimate for the user whose ID is given, using the item-based and user-based recommender methods.
Here,we tried to create our own movie database with ratings by using "movies.csv" and "ratings.csv"(link down below)  
We calculated a suggestion with calculating the correlation between the entered movie and other movies. Hence we suggest a movie for user by using correlations among them.

## Technologies
Project is created with:
* PyCharm: 2021.3 
* Pandas: 1.3.4 (especially "corrwith")


	
## Setup
To run this project, just run the functions at the bottom of code and call "item_based_recommender". That's it!

## Developments 
It can be achieved more precise results merging both item-based and user-based recommendation by calculating "Weighted Average Recommendation Score". It will be developed on next project that I will do. It can become more likely a recommendation system like Netflix uses. For now, it is just simple version of item-based recommendation system



