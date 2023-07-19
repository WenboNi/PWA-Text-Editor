# Progressive Web App Text Editor
This repository contains a progressive web app (PWA) text editor that runs in the browser. The application allows users to create notes or code snippets, with or without an internet connection, and reliably retrieve them for later use.

## Features

-Single-page application with PWA capabilities
-Data persistence using IndexedDB database
-Offline functionality
-Next-gen JavaScript support
-Client-server folder structure
-Backend served via live server
-JavaScript files bundled using webpack
-Generated HTML, service worker, and manifest files
-Installable as a desktop application
-Registered service worker using Workbox
-Pre-cached static assets


## Installation and Setup

1. Clone this repository to your local machine.

    > git clone git@github.com:WenboNi/PWA-Text-Editor.git

2. Navigate to the project's root directory.

    > cd PWA-Text-Editor

3. Install the dependencies using npm

    > npm install --save

## Usage

To run the text editor application, follow these steps:

1. Start the backend server and serve the client by running the following command in your terminal from the project's root directory:

    > npm run start

2. Open the text editor application in your browser by going to localhost:3000.

3. You should see the IndexedDB database storage immediately created when you open the text editor.

4. Enter content into the text editor and click off the DOM window to save the content with IndexedDB.

5. If you close the text editor and reopen it, you will find that the previously saved content is retrieved from IndexedDB.

6. Click on the "Install" button to download the web application as an icon on your desktop.

7. Load the web application, and you will have a registered service worker using Workbox.

8. The static assets will be pre-cached upon loading, including subsequent pages and static assets.

## Live URL

https://blooming-fortress-92562-a3dcb56a67d0.herokuapp.com/ 

## License

This project is licensed under the MIT License.

## Acknowledgements

This text editor application uses the idb package, a lightweight wrapper around the IndexedDB API.

## Contact 

If you have any questions or suggestions, please feel free to reach out to us.

Email: wenboni@yahoo.com
GitHub: https://github.com/WenboNi 

We appreciate your interest and contributions to this project!