This project is my entry for [promted.com)](https://www.prmpted.com/?ref=hadi_1_referral]). It's a tower defense game. At the time of submitting it to the contest, it had 13 different types of monsters, 3 kind of towers and only one set of surface graphics. The major goal of that game is to kill all the monsters approaching you via choosing the right amount of towers.

## Play the game!

[Just click here :)](https://ha1381di.github.io/promted-tower-defense/)

## "13" related details
- 13 monster types
- 13 health points
- 13 seconds wave delay
- 13 waves to defeat
- 13 supported browsers (maybe more ...)
  - OS X
    - Chrome 21
    - Firefox 14
    - Safari 6
    - Opera 12
  - iOS
    - Mobile Safari
    - Chrome
    - Dolphin
    - Mercury
  - Android
    - Dolphin (a bit slow and for some reason it's not correctly detecting touched fields)
  - Windows
    - IE9 (bullet animation broken because of missing css3 transition support)
    - IE10 (bullet animation broken because of missing css3 transition support)
    - Chrome 21
    - Firefox 14


## Build the dist:
```js
npm install
npm run build
```

## Build a ZIP file
```js
npm run build-zip
```

## Check dist size:

```js
npm run check
```

## Full featured game start

As this game uses `prefixfree` it is necessary to start the game via a webserver:

```js
npm run server
```

Afterwards just open the game via `http://localhost:8080`.
