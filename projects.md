---
title:  "A collection of some of my past projects"
mathjax: true
layout: post
---
## H3 Clustering Algorithm 
![Example image preview](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-10-07%20at%208.13.09%20PM.png?raw=true)

Skills: Weighted K-means clustering machine learning algorithm, Python (numpy, pandas, matplotlib), H3, KeplerGL, DBSCAN algorithm, unsupervised learning, SQL 

During my internship with Coco Robot Delivery, I found that Coco relied on field operators to maintain robots, and currently, the operating zones were manually created using the unique domain expertise. I wanted to find a way to automate this process and aid the creation of operating zones using certain constraints such as end-to-end travel time zones. 

1) Consideration of Constraints: Municipal boundaries, end-to-end travel time, historical failure rate
2) Using SQL to query geographical failure data as well as coordinates of all merchants in the areas
3) Using the H3 grid system to assign coordinates to hexagonal areas - to allow for analysis on the categorical level
4) Using Python and Google Maps API to build a custom clustering algorithm that included randomness and a scoring system to determine which runs of the algorithm produced clusters of greater quality
5) Used weighted k-means to incorporate form zones centered around hexagons with historically high failure rates in order to optimize current operating zones (Implemented DBSCAN as well to compare results and found that weighted k-means generated higher quality clusters according to a unique scoring metric)
6) Presented findings as a part of a final presentation  

## Optimization Algorithms and Root-Finding Methods 
[![Example image preview](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-03-21%20at%208.20.34%20PM.png?raw=true)](https://drive.google.com/file/d/1qMER7HqZ6ZvFlLa_Sss9KViTtBI51Ygg/view)

Skills: Mathematical Optimization, Root-finding Methods 

My analysis and replication of the Coordinate Descent Optimization Algorithm and multiple root-finding methods including fixed point iteration, Newton-Raphson, Bisection Search, and Secant Method. 

## Webscraping 
[![Example image preview](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-03-21%20at%209.36.08%20PM.png?raw=true)](https://drive.google.com/file/d/1XTXmYiJsU2RVyqQCclUxBKs6H15tDm5E/view)

Skills: Regex, Webscraping, tidyverse, Selenium webdriver

For a class project, I used packages rvest and polite as well as Selenium webdriver, I used webscraping methods to scrape content from the website: https://www.baseball-reference.com/. Specifically, I looked at Franchise History of the teams in the MLB and analyzed data across 22 seasons. I produced summary statistics using dplyr. Furthermore, I used regular expressions in order to pull data about team managers and extract the wins and losses data. 

## Monte Carlo Study and Simulation of the game Monopoly

[![Image](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-03-21%20at%206.20.24%20PM.png?raw=true)](https://drive.google.com/file/d/1XUkdepCPXkrUk4scbgHgcJQOZtSsAmd0/view)

Link to Full Project Repository: https://gitfront.io/r/user-7760407/zC7G8eLFQn87/Monopoly/

Skills: R, Object Oriented Programming, R6 Class 

In this project, I simulated the movement of pieces through a monopoly game using a random dice roll. I coded the entire Monoply Board as well as the Chance and Community Decks. In addition, I included the rules for moving through jail, being sent to jail, and leaving jail. It was especially challenging to conisder edge cases. Through running nearly 10,000 simulations of the game, I conducted a Monte Carlo Study to understand which positions get landed on the most in the Game of Monopoly. The entire project was built under the R6 Class system and entailed object oriented programinng to store and update important features of the players throughout the game. From the simulation study, I was able to provide a strategy as to which Monopoly properties are best suited to give you a high return on investment from rent collection. 

## Multivariate Linear Regression Analysis of WHO Data to build a predictive model of Life Expectancy
[![Example image preview](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-03-21%20at%207.26.51%20PM.png?raw=true)](https://drive.google.com/file/d/1ibUuSGAcfhTeRsVhMk2eaKtkEEuMv9Pb/view)

Skills: R, Data Visualization, Regression Algorithms, Multivariate Regresssion Analysis

In this project, I conducted a multivariate regression analysis on life expectancy data from the World Health Organization in order to provide reccomendations for the WHO, United Nations, and governments of developing countries on which factors of public health are most relevant and important to produce lasting changes in life expectancy. We conducted a thorough regression analysis in R in order to produce a final predictive model of life expectancy that had up to 80% accuracy on our training dataset. The link above will take you to my final presentation of my findings. 

## Analysis of Major League Baseball Data to build a predictive model for salary based on a number of player metrics
[![Example image preview](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-03-21%20at%208.11.18%20PM.png?raw=true)](https://drive.google.com/file/d/1gKu32uVhjyvuB9R3OL7kA2wefLnj0aJN/view?usp=share_link)

Skills: R, Data Visualization, Multivariate Regression Analysis

In this project, I conducted a regression analysis on salary data of MLB players using a number of predictive metrics including but not limited to, number of hits, runs batted during career, and the league that the player was in. 

## Complex Vector Class in C++

[![Example image preview](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-03-21%20at%208.35.00%20PM.png?raw=true)](https://gitfront.io/r/user-7760407/8AemFP4zu3YA/Complex-Vectors/)

Skills: C++, Operator Overloading, Objects, Pointers

In this program, I used created a Complex Vector class in C++ and used operator overloading to create a set of mathematical functions that would be able to process complex vectors.  

## Object Oriented Programming and String Streams in C++

[![Example image preview](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-03-21%20at%209.00.56%20PM.png?raw=true)](https://gitfront.io/r/user-7760407/Nk3yu4dPFVrd/Object-Oriented-Programming/)

Skills: C++, Parsing input data from files, Polymorphism, Object Oriented Programming 

In this program, I was given a file of data containing information about UCLA and USC students. I used string streams in C++ to parse the file and extract the relevant pieces of information. Using object oriented programming, I created classes for both UCLA and USC students to create student objects and store information about these students accordingly. 

## Bootstrapping and Randomization Trials
[![Example image preview](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-03-21%20at%209.43.35%20PM.png?raw=true)](https://drive.google.com/file/d/1Wd_MX7Pivouo9NDGah7sgHvAlWH4DM1z/view)

Skills: Statistical Methods of Bootstrapping using Likelihood functions

Using bootstrapping, I had to create 95% confidence interval of the probability parameter in a function that followed a geometric distribution. 

## Monte Carlo Study and Simulation of the game Chutes and Ladders

[![Image](https://github.com/sesha-csc/sesha-csc.github.io/blob/master/Screen%20Shot%202023-03-21%20at%207.29.32%20PM.png?raw=true)](https://drive.google.com/file/d/1BqdCylwaM3AL3brazOsTBnjwXM4ZeEL8/view)

Link to Full Project Repository: https://gitfront.io/r/user-7760407/BMxerLoKLGDP/Chutes-and-Ladders/

Skills: R, Graphics 

Through this project, I simulated two players playing a game of Chutes and Ladders. I built the board using graphics in R and arrows to indicate their movement. I also performed a final Monte Carlo Study to understand which ladders and chutes where the most landed on.

