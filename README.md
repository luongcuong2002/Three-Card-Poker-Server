# Three Card Poker Server

Three Card Poker Server is a server application responsible for handling requests from the [Three Card Poker](https://github.com/LuongCuong244/Three-Card-Poker-Client) game. It provides the necessary backend functionalities to support the multiplayer gameplay experience.

## Features
#### 1. User Authentication
- Implements user authentication to ensure secure access to game rooms.
- Supports login with Google and Facebook accounts for convenient user authentication.

#### 2. Game Room Management
- Manages the creation, updating, and deletion of game rooms.
- Allows users to join and leave game rooms based on availability and game room settings.

#### 3. Real-time Communication
- Facilitates real-time communication between players within the same game room.
- Enables players to exchange game-related information, such as card actions and game updates.

#### 4. Game Logic Processing
- Handles game logic and enforces the rules of the Three Card Poker game.
- Processes player actions, calculates game results, and updates the game state accordingly.

#### 5. Data Persistence
- Stores and retrieves game-related data, such as player profiles and game room information.
- Ensures data integrity and allows for the seamless continuation of games.

## Dependencies
- [Nodejs](https://nodejs.org/en/docs) : A JavaScript runtime environment for server-side development.
- [Express](https://expressjs.com/) : A fast and minimalist web application framework for Node.js.
- [Socket.IO](https://socket.io/docs/v4/server-api/) : Enables real-time communication between the server and clients.
- [MongoDB](https://www.mongodb.com/docs/) : A flexible and scalable document-oriented database for storing and managing game-related data.

## Client
- The source code of the client application is shared [here](https://github.com/LuongCuong244/Three-Card-Poker-Client).
