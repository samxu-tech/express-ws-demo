# Websocket client/server demo  

## Contents
Using nodejs, express, ws to test websocket client and server


## How to use it

git clone the project
enter the project root folder
npm install

npm start

you can visit the website in http://localhost:8081


## How to modify the client websocket connection address and port

/public/app.js
ws = new WebSocket(`ws://${location.host}`);


## How to modify the server websocket connection port
index.js
server.listen(8081, function () {
console.log('Listening on http://localhost:8081');
})
