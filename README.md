# Cs411project
Team Project 

## Project Description:
Event Finder: We will user users' current location and preferences to find the events fits users input

## Teammates:
* Yin-Ching Lee
* Thomas Lee
* Doruk Savasan

## API:
* Geolocation API: We will use this API to get the distance from users' location to the event
* Ticketmaster API: We will get the genre, time, locations of different events using this API

## Decoupled Structure:
* Flask
Frontend: HTML, CSS, JavaScript
Backend: Python, Flask
Database: Firebase

## How to run the web: 
1. Open terminal
2. type `cd <where you store your folder for this project>`
3. type `python app.py` or `python3 app.py`


## How to play with the Web:
1. On the login page, users can click on login button, and sign in with their Google account (We use Firebase Google OAuth)
2. On the index page, users should first click on the "get my location", and the latitiude and longtitude of the users' current location will be displayed on the page.
3. Users need to enter the genre, date ranges, maximum price, maximum distance, and the state code, then click on submit button.
4. Scroll dowm, a list of events will be displayed, which fits users preferences.
5. If users click on the history button, they will be navigated to another page, where users' past search experiences will be displayed.
6. When users click on the back button on the history page, they will be navigated back to index page.

