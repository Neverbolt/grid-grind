# Grid Grind
<img src="http://i.imgur.com/WSyzRU2.png" width="800px">

## Table of Contents
* [Game Info](#game) <br>
* [Demo](#demo) <br>
* [Usage](#usage) <br>
* [Updates & To-do](#todo)

<h2>
	<a name="game" aria-hidden="true" class="anchor"></a>
	Game Info
</h2>
### *How to Play* <img src="http://image.flaticon.com/icons/png/512/25/25400.png" width="20px">

Click any of the color blocks and watch them change to the next color. **I will be implementing a visible color pattern below the game so you can see in which order the blocks change.** The idea is that you have to be careful what order you change the blocks in. I'll put up an example soon.

### *Objective* <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/71/Ok_sign_font_awesome.svg/600px-Ok_sign_font_awesome.svg.png" width="25px">
The objective of this game is to obtain points by clicking the blocks and creating chains of the same color. If a chain is only three colors long then only 1 point is given for each block. As the chains get bigger, the points obtained per block get bigger and bigger.

**At the moment there is no level or point tracking system.**

### *Moving to the Next Level* <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/03/Plus_sign_font_awesome.svg/512px-Plus_sign_font_awesome.svg.png" width="25px">
In order to move to the next level I will eventually implement a point counter. If you don't obtain a certain number of points on a level with the given number of tries then you will have to start over. If you complete a certain number of levels successfully then you will be awarded bonus moves or extra tries.

<h2>
	<a name="demo" aria-hidden="true" class="anchor"></a>
	Demo
	<img src="http://zanifesto.com/zfassets/graphics/ionicons/game-controller-b-512px.svg" width="30px">
</h2> 
This game is still under construction, but a demo version of the game will be available at apps.alexmdodge.ca/gridgrind

<h1>
	<a name="usage" aria-hidden="true" class="anchor"></a>
	Usage
</h1>
This game leverages Phaser, jQuery, and a couple of other pieces to make it go!

```
npm install
bower install
```

To get started. Then use your gulpfile to run the build and try it out yourself,

```
gulp
```

<h1>
	<a name="todo" aria-hidden="true" class="anchor"></a>
	Updates & To-do
</h1>
There are a number of upcoming features listed here!

* Finish first level game state
  * Number of tries
  * Intro screen with game name
  * Progress points bar or similar
  * Block patter hint in bottom
  * Point chain for certain color chain lengths
* Multi level game states
  * Accumulated total
  * Player name on end message
  * Simple db for storing wins and score
  * Random pattern frame each level
  * Explosion tile hidden in pattern
  * Obstacles in later levels
  * Timer for later levels
