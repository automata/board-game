# WIP: Board Game

![2016-02-08](https://cloud.githubusercontent.com/assets/49062/12925773/1d0138e2-cf47-11e5-95a4-02692904457d.jpg)

Combines elements from Catan, Carcassonne and Ticket to Ride, the known board game triad.

# Material

- Three decks
  - 84 Tiles of ground
  - ?? Cards of resource
  - ?? Cards of goals
- 8 Peebles for each player
- ?? Markers

# Mechanics

## Starting

1. Shuffle both decks
2. Distribute 8 peebles and ?? markers for each player
3. Some player starts its turn

## Turn

Each player should do on its own turn:

- *(1)* Draw a tile from the deck and place it on a valid position (like Carcassonne)
  - If it's a resource tile, place a peeble on it. The tile will generate a resource
- *(2A)* Place markers on a path *if* it has enough resource and match path/resource card colors
  - A player can't place markers when path's edges have peebles of somebody else
- *(2B)* Buy a goal
- *(3)* Play the dice and generates resource cards for itself, matching dice color

# Scoring

- Sum the points from goal cards, player with large amount of points wins
