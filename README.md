# womensafety

A women safety app which uses a least-cost algorithm to generate the safest route of travel from their current location to any destination using the Google Maps API.

While Google Maps shows the shortest path from a starting point to a destination, this app employs an algorithm which takes safety of a location as a parameter to map the safest route possible with a distance threshold at any time of the day or night.
Technologies Used

    Android Studio
    ReactJS
    NodeJS
    Google Maps SDK
    Google Maps Directions API
    MapBox

Instructions to run Android Studio app

    Import Project 
    Get API keys as per instructions from console.cloud.google.com
    Replace "Your API Key HERE" fields in BasicMapDemoActivity.JAVA and google_maps_api.xml
    Run app

Instructions to run Node Server

    cd into NodeBackend using cd NodeBackend
    Run npm i
    Enter your email credentials in nodemailer.
    Enter "Your API Key HERE"
    Run server using node index.js

Instructions to run React App

    cd into safereact using cd safereact
    Run npm i
    Enter your MAPBOX API Key
    To run react application , npm start

This opens React Application on localhost:3000
