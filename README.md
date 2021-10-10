# Jammming
> This is a React application that allows users to search the Spotify library, create a custom playlist, and save it to their Spotify account.



## General Information
- I undertook this project as part of the Codecademy Full-Stack-Engineer curriculum
- The project was quite extensive and built outside of the Codecademy environment
- The front-end part of the project was basically given. The challenge was to implement the logic behind the app, especially connecting to the Spotify Web API
- THe aim of this project was to work with an external API by informing yourself about its inner working by reading its documentation and integrate its logic in your application



## Technologies Used
- React 17.0.2
- [Spotify Web API](https://developer.spotify.com/documentation/web-api/)



## Features
- Search the Spotify library for song titles 
- Creating a custom playlist with its own name and the ability to edit it
- Adding / removing songs to / from the custom playlists
- Connect the application to the user's Spotify account
- Save the custom playlist(s) to the user's Spotify account



## Screenshots
![Example screenshot](https://i.ibb.co/GpCmDzy/jammming-screenshot.jpg)



## Setup
The dependencies which are necessary to run this app can be found in the package.json file.

1. Clone the repo
2. Install NPM packages in the project folder by running
```
npm install
```
in the terminal.
3. Create a Spotify client ID by registering the app ![here](https://developer.spotify.com/dashboard/)
4. Enter the client ID in jammming/src/util/Spotify.js
```
const clientId = "YOUR_CLIENT_ID_HERE";
```
5. Run the app 
```
npm install
```
6. Visit localhost:3000 in your browser



## Learnings
- Building an appropriate structure of components for the app (e.g., creating respective CSS files for single components)
- Passing the state to specific components
- Work with specific information of the API (e.g., track URIs) to render specific content to the screen
- Implementing a searchbar and its functionality
- Obtaining a Spotify access token
- Implement Spotify search requests by using the impplicit grant flow



## Project Status
The project is finished. In the future I may try to rebuild this project using functional components and React hooks



## Acknowledgements
- This project is part of the [Codecademy](https://www.codecademy.com/) Full-Stack-Engineer Curriculum



