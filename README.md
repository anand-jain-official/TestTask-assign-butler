# How to use

1) POST to "/assign-butlers" with request body to get the assigned butlers as JSON response.

2) Available commands :- 

*) "npm start" to start the app. \
*) "npm run dev" to start the app using nodemon. \
*) "npm test" to test the app using mocha and supertest. \

3) Open index.html in a browser to see a textbox where JSON can be entered and submitted by clicking the "Submit" button. The response from api will be shown on the screen. Ensure the api server is running on PORT 5000 by running the command "npm start" in the project directory or by requesting "http://localhost:5000/ping" in your browser to get "pong" as response.