# Game Recommendation
As part of the final project for the DS 1 we have done project on Recommendation System for game recommendation. Recommendation is used as a marketing strategy by many e-commerce companies. So our team: Abjasree S, Poojan Smart, Niranjan Solanki and Vaishnav Panuganti started working on game recommendation based on the methods which were taught in this course.

The first part of the project is to scrape the game data as well as the user data from the websites provided below. There is an inbuilt API for steam but to use the API we have to purchase the products worth 5$ to use the API hence we tried scrapping through brute-force way.

Data Resources:
We will use game data obtained from the STEAM website given below
The data: https://store.steampowered.com/
We will use the user data obtained from the website given below
The user data: https://steamcommunity.com/games/steam/members

Problem Statement (Exploration):
The problem was divided into 3 parts which has been taught in the course

1. Scrape the data necessary for building the model and clean it
2. Build recommendation system for recommending games
3. Visualizing whether there are any clusters so that we can say that recommendation system can indeed be used.

## What we did in this project 
- In this project we have scrapped the data about the games and the hours played by each user for each game using BeautifulSoup
- We have used the hours played by the user as the implicit feedback to give top 5 recommendation
- We have used different base models as well as some complex model to give the recommendation
- We also used the dimensionality reduction techniques and visualized the data and found cluster and this information is used in building a cluster based content boosted model which gave the highest hit rate of 0.66 i.e., out of 5 games recommended 3 were played by the user 
