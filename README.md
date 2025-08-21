This game works on a new maze generation algorithm invented by @captainluma7991 on Youtube.
The algorithm is called Origin Shift
It goes as follows:

1. Start with a grid of nodes. Each has a direction property that can point nowhere, or to one of its neighbors.

2. Initialize the grid to be any perfect maze, that being a maze with no loops or isolated areas. Each node should point to one neighboring node, with a single node, the origin node, pointing nowhere.

3. Repeat the following steps for as many iterations as you'd like:
3a. Have the origin node, point to a random neighboring node.
3b. That neigboring node becomes the new origin node.
3c. have the new origin node point nowhere.


This is a working implementation of the algorithm described above in a fully working game format by me.
