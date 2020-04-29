# LandBaron



Rules: 

Here is a game my friend Carter Woetzel and I coded last year (2019). The objective of this game is to make the most money by bidding on properties that are placed on a grid that can range from 4x4 tiles to 7x7. The players each have a set budget and can outbid eachother on any tile that is not off limits or a company tile. Once both players are out of money or decide to pass on bidding back to back, the game is over. The company used Dijkstras path finding algorithim to determine the cheapest path from the upper left corner to the bottom right corner. If this path goes through a tile owned by a player, they get compensated the amount they bidded on that tile from the company. Whichever player gets more compensation from the company wins the game.



Quick Summary of classes:

The Tile class creates tile objects with a whole array of attributes such as the tiles value, type, and color

The ColorofTile class changes the tile color based of its current color attribute value

The LandBaron class contains all the backend things like Dijstras algorithm, the board generator code, and the instructions to update a tile if a player bids on it

The Main contains the code to drive the LandBAron class and the interactable GUI.



What I learned from This Code:

This project taught me how to implement GUIs, Dijkstra's Algorithm, Priority Queues, Object Oriented Programming , and much more. I also learned the process of planning large coding projects with a partner. Up until Carter and I coded this thing, we had no idea how much time goes into testing and debugging projects at a larger scale. At times it was frustrating, but overall it was a lot of fun and a good challenge for the two of us.

