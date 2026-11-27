# Virtual Guy — Platform Game

[![Play Online](https://img.shields.io/badge/Play%20Online-Live%20Preview-brightgreen?style=for-the-badge)](https://virtual-guy-live-preview.netlify.app/)

A 2D side-scrolling platform game developed with Construct 2 and exported for HTML5. The project was originally published in 2023 as **Virtua Guy**, a pixel-art platform game designed around a fun and challenging side-scrolling experience.

## Play Online

**[▶ Play Virtual Guy](https://virtual-guy-live-preview.netlify.app/)**

The game runs directly in the browser without requiring an installation.

## About

Virtual Guy is a browser-based 2D platform game featuring a side-scrolling format, pixel-art presentation and gameplay focused on navigating platforms and obstacles.

The project is part of my practical experimentation with game development using Construct 2, including gameplay logic, multimedia assets, browser deployment and HTML5 export.

The project was also published as a commercial HTML5/Construct game in 2023.

## Features

- 2D side-scrolling platform gameplay
- Pixel-art visual style
- Platform-based level navigation
- Character movement and jumping
- Enemies and environmental obstacles
- Collectible and interactive game elements
- Sound effects and background music
- Browser-based HTML5 gameplay
- Mobile-oriented HTML5 configuration
- Fullscreen web-app configuration
- Offline/service-worker support included in the exported project

## Technologies

- **Construct 2** — game development
- **HTML5** — browser deployment
- **JavaScript** — Construct 2 runtime
- **jQuery 3.4.1** — included in the exported project
- **Web App Manifest** — application configuration
- **Service Worker** — offline support

## Project Structure

The repository contains the exported HTML5 version of the game, including:

- `index.html` — main HTML5 entry point
- `c2runtime.js` — Construct 2 runtime
- `data.js` — exported game data
- `jquery-3.4.1.min.js` — jQuery dependency
- `appmanifest.json` — web-app configuration
- `sw.js` — service worker
- `images/` — game images and visual assets
- `media/` — audio and multimedia assets
- `icon-*.png` — application icons

## Running Locally

Because this is an exported HTML5 game, it can be tested locally through a web server.

For example, with Python installed:

```bash
python -m http.server 8000
```

Then open:

```
http://localhost:8000
```

Opening `index.html` directly may not provide the same behavior as serving the project through HTTP, particularly for browser features such as the service worker.

## Development Context

This project demonstrates practical work with Construct 2 and the process of turning a game project into a browser-playable HTML5 application.

The project was originally published in **2023** and later maintained in this repository as part of my portfolio of development and study projects.

## Author

**Coelho**

GitHub: [@coelho-anon](https://github.com/coelho-anon)

---

**[Play Virtual Guy Online →](https://virtual-guy-live-preview.netlify.app/)**
