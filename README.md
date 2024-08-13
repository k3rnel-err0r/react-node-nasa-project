# NASA Mission Control Project

This project is a React and Node.js application that simulates NASA's mission control interface for scheduling and managing space launches.

## Project Structure

The project is divided into two main parts:

1. Client (React frontend)

```
└── 📁client
    └── 📁public
        └── 📁img
            └── background-large.jpg
            └── background-medium.jpg
            └── background.jpg
            └── glow.png
        └── 📁sound
            └── abort.mp3
            └── click.mp3
            └── deploy.mp3
            └── success.mp3
            └── typing.mp3
            └── warning.mp3
        └── favicon.png
        └── index.html
        └── manifest.json
        └── robots.txt
    └── 📁src
        └── 📁components
            └── Centered.js
            └── Clickable.js
            └── Footer.js
            └── Header.js
        └── 📁hooks
            └── requests.js
            └── useLaunches.js
            └── usePlanets.js
        └── 📁pages
            └── AppLayout.js
            └── History.js
            └── Launch.js
            └── Upcoming.js
        └── App.js
        └── index.js
        └── settings.js
    └── .DS_Store
    └── .gitignore
    └── package-lock.json
    └── package.json
    └── README.md
```

2. Server (Node.js backend)

```
└── 📁server
    └── 📁data
        └── kepler_data.csv
    └── 📁public
        └── 📁img
            └── background-large.jpg
            └── background-medium.jpg
            └── background.jpg
            └── glow.png
        └── 📁sound
            └── abort.mp3
            └── click.mp3
            └── deploy.mp3
            └── success.mp3
            └── typing.mp3
            └── warning.mp3
        └── 📁static
            └── 📁js
                └── main.2664cbb8.js
                └── main.2664cbb8.js.LICENSE.txt
                └── main.2664cbb8.js.map
        └── asset-manifest.json
        └── favicon.png
        └── index.html
        └── manifest.json
        └── robots.txt
    └── 📁src
        └── 📁models
            └── launches.model.js
            └── planets.model.js
        └── 📁routes
            └── 📁launches
                └── launches.controller.js
                └── launches.router.js
            └── 📁planets
                └── planets.controller.js
                └── planets.router.js
        └── app.js
        └── server.js
    └── .gitignore
    └── package-lock.json
    └── package.json
```

## Installation

To install the project dependencies, run the following command in the root directory:
```
npm install-client
npm install-server
```

## Usage

To start the project, run the following command in the root directory:
```
npm run deploy
```