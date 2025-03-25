# Chess Game

This is a real-time multiplayer chess game built using **Node.js**, **Socket.IO**, and **chess.js**. The game allows two players to play chess online, with spectators able to watch the game in progress. The chessboard is rendered dynamically in the browser, and the game enforces chess rules using the `chess.js` library.

## Features

- **Real-Time Gameplay**: Players can make moves in real-time, and the board updates instantly for both players and spectators.
- **Role Assignment**: The first two connected users are assigned the roles of "White" and "Black" players, while additional users join as spectators.
- **Drag-and-Drop Interface**: Players can drag and drop pieces to make moves.
- **Chess Rules Enforcement**: The game validates moves and enforces chess rules using the `chess.js` library.
- **Spectator Mode**: Spectators can watch the game without interfering.

## Technologies Used

- **Backend**: Node.js, Express.js, Socket.IO
- **Frontend**: HTML, CSS, JavaScript
- **Chess Logic**: `chess.js` library
- **View Engine**: EJS (Embedded JavaScript)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sakshambajpai1604/Chess.com-clone.git
   cd chess-game
   ```
2. Install dependancies:
   ```bash
   npm install
   ```
3. Start the server:
   ```bash
   npx nodemon
   ```
4. Open your browser and navigate to:
   ```bash
   http://localhost:3000
   ```
   
## How to Play

1. Open the game in two different browser windows or share the link with a friend.
2. The first player to connect will be assigned the **White** pieces, and the second player will be assigned the **Black** pieces.
3. Drag and drop pieces to make moves. The game will enforce valid chess moves.
4. Additional users who join will be **spectators** and can watch the game in progress.
