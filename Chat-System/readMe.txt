step-by-step guide on how to run the Node.js server for the chat system:

1. Open Visual Studio Code.

2. Find the 'Open folder' then find the Chat-System folder,and then select Chat-system then Select folder.
    
3 Open the terminal in Visual Studio Code. selecting "Terminal," and then choosing "New Terminal."

4. In the terminal, run the following commands one by one:
    npm init -y 
    npm install express 
    npm install socket.io 
    npm install ejs
These commands will initialize your project, install the required dependencies (Express, Socket.IO, EJS), and create a package.json file.

5. After the dependencies are installed, run the following command in the terminal: this command will execute the server.js file and start the server.
  type this in the terniminal: 
    node server.js

6. Open your preferred web browser.

7. In the address bar of your web browser, enter the following URL:
    http://localhost:3000 

This will navigate to the chat system running on your local server.

Now you should be able to access and interact with the chat system in your web browser at http://localhost:3000.
