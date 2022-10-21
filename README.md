# Progressive-Web-Applications-PWA-Text-Editor
## Table of Contents
1. [Description](#description)
2. [Tech Use](#tech-use)
3. [Installation](#installation)
4. [Visuals](#visuals)
5. [License](#license)

## Description
This is a progressive web application that can function in a browser operating both online and offline. Additionally, the app can be used in a freestanding context and still operate correctly. 
## Tech Use
Heroku, Express, IndexedDB, Webpack & WebpackPwaManifest Plugins, Concurrently, Babel, and Babel extensions.

[Heroku Deployed Link](https://desolate-taiga-69412.herokuapp.com/)

[GitHub Repository](https://github.com/Zachattack221/Progressive-Web-Applications-PWA-Text-Editor)
## Installation
Run 'npm i' within the console, located at the root level of the directory. This will pull in the necessary node modules/packages from the root, client, and server level package.json files. 

Once necessary dependencies are installed, "npm run start:dev" (or 'nodemon server.js" if you have nodemon installed) in the console to concurrently build out and start the client and server simultaneously.

Optionally, this application is deployed live via Heroku, and can be accessed via the link above.


## Visuals
Manifest Setup
![Manifest](./images/Manifest.png)

Service Worker Setup
![Service Worker](./images/Service_worker.png)

Local Storage Working
![Local Storage](./images/Local_Storage.png)

Running App Functionally Offline
![Running App Offline](./images/Running_offline.png)

Running as Freestanding PWA 
![Freestanding PWA](./images/Freestanding.png)
## License
This application is licensed with the MIT License.