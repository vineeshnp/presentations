# Game backend from scratch using NodeJS
[Click here to register!](https://www.meetup.com/JavaScript-Meetup-Bangalore/events/252775912/)

## About Me
* [Vineesh N P](http://vineeshnp.com)
> Backend Developer [NodeJS and Python] @ [TechJini](https://www.techjini.com)
* [@vineeshvalsalan](https://twitter.com/vineeshvalsalan)

## Intro to game backend
* Few words about what a game backend is supposed to do.
* Existing languages and implementations.

### Intro to sockets
* What, why, when sockets?
* Sockets vs REST api's

### socket.io 
* Intro to the websocket libraries
* Reason to choose library

## Game with a case study of **CHESS** :
> We will try to take, chess as a case study, and explain the rest with a code base biased to chess.

### Architecture : Simple
* An image of simple architecture
* Explaining the components

### game state
* What is game state.
* What are the components of game state.

### Turing Machine based model: state processing(why in scalability) 
* Games are basically a state in memory, which changes wrt to the input from the user.
* This is similar to the turning machine designed by `Alan Turing`.
* Architecture and game state is compared to a Turing Machine

### CODE:
* Code to connect to socket client
* Code to send and receive data from client and server

### concepts of room in games
* Explain the relevance of rooms
* How to create and subscribe to rooms

### Implementing Actions
* Defining methods for each actions
* Starting the game
* Game moves
* Handling conflicts, like when a player makes a move he is not supposed to make.
* Winner declaration, and resetting the game board.

### using engine to validate moves
* Writing the entire game might be time consuming, thus some parts could be reused by some libraries.

### CODE: 
* Implementing concept of rooms
* Doing move validations

## Scaling
* Vertical scaling and Horizontal scaling.
* Socket scaling using broker.
* Game-state scaling using cache servers.
* Message queues.
* Reverse proxy using nginx.

## Architecture : Complex
* Image of architecture involving the above components

## Challenges
* Node is not designed for game backend.
* Handling computations on event loop.
* Importance of doing CPU intensive tasks using golang/rust.
* Need of timers.

## Suggestions
* Forget es5 approach.
* es6 / typescript will be lifesavers.
* Security with tokens
* Rather than writing from scratch, you could use frameworks.[But don't expect a long term support]
* Do profiling to find out time consuming functions.
* For production use game engines.

## Conclusion 
* Conclusion of JS and Game development.
* Q&A.
