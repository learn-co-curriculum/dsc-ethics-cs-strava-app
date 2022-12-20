# Case Study - Strava Fitness App

## Introduction
In previous lessons, we discussed data privacy and data security and the role of governments, companies, and users, to safeguard data from exploits. However, there are also situations where __public data__ can actually be a sensitive feature. Let's explore the case of __Strava Fitness App__ and how they threatened national security with a network designed to help you find a gym buddy.

## Learning Objectives

## Case Summary
Strava emerged in 2008 as a popular app for fitness enthusiasts to share workouts and network in the fitness space. One of Strava's most lauded features, a heatmap that visualized all of the users working out at a given moment, was released in 2015 and quickly became a cause for concern among those in the data privacy space. 

At the time of its update in 2017, Strava had over 27 million users, which resulted in over three trillion GPS data points. In the publication __Data Pollution__ (Ben-Shahar, 2018), the author Omir Ben-Shahar describes the Strava Fitness app as an example that illustrates how  a database can reveal information affecting public interests other than the users’ privacy. Let's discuss why Strava's seemingly innocuous use of public data can have a harmful impact and solutions that exist to navigate the use of public data.

* Strava enables millions of users to post map depictions of their physical workouts online, to be then viewed en masse in a “heat map” that may be accessed by anyone. 

* Because the map exposes large concentrated clusters of users in areas of dense activity, even in remote locations like the Sahara desert, it allows for bad actors to deduct secret geographic locations of U.S. military operations. Ben-Shahar asks the readers:
> "What else could a cluster of physical workouts in the Sahara Desert, or in an outskirt of an Afghan city, stand for?"

Strava's retention of the data presents an additional security risk as bad actors could also obtain detailed records of the location data used to populate the maps that is connected to user accounts. Recently, FakeReporter (a group of Israeli cybersecurity researchers) released a report that demonstrated another feature within Strava was used likely exploited by bad actors to obtain information about Israeli soldiers at six bases throughout the country. 

## Summary
