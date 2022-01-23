https://movie-time-mlm.herokuapp.com/login

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![badmath](https://img.shields.io/github/issues/Esper06/Movie-Time)
![badmath](https://img.shields.io/github/forks/Esper06/Movie-Time)
![badmath](https://img.shields.io/github/stars/Esper06/Movie-Time)

# Movie-Time
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
## Description

We wanted to find a way to give our users a comfortable, streamlined and efficient way to plan their movie night! Ever spent too long scrolling through Netflix only to be disappointed? Well now you can use our site to plan a movie night for yourself, your friends or your family. All of our members will be able to use the site in order to create a list of all their favourite movies, or movies they planned to watch. The user will be able to **like**, **comment** and **view** trailers of the movies they search.

We took on this task in order to test our skills and further develop our knowledge of node modules and restful APIs. The app allows us to employ all of the skills we have gathered thus far and observe our progression since the last project. Along the way we learned how to use a new npm module **(Flash)**.

```
# Api keys are secured and stored in env file and can be obtained automatically in heroku page.
```
## 🚀
## Mock-Up

The following animation show a mock-up of the app and functionality:


![📸 A gif animation of the app](./assets/screen.gif)


## 🛠️
## Installation 

In order to install the contents of our app, the user must simply open up the repository in their terminal and enter *'npm i'*. This will proceed to install of the necessary npm packages required for the app to function correctly.

```bash
npm i
```

### this will install the following dependencies 
```bash
"dependencies": {
     "bcrypt": "^5.0.1",
    "connect-flash": "^0.1.1",
    "connect-session-sequelize": "^7.1.2",
    "cookie-parser": "^1.4.5",
    "dotenv": "^10.0.0",
    "express": "^4.17.1",
    "express-handlebars": "^5.3.3",
    "express-session": "^1.17.2",
    "mysql2": "^2.3.0",
    "nodemon": "^2.0.12",
    "path": "^0.12.7",
    "sequelize": "^6.6.5",
    "sessions": "0.0.2-7"
  }

```
## 📚
## Run the app

  To use this app, you may need to run the following commands sequencially,

```bash
* mysql -u root -p
* source db/schema.sql;
* quit

* npm run dev
or
* npm run start

you will need to update .nev.sample with your credentials
```
## Usage

The user will first be required to create an account on our site in order to begin searching for their desired movies. After this, the user can use the search bar at the top of their screen to find the movies they may be interested in. After doing so, they will receive a list of potential movies (in the form of buttons) that match their search, which will then lead to another page, allowing that user to watch trailers, like and comment or add it to their list.

## Credits

All of the work found within our project was provided or created by us: Medhi, Matt and Lee. Github Profiles:

## ✅ Mehdi: https://github.com/MehdiMahmud79  
## ✅ Matthew: https://github.com/Esper06 
## ✅ Lee: https://github.com/Lee0997

## ❕ License

MIT License

Copyright (c) 2021 Matthew Walford

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

# webpage
https://movietimeuk.herokuapp.com/
