---
title: Graphical Game Solver
layout: page
---

## Inspiration

Recently, doing LeetCode questions with trees and graphs and taking a game theory course at school made me wonder if I could apply concepts from graph and game theory together. I've been practicing using C++ a lot on LeetCode, so I chose to use it with Qt to make an app to solve game trees! 

## What it does

The app allows you to draw trees by dragging and dropping decision nodes as well as edges. You can specify the payoffs and which player is making an action on a node by double clicking on the nodes. Once the game is drawn, click the solve button and the app will highlight the subgame perfect equilibrium (the outcome of the game where if both players play optimally, no player is better off) of the game. 

## How I built it

The app is built with Qt and C++. Working on this project really helped my object oriented programming skills in C++. 

## Challenge I ran into

Getting into serious C++ OOP for the first time was a bit of a challenge at first, learning how classes were defined and implementing them. Learning the Qt library also seemed complicated at first, but after working on it, I realized it wasn't bad. The solving part of the program wasn't actually very hard to implement once the graph drawing functionality was complete. 
