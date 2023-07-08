# Text-Editor

## Description

Jate is a text editor that runs in the browser. It is a single page application that can runs online and offline, uses data persistence and meets all PWA criteria. The application looks for data in the indexedDB to populate the editor, then if it cannot access that it will use local storage. This applications can be also be used offline, user will need to download to their desktop as an application. This application can be very helpful to developers to  with create notes or code snippets with or without internet connections so users can reliably retrive them in other time.

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Technologies used](#technologies-used)
- [License](#license)
- [How to Contribute](#how-to-contribute)
- [Deployed_Link](#deployed-link)
- [Questions](#questions)

## Installation

This program runs through a browser using the link to the the deployed application. To run this application locally you will need to:

- Clone this repository to receive all of the files. 

- Run ``"npm install"`` in the command line of your terminal to set up all of the dependencies.

- Run ``"npm start"`` or ``"npm run start:dev"`` to start the backend and serve the client.

- Go to the url of the application ``http//:localhost:3000``.

## Usage

Use the deployed URL to open the deployed application. 
--- screenshot --
![Jate]( )

When user types a code snippet or notes in the editor. The content will be saved in the IndexedDB when the window is unfocused. When you reopen the text editor after closing it, the content in the text editor will be retrieved from the IndexedDB.

when the user click on the "Install" button, the web application will be downloaded as an icon in their desktop.

The application works without an internet connection.

##  Technologies 

Node.js, Express.js, IndexedDB, PWA, Heroku

## Credit:

* UCLA EDX BOOTCAMP

## Deployed Link

[Heroku Link]()

## Questions

[Deployed application Link]()

For any addditional information, reach me at 