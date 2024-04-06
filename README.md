## Suroi16

<div align="center">
  <img src="https://img.shields.io/badge/node.js%20-%23339933.svg?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/typescript-%233178C6?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/pixijs%20-%23e22162.svg?style=for-the-badge">
  <img src="https://img.shields.io/badge/uwebsockets.js%20-%23000000.svg?style=for-the-badge">
  <img src="https://img.shields.io/badge/html-%23E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/css-%231572B6?style=for-the-badge&logo=css3">
  <img src="https://img.shields.io/badge/sass-%23CC6699?style=for-the-badge&logo=sass&logoColor=white">
  <img src="https://img.shields.io/badge/vite-%235468FF.svg?style=for-the-badge&logo=vite&logoColor=white">
</div>

## About
Suroi 16 is an open source game  inspired by the surviv.io, incorporating its assets. This project is still in progress.

## How to Contribute:
Join our discord server and contact one of the staff
[suroi16 discord server.](https://discord.gg/JxHmKAhbmG)

## Play the game!
[suroi.io](link soon...)

## Join the Discord!
[suroi16 discord server.](https://discord.gg/JxHmKAhbmG)

## Installation and setup
Start by installing [Node.js](https://nodejs.org) and [pnpm](https://pnpm.io).

Next, [click here to download the repo](https://github.com/noraaaaaaaaaaaaaaaa/Suroi-16.git), or use the following command to clone it:
```sh
git clone https://github.com/noraaaaaaaaaaaaaaaa/Suroi-16.git
```

To install dependencies, open a terminal in the project root, and run this command:
```sh
pnpm install
```

This will create a `node_modules` directory in all three folders (`client`, `common`, and `server`) and link the packages there.

## Development
To run the game locally, open a terminal in the project root and run the following:

```sh
pnpm dev
```
To open the game, go to http://127.0.0.1:3000 in your browser.

## Production
To build for production, run this command in the project root:
```sh
pnpm build
```

To start the WebSocket server, run this command:
```sh
pnpm start
```

Production builds are served using [NGINX](https://nginx.org). A sample configuration file can be found [here](nginx.conf).

## Self-hosting
Visit [the wiki](https://github.com/HasangerGames/suroi/wiki/Self%E2%80%90hosting) for details on how to self-host.
