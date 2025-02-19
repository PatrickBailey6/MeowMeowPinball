# MeowMeowPinball
Carolina Club Pinball's custom pinball machine project, headed by Patrick and Delphine

## Overview
This is a pinball machine centered around a dog-cop in a "dog-eat-dog-eat-cat world"
The theme of the pinball machine is that a bunch of bad cats have all gotten out of the bag, and as a cartoonish dog dressed as a cop it's your job to put them away.

## Game Basics
As most people haven't played much pinball, I'll explain a bit about the flow of the game: As you shoot the ball from the __flippers__ at the bottom into lanes at the top or targets, you'll score some points and open up missions. The missions are skilled objectives, directing the player to make specific __shots__, which are typically denoted using flashing leds and bright colors, as well as the LCD screen assisting in this direction. The better you do on these missions without draining the ball (letting it fall to the bottom), the more you can unlock and the bigger the __jackpot__ will be.

## How are we doing this?
We are using a few different systems: 
1. Using a Raspberry Pi to run the software controlling the game flow.
2. We use the MPF software on the Pi
3. The FAST pinball system is middleware that gets signals from software and sends it to playfield hardware

We'll integrate all of these systems with pre-existing pinball hardware to get a fully-working game
