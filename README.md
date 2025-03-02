Weather-App
forthebadge forthebadge    forthebadge forthebadge forthebadge forthebadge

The Weather App is a real-time project developed using JavaScript, CSS, Express and Handlebars. This project is an interesting project for simply weather forecasting. The user can check the condition of the present-day climate probability and predict whether the day is a cloudy or sunny day. The user can write down the name of any city across the world in the app.  

Get Started
Clone or download this repository. git clone https://github.com/Amulya-coder/Weather-App.git

Create a package.json file for your application. npm init

Now install Express in the weather-app directory and save it in the dependencies list.

npm install express

After that install nodemon as globally npm install -g nodemon

Handlebars Installation

Install using npm

npm install express-handlebars
Setup
To start the server:
cd Weather-App
npm start
Navigate to http://localhost:8000/ in your browser.
Note
Insert the API key that you got from OpenWeatherMap in public/js/main.js

Usage
This view engine uses sensible defaults that leverage the "Express-way" of structuring an app's views. This makes it trivial to use in basic apps:

Directory Structure of Project

.
├── Templates
└── partials
    ├── footer.hbs
    ├── headerLinks.hbs
    ├── navbar.hbs
└── views
    ├── 404error.hbs
    ├── about.hbs
    ├── index.hbs
    ├── weather.hbs

3 directories, 7 files
📷 Screenshots
weather1 weather2
