
# Ticket reservation app

It was my first experimental app made in Angular, so I am aware that it has a lot of imperfections in the
code. But thanks to this project I learned a lot and I can avoid a lot of bugs in the future. I began with
making a server in express.js and connected it with MongoDB to have a possibility to login and signUp.
Information about a flight is downloaded from api FlyScanner, but some information are set randomly,
because api has not provided them for free. After you choose a place of departure, destination, date and
number of people , you can see available flights (only one flight per day). After clicking the button
"choose" you proceed to the next step which is "choose luggage" and "choose seats" for passengers.
The last step is the summary of your chosen options in this application. App is responsive and written
according to the mobile first standards.

## Warning!
To try all functionality of this app, you have to clone this repository on your computer, because
the back-end of the app stopped working on heroku.

## Technologies

Angular, Scss, Express.js, MongoDB

## Demo

<video src="/fontend/src/assets/ticket.webm />

## Installation

To see all funcionality of this app clone this repository to your computer and then write on terminal:

```bash
npm install
```

## Launch in a browser

To start front-end of application:

```bash
ng serve
```
And to start back-end of application:
```bash
nodemon server.js
```
## To do
- change code to more clean 
- add some spiners when data from api are loading
- add local storage to not loosing data after refreshing page 
- limit seasion to half hour - after this time user will be log out
