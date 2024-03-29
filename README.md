# Text Editor
![badge](https://img.shields.io/badge/MIT-License-blue.svg)

## Description

JATE is a text editor that runs in the browser. Its a single page application that meets the PWA criteria. It could be useful for developers to create notes or code snippets with or without internet connection so that they could reliably retrieve them for later use.

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Technologies used](#technologies-used)
- [License](#license)
- [Deployed_Link](#deployed-link)
- [Questions](#questions)

## Installation

This program can be run through a browser using the link to the the deployed application. Alternatively, to run this application locally you will need to:

- Clone this repository to receive all of the files. 

- Run "npm install" in the command line of your terminal to set up all of the dependencies.

- Run "npm start" to start the backend and serve the client.

- Go to the url of the application (http//:localhost:3001) to begin using it.

## Usage

To use the application from the command line (after installing dependencies):

1- Open the root directory of the repository in your terminal or bash.

2- Bundle the front-end code by entering (npm run build) in the command line.

3- Start the server by entering (npm run start) in the command line.

4- Go to the port on your local host.

5- Click the "Install" button.

Or

Use the deployed URL to open the deployed application. 

![Alt text](./assets/images/JATE1.png)

Type any code snippet or notes in the editor. The content will be saved in the IndexedDB when the window is unfocused. When you reopen the text editor after closing it, the content in the text editor will be retrieved from the IndexedDB. 

If the Install button is clicked, the web application will be downloaded as an icon in your desktop.

![Alt text](./assets/images/JATE2.png)

The application works without an internet connection.

![Alt text](./assets/images/JATE3.png)

![Alt text](./assets/images/JATE4.png)

##  Technologies used

Node.js, Express.js, IndexedDB, PWA, Heroku

## License

Text Editor is available under the MIT License.

## Deployed Link

https://pwa-text-editor-5-552eb13071c3.herokuapp.com/


## Questions

https://github.com/andedu15
