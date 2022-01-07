
# BS Scrabble

This is a 2 player multiplayer Scrabble knockoff game using Socket.io to support multiple clients and Vue 
for a responsive drag-and-drop interface.

This was a partner final project for my "Client-Side Programming" class. I designed the UI of the game using Vue and set 
up the `GameBoard` class structure while my partner primarily worked on the server-side validation and scoring.

## Getting Started

First, make sure that Node.js is installed on your machine.

1. To install Node dependencies, use the `npm install` command in the Node command prompt
2. One dependencies are installed, use the `npm start` command to start the server
3. Go to http://localhost:8080 or http://127.0.0.1:8080/ to play!
4. Once 2 clients have connected there can be back-and-forth gameplay!

**Note: only 2 clients can be connected at a time! Any additional clients that navigate to the page will see an alert that there are too many people connected.**

## Screenshots

![Making a Move Screenshot](https://github.com/ben-basten/bs-scrabble/blob/main/screenshots/making-move.png?raw=true)

_Example of what gameplay would look like if it's your move. Experimental letters that have been dragged on the board but not played yet are displayed in a darker orange._

---

![Dialog Box Screenshot](https://github.com/ben-basten/bs-scrabble/blob/main/screenshots/dialog.png?raw=true)

_Example dialog box - they're used for changing player names and communicating turns/victory._

### Have fun!