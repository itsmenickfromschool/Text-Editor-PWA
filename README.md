# Just Another Text Editor (J.A.T.E)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
Just Another Text Editor (J.A.T.E) is a Progressive Web Application (PWA) that allows users to write, save, and access text notes with or without an internet connection. This application demonstrates the use of IndexedDB for data storage and retrieval, service workers for offline functionality, and webpack for asset bundling.

## Table of Contents
- [Technical Features](#technical-features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [License](#license)
- [Credits](#credits)
- [Questions](#questions)

## Technical Features
- **IndexedDB**: Implements an object store with GET and PUT methods for persistent data storage.
- **Offline Functionality**: Utilizes service workers to enable application functionality without an internet connection.
- **Auto-save Feature**: Automatically saves content inside the text editor when the window is unfocused.
- **Webpack Bundling**: Assets are bundled using webpack.
- **Service Worker with Workbox**: Caches static assets for offline access.
- **Async/Await**: Uses babel to leverage async/await for asynchronous operations.
- **PWA**: Includes a generated `manifest.json` using WebpackPwaManifest plugin and can be installed as a Progressive Web Application.

## Installation
To install the application locally:
1. Clone the repository to your local machine.
2. Run `npm install` to install dependencies.
3. Use `npm run build` to build the application using webpack.

## PWA Installation
To install the PWA:
1. Navigate to the [live URL](https://text-editor-pwa-production.up.railway.app/) of the application.
2. Look for a browser prompt or icon in the address bar indicating that the app can be installed.
3. Follow the browser’s instructions to complete the installation.
4. Once installed, the app will be available on your device like any other installed application.

## Usage 
After installation, run `npm start` to launch the application. The application allows users to write and save notes, with the added capability of functioning offline.

To use the PWA, after installing it search for it on you computer and use like any other app on your machine!

## Deployment
- **Live URL**: [Deployed Application](https://text-editor-pwa-production.up.railway.app/)
- **GitHub Repo**: [GitHub Repository](https://github.com/itsmenickfromschool/Text-Editor-PWA) 

## License
This application is covered under the MIT license.

## Credits
Developed by [Nicholas Burr](https://github.com/itsmenickfromschool) with starter code provided by EDX.

## Questions
For questions and inquiries, contact me at:
- GitHub Profile: [Your GitHub Profile](https://github.com/itsmenickfromschool)
-[Email](mailto:nicholasstclairburr@gmail.com)

## Screenshots
[Main Page](./screenshots/mainsite.png)
[Install](./screenshots/install.png)
[Installed Locally](./screenshots/beans.png)

