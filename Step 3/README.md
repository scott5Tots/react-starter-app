A React application is made up of 3 main parts:
* Components
* Pages
* App.js <br>
___
Components are independent and reusable files that work "isolated" from the main app. In this project, our components tell our app how to `get, put, post, delete` data from our backend server. Components are also useful if you want to add a nav bar and modals. <br>
The pages folder defines how each page (ex. http://flip3.engr.oregonstate.edu:5547/players) is structured. App.js is our main page (http://flip3.engr.oregonstate.edu:5547/)<br><br>
![app.js file](https://github.com/scott5Tots/react-starter-app/blob/main/Step%203/assets/Src.png)<br><br>
___
The `App.js` client file demonstrates a basic method for retrieving data from an Express server. It employs a function to fetch SQL data when the component mounts using the axios library for the HTTP GET request.

Please note, this example is simplistic and does not adhere to React best practices. Ideally, server calls should be handled within a separate component or service function rather than directly in the main `App.js` file. This approach helps to maintain clean code, separation of concerns, and better reusability across the application.

![app.js file](https://github.com/scott5Tots/react-starter-app/blob/main/Step%203/assets/Client%20app.png)<br><br>

Before running the React app, add a port number to the start script, like so `PORT=XXXX`. This will make `npm start` run the app in said port. Make sure the port is not taken and is **NOT THE SAME** as your backend port.<br>

![package.json React](https://github.com/scott5Tots/react-starter-app/blob/main/Step%203/assets/port_package.png)
___
The end result should appear as so: <br><br>
![app.js file](https://github.com/scott5Tots/react-starter-app/blob/main/Step%203/assets/Endresult.png)
