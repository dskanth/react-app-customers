This project was initially cloned from: https://github.com/aditya-sridhar/simple-reactjs-app
This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Prerequisites
Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

Install create-react-app
Install create-react-app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app

npm install -g create-react-app
Live Application URL
The Application is deployed in https://aditya-sridhar.github.io/simple-reactjs-app

Click on the link to see the application

Cloning and Running the Application in local
Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

npm install
In order to run the application Type the following command

npm start
The Application Runs on localhost:3000

Application design
Components
Customers Component : This Component displays a list of customers. This Component gets the data from a json file in assets folder

CustomerDetails Component : This Component Displays the details of the selected customer. This Component gets its data from a json file in assets folder as well. This Component is the Child Component of Customers Component

HTTP client
axios library is used to make HTTP Calls

URL
The application has just one url /customerlist which ties to Customers Component
