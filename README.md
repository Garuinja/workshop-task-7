Link - https://garuinja.github.io/workshop-task-7/

### Brief Account of Experimentation
- I intended to go with using the random walk system but I ended up with a random particle system because walk systems have the background to be in the setup function and particle systems have the background in the draw function. I should also say that I forked Ella Pan's workshop task 0 code (https://ellap4n.github.io/workshop-task-0/) which already has the background in the draw function and moving it to the setup function affects the appearance of other elements in the code. So in the end I modified the the code so that whenever the mouse hovered over the the red, blue or yellow circles not only would the circles on the pie would appear but so would the particles.

### Problem Solving
- When applying the walk system into the Ella's code it wasn't working for whatever reason until I realised that the for loop in the draw function had `balls.move();` instead of `balls[x].move();`

### Future Development
- I would like to find a way to also include the walk system so then the walk system would be visible and then the mouse hovering could reveal the particle system.
