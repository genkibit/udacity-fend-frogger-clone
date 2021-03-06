Bug Frenzy
===


Description
---
Bug Frenzy is a basic clone of the classic game Frogger. It implements inheritance patterns commonly used in JavaScript programming. Inheritance is an important concept of object-oriented programming that makes for cleaner, maintainable code, especially when working with other developers on large applications.

This project also features used in web-based animation and game design.
  1. A game engine using `RequestAnimationFrame` and delta time
  2. Game modules for randomizing and adding behaviors to game entities
  3. Built-in tile-mapping engine
  4. Sound effects and background music using HTML5 Audio
  5. An HUD that shows level, score, timer, lives and audio toggle button


App Link
---
**<https://noelnoche.github.io/udacity-fend-frogger-clone/>**


How To Play
---
1. Click the cartridge to begin
2. Use the arrow keys to maneuver your character to one of the open grass blocks on top
3. Try to get all five characters to the top without colliding with a bug or obstacle


Scoring
---

| Action                        | Points |
|-------------------------------|:------:|
| Each second remaining         |   1    |
| Blue Gem                      |   5    |
| Green Gem                     |   10   |
| Orange Gem                    |   15   |
| Heart                         |   Extra life  |


Development
---
1. Run development build: `npm start`
2. Make changes to individual src/app/*.js files (except bundle.concat.js)
3. Open a second command terminal window
4. Concatenate the files in step 2: `npm run mk-concat`
5. Run eslint (make needed corrections and repeat from step 4): `npm run eslint`
6. Open the application in the browser: `localhost:8080`
7. To stop the server hit control + C
8. To compile production version: `npm run build`


Credits
---
+ Original game assets and engine by **[Udacity](https://www.udacity.com/)**
+ Original cartridge design by Atari, Inc
+ Game BGM:
	- "Daily Beetle" Kevin MacLeod **[incompetech.com](https://incompetech.com)**
	Licensed under Creative Commons: **[By Attribution 3.0](https://creativecommons.org/licenses/by/3.0/)**
	- "Vivacity" Kevin MacLeod **[incompetech.com](https://incompetech.com)**
	Licensed under Creative Commons: **[By Attribution 3.0](https://creativecommons.org/licenses/by/3.0/)**


License
---
Code is provided under an **[MIT license](https://github.com/noelnoche/udacity-fend-frogger-clone/blob/gh-pages/LICENSE.md)**.
