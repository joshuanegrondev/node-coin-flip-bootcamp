# 💸 Week08 Bootcamp2019a Project: Node Coin Flip Game

### Goal: Create a simple web application that uses the fs and http modules. Use http to create the server and fs to read your html file. Include vanilla ES6 js in a script tag at the bottom of your html file. Try creating a coin flip guessing game
To use: copy the code and download figlet using npm install figlet from the command line
### How I did it:

- Created a server which would handle requests for html, css, and SJS.
- Had two buttons and a section in the DOM, whenever either button was clicked, an event listener would trigger and make a server request
- The server would calculate a random answer for the coin flip and return a JSON object with the response.
- Based on the response, the callbacks to the fetch would let the user know whether they won or lost based on the random answer.
