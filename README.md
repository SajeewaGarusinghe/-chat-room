# -chat-room

we will be using Socket.io and HarperDB to build a fullstack, real-time chat application with chat rooms

server side dependencies

npm i axios cors express socket.io dotenv
npm i   express   dotenv
npm i -D nodemon

    Axios is a commonly used package to easily make requests to APIs.
    Cors allows our client to make requests to other origins – necessary for socket.io to work properly.Cross-Origin Resource Sharing
    Express is a NodeJS framework that allows us to write our backend more easily with less code.
    Socket.io is a library that allows the client and server to communicate in realtime – which isn't possible with standard HTTP requests.
    Dotenv is a module that allows us to store private keys and passwords safely, and load them into our code when needed.
    install nodemon as a dev dependency, so we don't have to restart our server every time we make a change to the code – saving us time and energy: