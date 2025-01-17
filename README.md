# HTML5 Slot Machine

![Build and Deploy Status](https://github.com/dingosgotmybaby/html5-slot-machine/actions/workflows/deploy.yml/badge.svg)

This is a modern proof of concept casino slot machine game, built using only vanilla HTML, CSS and JavaScript.
No Flash or Frameworks required. Allowing for an amazing low bundle size and blazing fast performance.

Built using the _Web Animations API_.

## Features

- Fully responsive for great UX on mobile, web & fullscreen mode.
- Autoplay functionality, which keeps running even if the game window is in background.

## Installation, Build & Deployment

1. Clone repository
2. Run `npm install`
   - _Development_: run `npm start` and go to `http://localhost:8080`
   - _Production_: run `npm run build` and serve from `/dist`

## Configuration

For configuration options see `config` object in [index.js](/src/js/index.js)

| Property      | Description                                                                                                                            | Default   |
| ------------- | -------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| `inverted`    | Controls visual spinning direction of reels. If false, reels will spin from bottom to top. If true, reels will spin from top to bottom | false     |
| `onSpinStart` | Callback function invoked when spin starts with symbols pattern array `(symbols) => void`.                                             | undefined |
| `onSpinEnd`   | Callback function invoked when spin ends with symbols pattern array `(symbols) => void`.                                               | undefined |

## Credits

Icons are from [Game-icons.net](https://game-icons.net/) and are licensed under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)
