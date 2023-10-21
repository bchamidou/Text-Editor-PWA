Project: TEXT-EDITOR-PWA
 
![License Badge](https://img.shields.io/badge/License-MIT%20License-blue)

## Technologies
***
Technologies used: 
![Technologies](https://img.shields.io/badge/-Git-F05032?logo=Git&logoColor=white)
![Technologies](https://img.shields.io/badge/-JavaScript-007396?logo=JavaScript&logoColor=white)
![Technologies](https://img.shields.io/badge/-Node.js-339933?logo=Node.js&logoColor=white)
![Technologies](https://img.shields.io/badge/-npm-CB3837?logo=npm&logoColor=white)
![Technologies](https://img.shields.io/badge/-IndexedDB-4479A1?logo=IndexedDB&logoColor=white)
![Technologies](https://img.shields.io/badge/-PWA-4479A1?logo=PWA&logoColor=white)

## Table of Contents
*** 
- [Description](#installation)
- [Installation](#installation)
- [Usage](#usage)  
- [Contributing](#contributing) 
- [Contact](#contact)
- [License](#license)

## Description
***
JATE is a text editor that runs in the browser. Its a single page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.
This text editor was built to implement methods for getting and storing data to an IndexedDB database and used a package called idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data.

### User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Installation
***

The installation can be completed by following these instructions:

***Requirments***
[Node.js](https://nodejs.org/en/) | [Express](https://www.npmjs.com/package/express) | [Nodemon](https://www.npmjs.com/package/Nodemon) | [Webpack](https://www.npmjs.com/package/Webpack) | [Babel](https://www.npmjs.com/package/Babel) | [Manifest.json](https://www.npmjs.com/package/Manifest.json) | [IndexedDB](https://www.npmjs.com/package/IndexedDB) | [Heroku](https://www.heroku.com)


1. Clone the GitHub repository to you local computer. Click on the following link.
* Repository link : https://github.com/bchamidou/Text-Editor-PWA

2. Install the required dependencies from the root directory by running the following command in the terminal:
   
     npm i && npm run build

4. Start the app by running the following command in your terminal, this command will start both the server and the webpack development server concurrently, allowing you to see the application in your browser:
   
     npm run start:dev

6. Once the development server is running, you should be able to access the application by opening your web browser and navigating to the specified URL: http://localhost:3000 .

## Usage 
***
To execute the script, open a Git terminal on the main project folder (cloned folder) Run the following command: npm start

### Screenshot
![Alt text]()

### Link 

A link to the code:
```
 https://github.com/bchamidou/Text-Editor-PWA
```
A link to heroku:

 ```
 https://text-editor-pwa-bch-8fd83b851066.herokuapp.com
 ```
## Contributing
***

I  utilized several coding website for help, including STackOverflow, w#schools.com, …. I also watched YouTube video tutorials and the course resources.

## Contats
***

For additional questions, please contact by email: bchamidou@gmail.com.
or my Github page:(https://github.com/bchamidou@gmail.com)

## License
***

This application is covered under the MIT License.

Copyright (c) 2023 Bchamidou.

This software/code is licensed under the MIT License; 
to use this software/code you must agree to follow and comply the License.
A copy of the License can be found at: https://www.gnu.org/licenses/gpl-3.0.md 
