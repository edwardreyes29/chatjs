# Live Chat Using Socket.io

This project involves socket programming using node.js and socket.io that integrates both client-side and server side code and run on each peer.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Installations

Git clone this repo into your local terminal (Better if in the IDE)

``` bash
git clone https://github.com/jemmamariex3/chatjs.git
```

Enter the directory using basic bash commands

``` bash
cd chatjs
```

Install all dependencies

``` bash
npm install
```
## Running Program

Users are able to set port values of their choice.
Run the following command to get started

``` bash
PORT=<enter-port-num> node chat.js
```

Or PORT can simply be run on 3000 by default: 

``` bash
node chat.js
```
## Contributions

#### Jemma

- Researched and implemented client and server side environment with socket.io
   - Using Node HTTP Server and socket.io
- Worked on the UI/UX of the browser Chat interface
- Researched and implemented readLine for user input and menu prompts
- Implemented the menu interface for terminal
- Retrieved public IP address using network.js
- Figured out how to allow user imput for PORT initialization option
- Set up command for the 'Help' option
- Created disconnectClient() function to terminate selected IP address
- Wrote up the Read Me file

#### Edward
- Researched and implemented client and server side environment with socket.io
- Updated the readLine menu for user input - used inquiry.js
- Created validation functions to make sure socket connections are not duplicated in the clientConnection array
    - (addNewClient(socket), replaceExistingClient(socket), isIPConnected(socket))
- Created the displayConnection function to output list of connected users
- Assisted in research for the disconnectClient function
- Created the function sendMessageId() in order to send individual messages to selected IP users

## Sources
The following resources were used to help build and research for this project:

[Node Chat Tutorial](https://itnext.io/creating-a-chat-with-node-js-from-the-scratch-707896d64593)

[app.listen vs server.listen](https://stackoverflow.com/questions/17696801/express-js-app-listen-vs-server-listen)

[Socket.IO Tutorial With io.js and Express](https://www.programwitherik.com/socket-io-tutorial-with-node-js-and-express/)

[Custom Port](https://gist.github.com/indiesquidge/7fe1d8be1b973f782c97)

[How to set port for express server dynamically?](https://stackoverflow.com/questions/42656326/how-to-set-port-for-express-server-dynamically)

[How to set environment variable for hosting and port?](https://stackoverflow.com/questions/15353724/how-to-set-environment-variable-for-hosting-and-port)

[Simple Node.js prompt](https://coderwall.com/p/v16yja/simple-node-js-prompt)

[Readline](https://gist.github.com/DTrejo/901104)

[socket. handshake.address return ::ffff:127.0.0.1](https://github.com/socketio/socket.io/issues/3337)

[Network Library](https://www.npmjs.com/package/network)

[Using Socket.IO as a cross-browser WebSocket](https://subscription.packtpub.com/book/web_development/9781785880865/1/ch01lvl1sec12/using-socket-io-as-a-cross-browser-websocket)

[Inquiry.js](https://www.npmjs.com/package/inquirer)

[opn](https://www.npmjs.com/package/opn)
