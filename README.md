# Budget Tracker

## Description

This project added offline persistence to an otherwise 'only online' application. Using Budget Tracker, users no longer have to worry about spotty WiFi or cell service. If you happen to go offline while using this app, your changes will be uploaded as soon as you reconnect! Pretty nifty, huh?

You can track your budget from anywhere! We're hosted on an Amazon AWS server, so why not use our app from deep within the Amazon rainforest? It'll still work, I promise!

## Table of Contents

* [Usage](#usage)
* [Credits](#credits)
* [Features](#features)
* [Contribution](#contribution)

## Usage

Load Budget Tracker in your favorite browser (preferably NOT Internet Explorer, even though it'll still work!), and add the initial balance of your budget to the fields at the top of the page. Add other transactions to see your financial fluctuations reflected on a graph! Even if you're stuck with a spotty internet connection, your requests will always make it back to our database, thanks to some clever coding on the back end.

## Credits

Elijah Kanellakis

## GitHub Repository Link

[GitHub Link](https://github.com/kanellakise/pwa-challenge-elk-wk19)

[Link to Deployed Application](https://protected-ridge-69892.herokuapp.com/)

## Features

This project is built with JavaScript, Node, MongoDB, and the Express.js and Mongoose npm packages. The nodemon npm package was used for development.

This project features a complete Service Worker that installs, activates, and fetches cached files to assist with frequent usage of the application.

Thanks to the Service Worker, offline persistance, and a robust manifest, this is the quintessential PWA.

## Contribution

Fork this project's repository and work to your heart's content! You may make a pull request when you feel sufficient progress has been made, and I will review the changes. Thank you!
