# Apple Health Web Dashboard

NOTE: Apple Health Web Dashboard is a clone of https://github.com/MaximeHeckel/health-dashboard

## Description: 

Apple Health Web Dashboard provides a daily view of your Apple Health data, like steps, sleep, etc. 

Apple Health Web Dashboard is a react web app (bootstrapped with React Create App). It pulls data from a backend server and displays it. See: https://github.com/markwk/apple-health-sync-backend

## Dependencies
* Should have installed [create-react-app](https://github.com/facebookincubator/create-react-app) globally
  npm install -g create-react-app
* To make a build version, should have installed yarn globally

## Installation and Setup 

* Install dependencies by running $ npm install 
* Set your backend url by editing config/webpackDevServer.config.js to proxy target. It's currently set to target: 'http://localhost:8000',
* To test, run $ npm start
