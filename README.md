# text-editor
Text Editor

## Description.

In this challenge, you are asked to build a browser-based text editor that works online and offline. It should save content using IndexedDB, be a Progressive Web App (PWA), and use idb for database interaction. Implement a client-server folder structure, bundle JavaScript files with webpack, and handle modern JavaScript. Provide desktop installation and deploy to Heroku with proper build scripts.

# Overview

## The Challenge:
The challenge is to create a text editor that works in a web browser and can be used offline. It should store data using IndexedDB as a backup option. You will use the idb package to handle data storage. The finished project needs to be deployed to Heroku. The goal is to build a reliable tool for creating and saving notes or code snippets, accessible both online and offline.

## Usage Instructions:
Following these instructions will allow you to create and retrieve notes or code snippets reliably using the text editor web application, both with and without an internet connection.

1. Open the text editor web application in your editor.
2. Upon opening, you should see a client-server folder structure.
3. From the root directory, run npm run start to start up the backend and serve the client.
4. Run the text editor application from your terminal, ensuring that your JavaScript files are bundled using webpack.
5. Run your webpack plugins to generate an HTML file, service worker, and manifest file.
6. Utilize next-gen JavaScript in your application, ensuring that the text editor functions in the browser without errors.
7. When you open the text editor, IndexedDB should immediately create a database storage.
8. Enter content in the text editor and click off the DOM window to save the content using IndexedDB.
9. Upon reopening the text editor after closing it, the content should be retrieved from IndexedDB.
10. Click on the Install button to download the web application as an icon on your desktop.
11. Load the web application, which should register a service worker using workbox.
12. Upon registering the service worker, your static assets should be pre-cached upon loading, including subsequent pages and static assets.
13. When deploying to Heroku, ensure you have proper build scripts for a webpack application.

## Installation Process:
1. Clone the starter code repository.
2. Navigate to the repository directory.
3. Install the required dependencies.
4. Start the backend server and serve the client.
5. Build the JavaScript files using webpack.
6. Run the webpack plugins to generate additional files.
7. Ensure your application is using supported next-gen JavaScript features.
8. Open the text editor in your web browser to create IndexedDB storage.
9. Enter content in the text editor and let it save automatically.
10. Close and reopen the text editor to retrieve the saved content.
11. Click the "Install" button to download the web application as an icon.
12. Load the web application from the downloaded icon on your desktop.
13. Ensure the service worker is registered using Workbox.
14. Pre-cache static assets, including subsequent pages, using the service worker.
15. Deploy the application to Heroku, considering proper build scripts.

## What I Learned:

- Build a web-based text editor.
- Enable offline functionality using a Progressive Web App (PWA) approach.
- Store data persistently using IndexedDB.
- Implement immediate database storage for efficient usage.
- Save and retrieve content within the text editor.
- Set up a client-server folder structure.
- Bundle JavaScript files using webpack.
- Generate essential files (HTML, service worker, manifest).
- Write compatible code in next-gen JavaScript.
- Install the app as a desktop icon.
- Register a service worker for offline caching.
- Deploy the app to Heroku with appropriate build scripts.

In closing, through this challenge I have gained valuable experience in creating a web text editor with offline capabilities, utilizing IndexedDB for data storage, and deploying it to Heroku while ensuring optimal performance.

## License & Copyright ©
#
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [Open Source Initiative Link](https://opensource.org/licenses/MIT)

#
### Copyright © 2024 Mohammad Abbasi
#
```md

MIT License



