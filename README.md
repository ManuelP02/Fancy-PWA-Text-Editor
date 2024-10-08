# Fancy PWA Text Editor -JATE -

## Description

JATE is a Progressive Web Application (PWA) text editor that runs in the browser. It allows developers to create notes or code snippets with or without an internet connection, ensuring reliable retrieval for later use.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)

## Features

- Single-page application that meets PWA criteria
- Works offline
- Uses IndexedDB for data persistence
- Implements multiple data persistence techniques as redundancy
- Bundled with webpack
- Creates a service worker with workbox that caches static assets
- Uses babel to use async / await
- Generates a manifest.json using the WebpackPwaManifest plug-in
- Can be installed as a desktop application

## Installation

1. Clone the repository
2. Run `npm install` in the root directory to install dependencies
3. Run `npm run build` to build the client

## Usage

1. Run `npm run start` from the root directory to start the backend and serve the client
2. Open your browser and navigate to `http://localhost:3000`

## Technologies Used

- JavaScript
- Node.js
- Express.js
- IndexedDB
- Webpack
- Workbox
- Babel

## Deployment

This application is deployed on Render. To deploy your own instance:

1. Ensure your repository includes the `.npmrc` file from the starter code
2. Follow the Render Deployment Guide
3. Set the build command to: `npm install && npm run build`
4. Set the start command to: `cd server && node server.js`

## Demo

[Deployed app link](https://fancy-pwa-text-editor.onrender.com/)

### Images

#### Index on browser

![index-on-browser](https://github.com/user-attachments/assets/02ca51d8-2604-4487-9694-0a7587462442)

#### Index installed

![index-installed](https://github.com/user-attachments/assets/536e85c6-a9ca-4556-a0fa-6efbfc78593b)

#### Service worker

![service-worker](https://github.com/user-attachments/assets/133cc1a1-a0ad-43a5-a68d-52ce116de633)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions you can contact me at: m.e.penafernandez@gmail.com
