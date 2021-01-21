---
title: Nematode Path Finding Visualizer
layout: page
---

## Inspiration

I've wanted to make a path finding visualizer for a while after watching several Youtube videos on them. I finally decided to do one when I heard about how nematodes search for their food. The process seems very mechanical, and definitely programmable enough to simulate. 

## What it does

The app lets the user visualize a nematode's path and search for a food source. A start node and end node are specified and the user can also add walls if they like. Once started, the program will simulate the path and then animate it. At the bottom of the screen, you will see the primary neural circuits that are associated with the nematode. 

## How I built it

The app is built with JavaScript and React. Nodes are represented as small divs and the searching algorithm is implemented as a pseudo random search process. 

## Challenge we ran into

As my first time with React and JavaScript, it was difficult at first to understand the syntax and framework but now I feel comfortable working with it. One issue with the algorithm is that sometimes the nematode will spend a lot of time searching more towards the food source. This is counterintuitive, but I haven't come up with an ideal solution. Essentially, the nematode will on average travel towards open nodes that are closer to the food sources. However, as it approaches the food source, the relative distances to the food source become more equal. As a result, the nematode gets more confused as it moves towards the source. 
