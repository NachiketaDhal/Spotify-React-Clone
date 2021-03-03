## Spotify React Clone

This app is a demo replica of Spotify (using their spotify api) that I decided to create in order to learn React and also have fun. This is not meant for production use, just to have fun locally.

## Project ScreenShots

### Login Page

![alt text](https://github.com/NachiketaDhal/Spotify-clone/blob/master/blob/login.png)

### Main Page

![alt text](https://github.com/NachiketaDhal/Spotify-clone/blob/master/blob/home.png)

## Installation and Setup Instructions

#### Example:

Before the already well known react installation process, place visit spotify developer page and go inside the dashboard. There you can create a new app, and you will get your clientId. Also open the app inside the dashboard and edit settings. Only thing you need to change is redirect url. It is the url your app is running at. By default localhost runs at http://localhost:3000/ so you can copy and paste that if you are just looking to test the app.

Copy your clientId inside `spotify.js` file and also put your `redirectUrl`

Now for the regular react app process you will need `node` and `npm` installed globally on your machine.

Installation:

`npm install`

To Start Server:

`npm run build && npm start`

To Visit App:

`localhost:3000`
