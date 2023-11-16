# Debugging
![app.js file](https://github.com/scott5Tots/react-starter-app/blob/main/debugging/assets/Ladybug.JPG)<br><br>
Knowing how to properly test and debug your application is just as critical as your coding prowess. <br>
While console logs can be very helpful, they are often time consuming due to repetition and are limited in scope when it comes to your backend. Postman is a free software app that allows developers to test http methods on databases. It is a great tool to test whether your backend or frontend is the one causing trouble. <br><br>
If the tests come out as expected on Postman, then the problem is most likely related to something in your frontend (wrong call, faulty logic, etc). If the Postman tests fail,then the problem is most likely with your backend logic.<br>
___
### HTTP Method & URL
The method I am testing is POST, I wanted to make sure I could create a new structure record in the server, as I was running into issues when I tried doing it in my frontend.<br><br>
The request is being sent to `http://flip3.engr.oregonstate.edu:4610/structures`, which in my case is where the Express server is running. The endpoint is 'structures', which stores all buildings and structures data for my project.
___
### JSON Body & Response
The JSON data sent to the API should match the database's format, which in this instance includes fields for coordinates, userAssociated, name, and description.<br><br>
The response, which can be seen in the bottom right corner, is a 500 error code. This means there must be something wrong with my backend logic. 
---
**NOTE**

I couldn't get the full response as I don't have access to the SQL servers anymore. The complete response has way more details, which helps to speed up debugging.

---
<br><br>
![POST test](https://github.com/scott5Tots/react-starter-app/blob/main/debugging/assets/post_bug.png)

