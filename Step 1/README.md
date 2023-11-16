# Overview - Step 1 - Creating Project folders and adding dependencies
Students are expected to have flip servers setup, with a working version of node installed on the [server.](https://github.com/osu-cs340-ecampus/nodejs-starter-app) <br>
Not all versions of NodeJS work in the flip servers, but for me version 20.3.1 did the trick. If your having trouble with node, refer to this [post.](https://github.com/scott5Tots/react-starter-app/blob/main/Step%201/assets/node_version.png) If your still having issues, contact your TAs, instructor, or attend Office Hours. <br>
The following instructions assumes your SQL tables have been created in the flip servers under CS340_[yourONID]. For more information, visit the [Node.js repo.](https://github.com/osu-cs340-ecampus/nodejs-starter-app/tree/main/Step%202%20-%20Loading%20Data%20into%20the%20Database)

## Creating backend directory
Create a main directory in the flip servers where you want your app to reside. Change directories to that folder and make a directory called ‘backend’. This directory will have all the backend logic and controllers for the react app. <br><br>
![Create backend directory](https://github.com/scott5Tots/react-starter-app/blob/main/Step%201/assets/Backend-dir.png) <br>

Next, run `cd backend` to change directories. <br>
Now you can initialize node using ```npm init``` or ```npm init -y``` for quick setup. <br><br>
![npm init](https://github.com/scott5Tots/react-starter-app/blob/main/Step%201/assets/Backend-init.png) <br>
Install the following dependencies:
* express
* cors
* mysql <br><br>
![install dependencies](https://github.com/scott5Tots/react-starter-app/blob/main/Step%201/assets/Backend-dep.png) <br>
## Creating client directory
Open a new terminal and in your main project directory run the following command ```npx create-react-app client```. This will make a new directory `client` and install node + react dependencies. This process takes 2-5 minutes to complete, as it downloads and installs all the necessary modules for the React app. Change directory to `client` and use `npm i` to install:
* react-router-dom
* axios
---
This is what the main project directory should look like. <br><br>
![Directory overview](https://github.com/scott5Tots/react-starter-app/blob/main/Step%201/assets/Main-dir.png)
