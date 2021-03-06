# Software Requirements Specification

## Purpose of the app

**Tower Defence** is a classic tower defence game. The point of the game is to prevent waves of attacking invaders from reaching the end of the maze. This is done by building towers along the way and trying to eliminate as many attacking invaders as possible. Building towers costs gold and gold is acquired via surviving waves and eliminating invaders. There are multiple kinds of towers. There is currently only one types of invaders. The game comes with just one map, but users can create their own maps.

## First draft of UI

The game is consists of two different windows: one is for the configuration of settings(for example selecting the level to play, changing % of invader hit points and starting the game) and a second one for the actual game.  UI is made using **JavaFX**. *The image below illustrates this.*

<img src="https://raw.githubusercontent.com/Melimet/TowerDefence/master/documentation/pictures/UIFirstDraft.png" width="750">

*The image below is an artist's illustration of what the game window might look like.*

<img src="https://raw.githubusercontent.com/Melimet/TowerDefence/master/documentation/pictures/ConceptPicture_TowerDefence.png" width="750">

## Functionalities provided by a basic version
### Configuration window 

- Player can choose from different maps to play
- Player can change the difficulty of the game by increasing/reducing the hitpoint % of invaders
- Player can start the game by pressing start button

### Game window

- Player can play the game from start to finish
  - Game ends when player runs out of lives or player makes through all of the waves

- Player can build different kinds of towers 
  - Towers cannot be placed on roads
  - Player must have enough gold to build a tower and gold is deducted after building a tower
  - Towers attack automatically whenever there is an invader inside their range of fire

- All waves are different and become progressively harder as the game progresses
  

## Ideas for further development

- Database for high scores
- Prettier models for towers and invaders
- Pausing the game
- Hotkeys for different towers instead of only drag and drop
- More maps/towers/invaders
- Saving & loading game. If this feature gets added it will most likely be only able to continue from the start of the current wave, not the exact state the game was left in.

