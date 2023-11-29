# Multi-window-pong-game
Play pong game across multiple windows on the same origin using localStorage. Inspired by [this](https://github.com/bgstaal/multipleWindow3dScene) project. I hope you enjoy it!

## Demo
![preview](./preview.gif)

## How to run
1. Clone the repo
2. open `index.html` in multiple windows tabs

## How it works
* Using `localStorage` to store the game state and sync it across multiple windows. 
* `screenX` and `screenY` are used to calculate different window positions.
* Maybe [window.getScreenDetails()](https://developer.mozilla.org/en-US/docs/Web/API/Window/getScreenDetails) can be used to get the window position in the future.

## License
[MIT](./LICENSE)
