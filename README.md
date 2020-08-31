Reactive framework such as Angular or bootstrap are not precise enough for some
types of content such as comic books, in which different screen sizes and orientation
can dramatically alter the flow and readability of the story.  

FramesJS let's you precisely define different views for different 
screen types and then figures how to best render your site or page 
for any possible screen size or resolution.

check out the demo


# thegrid

This is a repository for an idea for a game I had. I'm not sure when I'll be able to earnestly work on it, but I wanted to put down the idea somewhere before it slips away. 

The grid is a multiplayer game based on the ancient game of Go. The rules: 

- The game can be played by up to 5 players on a grid board (200 x 200)
- Each player is assigned a color. At the start of the game, each player has 4 stones to place on the board. Then, each player gets a new stone 30 seconds after placing the last stone
- stones start to decay as soon as placed on the board, and lose about 10% of their density every 30 seconds, until they vanish completely. This last rule is to prevent the formation of permanently safe territories, which are common in Go. 
