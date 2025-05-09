# Tic Tac Toe Game

A modern, interactive Tic Tac Toe game built with React and Vite. Play the game live at [tictactoe256.netlify.app](https://tictactoe256.netlify.app)

## Features

- 🎮 Interactive game board with real-time updates
- 👥 Customizable player names
- 📝 Game history log
- 🏆 Win detection
- 🤝 Draw detection
- 🔄 Game restart functionality
- 🎯 Turn-based gameplay
- 💫 Modern UI with active player highlighting

## Technologies Used

- React 18
- Vite
- CSS3
- JavaScript (ES6+)

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:
```bash
cd tic-tac-toe
```

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm run dev
```

The application will open in your default browser at `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

## How to Play

1. The game starts with Player 1 (X) and Player 2 (O)
2. Players can customize their names by clicking on them
3. Take turns clicking on empty squares to place your mark (X or O)
4. The first player to get three of their marks in a row (horizontally, vertically, or diagonally) wins
5. If all squares are filled and no player has won, the game ends in a draw
6. Click the restart button to start a new game

## Project Structure

```
src/
├── components/
│   ├── GameBoard.jsx
│   ├── Player.jsx
│   ├── Log.jsx
│   └── GameOver.jsx
├── App.jsx
├── index.jsx
├── index.css
└── winning-combinations.js
```

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Built as part of React learning journey
- Inspired by classic Tic Tac Toe game
