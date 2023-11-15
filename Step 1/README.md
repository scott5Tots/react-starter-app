# Overview - Step 1 - Creating Project folders and adding dependencies
Students are expected to have flip servers setup, with a working version of node installed on the server. (more here https://github.com/osu-cs340-ecampus/nodejs-starter-app) 
Not all versions of NodeJS work in the flip servers, but for me version 20.3.1 did the trick. 
The following instructions assumes your SQL tables have been uploaded/imported to a PORT in the flip servers. For more information, visit [NodeJS repo](https://github.com/osu-cs340-ecampus/nodejs-starter-app/tree/main/Step%202%20-%20Loading%20Data%20into%20the%20Database).

## Creating main directories
Create a main directory in the flip servers where you want your app to reside. Change directories to that folder and make a directory called ‘backend’. This directory will have all the backend logic and controllers for the react app. <br>
![Create backend directory](https://github.com/scott5Tots/react-starter-app/blob/main/Step%201/assets/Backend-dir.png) <br>

Next, run <br>
```npm init``` or ```npm init -y``` for quick setup. <br><br><br>
![npm init](https://github.com/scott5Tots/react-starter-app/blob/main/Step%201/assets/Backend-init.png) <br>
Install the following dependencies
* express
* cors
* mysql
![install dependencies](https://github.com/scott5Tots/react-starter-app/blob/main/Step%201/assets/Backend-dep.png) <br>
