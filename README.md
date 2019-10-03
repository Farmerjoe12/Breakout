# A Breakout clone written for the browser

With this version of Breakout (in contrast to [this version](http://github.com/Farmerjoe12/MDN_Game)) I used a JS framwork called Phaser. It is a simple graphics library making support for things like animations, tweens, and physics a whole lot easier than doing it by hand.

## New Update

The newest update comes in the form of hosting. This app can now be run with node.js. I followed some tutorials on the net to enable node.js hosting of this game, so I can host it natively on my PC instead of relying on github pages. Really this is inconvenient and I'd probably never do this in real life but it was a good quick project to learn node.

## Interesting Takeaways from Phaser

Using a 'game engine' framework makes developing games so much easier and more efficient. Adding a ball to the screen with movement and collision physics can be done in less than 10 LoC.

Reacting to events in game couldn't be simpler. Making game elements move and collide basically just requires the elements to be in the game and have collisions turned on.

## Possible Improvements

- Ball Velocity Changes
- HTML/CSS Menus
- Bonus scoring
- New modes
- Double balls
- Double paddles
- New 'maps'
- Scaling and resolution opportunities

## Check it out 

https://Farmerjoe12.github.io/Breakout

## If you want to use Node on your own machine

Download the source code and run 'npm install express'

Then, run 'node breakout.js' and connect to localhost:8081.
