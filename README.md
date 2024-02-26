# Grid-Search

This repository contains a JavaScript implementation of a search algorithm, designed primarily for pathfinding in grid-based environments. The main focus of this implementation is to provide a flexible and efficient solution for various search scenarios.

## Contents

Introduction <br>
Features  <br>
Usage   <br>
Class Structure   <br>
Node Representation  <br>
Functions and Methods  <br>
Examples  <br>


## Introduction

Pathfinding algorithms are essential in various applications such as robotics, video games, and logistics. This JavaScript implementation offers a versatile solution for finding optimal paths in grid-based environments. It is based on the A* search algorithm, enhanced with graph search techniques.

## Features

Flexible grid representation.
Efficient A* search algorithm implementation.
Support for different heuristic functions.
Customizable search configurations.
Modular and extensible code structure.

## Usage

Include the Search_Student.js file in your JavaScript project.
Create a grid environment and configure the search parameters.
Initialize an instance of the Search_Student class with the grid and configuration.
Start the search by calling the appropriate methods and iterate until completion.
Retrieve the path or other relevant information from the search results.


## Class Structure

The main class in this implementation is Search_Student, which encapsulates the search functionality. It contains methods for initializing the search, performing search iterations, computing heuristics, and checking if actions are legal. Additionally, there is a Node class representing nodes in the search tree.

## Node Representation

Each node in the search tree is represented by the Node class. It contains attributes such as coordinates, parent node, action, cost, and heuristic. These attributes facilitate efficient pathfinding and search progress tracking.

## Functions and Methods

canFit(x, y, size): Determines if an agent of a given size can fit in a specified location.
computeSectors(): Computes and stores connected sectors in the grid.
isConnected(x1, y1, x2, y2, size): Checks if two locations are connected in the grid.
isLegalAction(x, y, size, action): Determines if an action is legal at a given location.
startSearch(sx, sy, gx, gy, size): Initializes the search with start and goal locations.
estimateCost(x, y, gx, gy): Computes the heuristic function from a given location to the goal.
searchIteration(): Performs one iteration of the A* search algorithm.
getOpen(): Retrieves the current open list states.
getClosed(): Retrieves the current closed list states.


## Examples

Refer to the examples provided in the repository for usage demonstrations and integration with different grid environments. These examples showcase how to initialize the search, configure parameters, and retrieve search results.




## Easy
<img width="769" alt="image" src="https://github.com/BilalNaseer7773/Grid-Search/assets/90666694/abdab8f3-a013-46b5-a673-9cf411fd77a6">

<img width="774" alt="image" src="https://github.com/BilalNaseer7773/Grid-Search/assets/90666694/c646ba2e-c0bc-4502-9c31-17f655db86ff">

## Medium
<img width="772" alt="image" src="https://github.com/BilalNaseer7773/Grid-Search/assets/90666694/2bcfb37c-dded-4bb3-b2b0-0cf9de226171">

<img width="769" alt="image" src="https://github.com/BilalNaseer7773/Grid-Search/assets/90666694/6bbf84cd-84c1-456f-b6b1-7b54a8072971">

## Medium Hard
<img width="764" alt="image" src="https://github.com/BilalNaseer7773/Grid-Search/assets/90666694/502ebfe2-97e1-4853-880e-954514a03bd7">

<img width="767" alt="image" src="https://github.com/BilalNaseer7773/Grid-Search/assets/90666694/5492bbc6-ac2c-4c15-ac21-19572b937462">


## Hard
<img width="769" alt="image" src="https://github.com/BilalNaseer7773/Grid-Search/assets/90666694/256a2f71-4dab-4b04-bd3a-f3a9c79060c9">

<img width="772" alt="image" src="https://github.com/BilalNaseer7773/Grid-Search/assets/90666694/f8d799d2-894d-4a9e-baa9-a34469ec3835">
