# Solve-Monty-Hall-Problem-in-R
http://www.bodowinter.com/tutorial/bw_doodling_monty_hall.pdf. A HUGE THANK YOU to BODO WINTER 

## Introduction
In this project we are going to solve this Monty Hall problem in R language.

## What is Monty Hall problem?
<img width="362" alt="screen shot 2018-07-11 at 3 50 57 pm" src="https://user-images.githubusercontent.com/39840213/42597921-8530a51c-8528-11e8-9879-596b53209e5c.png">

Source:  https://en.wikipedia.org/wiki/Monty_Hall_problem

## What is Monty Hall problem in text? 
Assume that a room is equipped with three doors. Behind two are goats, and behind the third is a shiny new car. You are asked to pick a door, and will win whatever is behind it. Let's say you pick door 1. Before the door is opened, however, someone who knows what's behind the doors (Monty Hall) opens one of the other two doors, revealing a goat, and asks you if you wish to change your selection to the third door (i.e., the door which neither you picked nor he opened). The Monty Hall problem is deciding whether you do. 


### So, let’s get started!!! 
First, we need to make a vector “doors” with three doors: “A”, “B” and “C”.
```
doors <- c("A", "B" , "C")
```
