# SmartBrain-api - v2

## Install, Run

Final project for ZTM course

1. Clone this repo
2. Run `npm install`
3. Run `npm start`
4. You must add your own API key in the `controllers/image.js` file to connect to Clarifai API
5. Add your own database credentials to `server.js` lines 14 to 29

You can grab Clarifai API key [here](https://www.clarifai.com/)

** Make sure you use postgreSQL instead of mySQL for this code base.

## Run

Check in `server.js` the settings for LOCAL vs. DOCKER settings

### Run locally
 
1. Run Beaver Postgres
2. Run `redis-server` in a separate tab

### Run with Docker

1. Start Docker
2. Run `docker-compose up`

## Extra functionalities that it is possible to add

[Udemy course - functionalities to add](https://www.udemy.com/course/the-complete-junior-to-senior-web-developer-roadmap/learn/lecture/10521040#overview).
