# Travel App Project BY ZOE BALEK

## Overview
This project requires you to create an asynchronous web app that uses Web API and user data to dynamically update the UI. 

## Project Setup
For this app to run, the following dependencies had to be installed first:
1. Node
2. Express
3. Body-Parser
4. Cors
5. Dotenv

You can run `npm install` to install the dependencies.

### Start the app

1. run: npm run-me
2. app is running on http://localhost:3143/

### APIs used:

- Geonames API - this API will allow us to get the coordinates of the place we're searching for.
- Weatherbit API - after getting the coordinates from the Geonames API, this API will get us the weather forecast for the place we're searching for.
- Pixabay - this API will retrieve an image of the place we're searching for.

### To figure out the response fields I need to get back I've used the API documentation:

- Geonames: http://www.geonames.org/export/web-services.html
- Weatherbit: https://www.weatherbit.io/api/weather-history-daily
- Pixabay: https://pixabay.com/api/docs/

Note:
- Geonames doesn't use an API key, instead it uses a username:
http://api.geonames.org/postalCodeSearch?postalcode=9011&maxRows=10&username=demo
