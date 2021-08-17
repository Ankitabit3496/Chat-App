# Chat-App
A dockerized real time web application built with Socket.io and Node.js where users can chat with the other users in the room and can share their geographical location if permission is granted. Implemented  the special feature of automatic scrolling upon receiving a new message.

## [Demo](https://ankita-chatapp.herokuapp.com/)

## Features
- The users must join a room to chat with a specific username.

 <p align="center">
 <img src="https://github.com/Ankitabit3496/Chat-App/blob/main/Images/Image_1.png" width="400" height="200" style="float:center">
 </p>
 
- Users can chat with other users of the same room.
- Users can share their geographical location with the others if permission is granted.
- When a new message is received, the page automatically scrolls down.

 <p align="center">
 <img src="https://github.com/Ankitabit3496/Chat-App/blob/main/Images/Image_2.png" width="400" height="200" style="float:center">
 </p>
 
 ## Running It Locally
 *You can directly do `npm install` and run `node src/index.js` but if you don't have npm/node installed, use docker to avoid hassle of downlaoding dependancies.*
 - Make sure you have docker installed.
 - `STEPS`: Use following commands sequentially in the terminal
  1. `docker build .` for building the image.
  2. `docker run -p {LOCALPORTNAME}:{ACTUALPORT} {image}` after obtaining image id from the above command.
  
 ## Author
   [ANKITA](https://github.com/Ankitabit3496)
