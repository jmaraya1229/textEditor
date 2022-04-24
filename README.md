# PWA Text Editor

### Link to deployed application: https://jmaraya-texteditor.herokuapp.com/

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)

## Description
The purpose of this application to allow the user access to a text editor that is readily available online and offline. 

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Installation
To install the application, the user can `git clone` this repo then run `npm install` on the command line to install the required technologies.

## Usage
After completing the installation, the user can run the application by typing `npm start` on the command line. Then, the text editor will be available to access by going to `http://localhost:3000/` on their web browser once the webpack is finished compiling. 

Now, the user will be able to use the text editor. They can type whatever text that they want, and if they leave the webpage and come back, the previous text will still be available.

The user will also be able to install the text editor so that they can access it offline. The user can install the offline version of the text editor by either clicking the `Install!` button on the top left of the page. Doing so will cause a shortcut to the text editor to appear on the user's homepage. The user can then pop out the editor by clicking the arrow that states `To open this link, choose an app`. After clicking it, the text editor should be the only available app to use, then it will pop out of the web browser and onto the screen as its own app. 

### Video of Usage
![video using app](/client/src/images/text-editor.gif)
