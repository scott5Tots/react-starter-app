# Organization
To maintain a clear and organized project, regardless of its size or the number of features, it's crucial to have a well-organized folder setup. The guide separated the backend and client files into two separate folders. Remember to follow this separation when adding new files, especially as your project keeps growing in complexity. Here's how we organized the files for our project:<br>

<p align="center">
  <img src="https://github.com/scott5Tots/react-starter-app/blob/main/tips%20and%20best%20practices/assets/dir.png" alt="File structure">
</p>

## Security Practices
When you're working on projects that will be posted online, remember to protect your personal information, especially authentication details. A good way to do this is by using a `.env` file in conjunction with your `db_connector.js`. This keeps your login credentials secure. Even experienced developers can sometimes overlook this, so it’s wise to start practicing this habit early. Here’s how our `.env` file was set up:

`.env`
```
# Environment configuration
DB_HOST=classmysql.engr.oregonstate.edu
DB_USER=cs340_[yourONID]
DB_PASSWORD=myPassword
DB_DATABASE=cs340_[yourONID]

```
The `.env` file should be placed in the root directory of your project and should never be committed to version control (e.g., Git), so you should also add `.env` to your `.gitignore` file. <br>

Here's what our `db_connector.js` file looked like: <br>

![db_connector.js with .env file](https://github.com/scott5Tots/react-starter-app/blob/main/tips%20and%20best%20practices/assets/db_env.png)

This setup ensures that sensitive information like database credentials is not hard-coded in your application code, thereby enhancing security.

## Modules Used
Node.js and React offer a vast array of modules and packages, providing great options and flexibility in how you construct your application. Below, we've listed the packages used in our project. You are free to use less or more, just make sure to adjust according to what works best for your project. Remember to remove any unused packages to keep your application streamlined. <br>

### Backend Packages:
- cors
- dotenv
- express
- forever
- mysql
- mysql2
- nodemon
- pm2

### Client Packages:
- @emotion/react
- @emotion/styled
- @fontsource/roboto
- @fortawesome/fontawesome-svg-core
- @fortawesome/free-solid-svg-icons
- @fortawesome/react-fontawesome
- @mui/icons-material
- @mui/material
- @mui/x-data-grid
- @testing-library/jest-dom
- @testing-library/react
- @testing-library/user-event
- axios
- dotenv
- pm2
- react
- react-dom
- react-icons
- react-router-dom
- react-scripts
- react-table
- web-vitals
