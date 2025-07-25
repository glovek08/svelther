<picture>
  <source srcset="static/svelther-logo_light.png" media="(prefers-color-scheme: dark)">
  <img src="static/svelther-logo_dark.png" alt="Svelther Logo" width="300">
</picture>


A simple weather showcase app built with [Svelte](https://svelte.dev/) and [SvelteKit](https://kit.svelte.dev/).  
This project demonstrates how to fetch and display weather information based on the user's current location.

![Built with Svelte](https://img.shields.io/badge/Built%20with-Svelte-%23FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![Powered by Vite](https://img.shields.io/badge/Powered%20by-Vite-%23646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Node >= 20](https://img.shields.io/badge/Node-20+-339933?style=for-the-badge&logo=node.js&logoColor=white)
![NPM >= 10](https://img.shields.io/badge/NPM-10+-CB3837?style=for-the-badge&logo=npm&logoColor=white)

## Features

- Detects user location (with permission).
- Fetches current weather for the detected location.
- Clean, minimal UI built with Svelte.

## How it Works

- Uses the browser’s Geolocation API to get the user's latitude and longitude.
- Fetches weather data from ![Open-Meteo](https://www.open-meteo.com) API
- Displays the current weather for the user's location.

## Technologies Used

- [Svelte](https://svelte.dev/)
- [SvelteKit](https://kit.svelte.dev/)
- [Vite](https://vitejs.dev/)
- JavaScript
- [Node.js](https://nodejs.org)
