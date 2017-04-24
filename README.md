# CS216PA3
CS 216 project assignment 3

Six Degrees of Kevin Bacon is a parlor game based on the "six degrees of separation"
concept, which posits that any two people on Earth are six or fewer acquaintance links apart.
The goal of the game is to find the shortest path between an arbitrary actor and
prolific character actor Kevin Bacon.

A program that implements the “Six Degrees of Kevin Bacon” game using a graph. each actor is assigned
to a vertex, and an edge is added between two actors if they have appeared together in a movie. Then the shortest
path between an actor and Kevin Bacon is found using Breadth-First Search. The bacon number and the path from the
actor to Kevin bacon is outputed

The computation of a Bacon Number for actor X is a "shortest path" algorithm, applied to the
co-stardom network:
• Kevin Bacon himself has a Bacon Number of 0.
• Those actors who have worked directly with Kevin Bacon have Bacon Number of 1.
• If the lowest Bacon Number of any actor with whom X has appeared in any movie is
N, X's Bacon number is N+1.

.
