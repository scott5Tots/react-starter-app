# Backend - Step 2 - Backend directory
Using the 'touch' command, create a new file called app.js. <br>
The backend server is running in port 9884 <br>
`app.js` configures the Express server with routes for different data entities. This approach allows us to use a modular architecture, where each route is associated with a specific data entity (in our project's case, locations, players, structures, etc). This is also where the `PORT` number is specified — in this example, we're using port 9884. It's important to choose a port that's not already in use by another process and/or students.
![app.js file](https://github.com/scott5Tots/react-starter-app/blob/main/Step%202/assets/Appjs.jpg)<br>
Create a new file called db-connector.js to have your authentication information. For more detailed instructions and explanations on this step, follow the [node.js guide](https://github.com/osu-cs340-ecampus/nodejs-starter-app/tree/main/Step%201%20-%20Connecting%20to%20a%20MySQL%20Database) <br><br>
![app.js file](https://github.com/scott5Tots/react-starter-app/blob/main/Step%202/assets/db-connector.js.png)
---
Finally, update the `package.json` file by adding this start script. Doing so ensures that when you run `npm start`, it will execute the app using `app.js`. <br><br>
![package.json file](https://github.com/scott5Tots/react-starter-app/blob/main/Step%202/assets/package.png)
