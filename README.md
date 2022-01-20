### Angular/Ngrx game

Application requires [Node.js](https://nodejs.org/) v10+ to run.
Install the dependencies and devDependencies and start the gamr.

```sh
clone repository
cd angular-ngrx-bombs-game
npm iinstall
npm run start
```

### Tech stack

* Angular 13
* ngrx/store 13
* rxjs 7
* typescript 4
* Karma/Jasmine

### Brief game description

> Bombs are colored circles
There are 3 colored bins at the bottom of the screen.
The colors of these bins swap every 40 seconds.
Countdown for this change at the bottom right presented.
Circular coloured "bombs" are spawned above these bins.
The "bombs" have a random lifetime from 5 to 10
seconds, which are visible on the bomb.
At the end of its lifetime the bomb is removed.
The aim of the game is to drag a "bomb" and drop it into a
bin of the same colour before the bomb disappears or the
bin changes colour. 1 point is gained for each successful
drop. 1 point is lost for each "bomb" that is removed before
it is placed in a bin or if it is placed in the wrong coloured
bin.
The bin changes its color shade and increases in size
when a "bomb" is dragged onto it.
The current points are displayed in the top left.
The game ends after 120 bombs have been placed on the canvas.
Bombs are spawn with an increasing frequency, starting
every 5 seconds at the beginning and spawning every 0.5
seconds by the end of the game.