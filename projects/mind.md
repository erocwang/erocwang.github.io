---
title: Mind Reading Machine
layout: page
---

## Inspiration

In a low level programming class at school, we learned about Claude Shannon, who proposed that humans were not a good source of random information. He supported his theory with a by creating a series of machines called _mind readers_. Here I have created my own _mind reader_ which guesses binary user input (0/1, L/R, etc). 

## What it does

The app pits the user against a bot which uses the user history to make educated guesses on the next input. The bot will receive a point if it guesses correctly, and the user will receive a point otherwise. 

## How I built it

The app is built with JavaScript and React. Essentially, the program will keep track of different lengths of user history and use that information to make a guess on the next input. Each substring predictor has a running accuracy percentage which the program uses to choose the best candidate to get a prediction from. 

## Challenge I ran into

It was difficult to keep track of user input with my current choice. Right now, the program uses multiple nested maps in order to keep track of substrings and predictors. This makes reading and generating more support code harder. In the future, the app will be improved using predictor classes instead of maps. 


