# Simple realtime chat application

## Live sessions:

UI => [https://5db18b328933328c43dbb4fa--zen-jones-343ca0.netlify.com/](https://5db18b328933328c43dbb4fa--zen-jones-343ca0.netlify.com/) <br>
Server => [https://slav-chat-application.herokuapp.com/](https://slav-chat-application.herokuapp.com/)

### React - for local setup you have to comment the 'production' API ENDPOINT line and remove the comment for `localhost:5000`

#### ~/client/src/components/Chat/Chat.js

`cd ./client` <br>
`npm install` <br>
`npm start` - starts the react app on port - 3000 <br>

### Express - for better development experience you have to edit the `package.json` file to start the app with `nodemon` instead of `node`

#### ~/server/package.json

`cd ./server` <br>
`npm install` <br>
`npm start` - starts the Server on port - 5000 <br>

## Technologies

- Express.js
- React
- Socket.io
