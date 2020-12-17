# Budget Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

A web application that allows the user to track their expenses and stay on top of their spending.

[Link to application](https://protected-river-91795.herokuapp.com/)

![Budget Tracker Screenshot](https://github.com/nikolaybutnik/budget-tracker/blob/main/public/assets/img/budget-tracker-screenshot.png?raw=true)

## Table of Contents

1. [Installation](#Installation)
2. [Usage](#Usage)
3. [License](#License)
4. [Contributing](#Contributing)
5. [Tests](#Tests)
6. [Questions](#Questions)

## Installation

To install the application locally, run `npm install` to install all dependencies required to run it.

## Usage

To start the application locally, run `node server.js` or `npm run start` from the CLI, and then navigate to localhost:3000 in the browser. [The app is also hosted on Heroku.](https://protected-river-91795.herokuapp.com/)
This application uses MongoDB to keep track of a user's spending. The user may enter a name and an amount for a transaction in the provided fields, and then click either `Add Funds` or `Subtract Funds` to store the transaction in the database. The user's funds are tracked and updated at the top of the screen. The transactions are also dynamically charted to provide the user with a bird's-eye-view of their spending practices.
The application also features elements of PWA. If at any point internet connection is lost, if a transaction is posted at that time it will not be lost but stored in the browser with Indexeddb. Once internet connection is reestablished, the stored transactions are synced with the database. The webpage is also cached on page load, to provide a smooth user experience if connection is unstable.

## License

This project is covered under the MIT license. To find out what is permitted under this license, click the license badge at the top of the README. Alternatively, refer to the LICENSE file in root of the project.

## Contributing

Feel free to submit any pull requests. All pull requests will be considered.

## Tests

No tests are currently written for this application.

## Questions

You may directly send any questions related to this project or any of my other projects to [my email adress](mailto:btnk.nik@gmail.com). To find all my projects visit [my GitHub profile](https://github.com/nikolaybutnik).
