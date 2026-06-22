# Tic Tac Toe

A classic two-player Tic Tac Toe game built with React.

![Game Preview](public/preview.png)

## 🎮 How to Play

- The game is played on a 3×3 grid
- Player **X** always goes first
- Players take turns placing their mark (X or O) on an empty cell
- The first player to get **3 marks in a row** (horizontally, vertically, or diagonally) wins
- If all 9 cells are filled and no one has won, the game is a draw
- Press **Reset** to start a new game at any time

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- npm

### Installation

```bash
# Clone the repository
git clone https://github.com/CostaLacoste/Tic-Tac-Toe.git

# Navigate into the project folder
cd Tic-Tac-Toe

# Install dependencies
npm install

# Start the development server
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to play.

## 🛠️ Built With

- [React](https://reactjs.org/) — UI library
- [Create React App](https://create-react-app.dev/) — project bootstrapping
- CSS — custom styling

## 📁 Project Structure

```
src/
├── App.js
├── App.css
└── Components/
    ├── Assets/
    │   ├── circle.png
    │   └── cross.png
    └── TicTacToe/
        ├── TicTacToe.js
        └── TicTacToe.css
```

## ✨ Features

- Two-player local gameplay
- Win detection for all rows, columns, and diagonals
- Visual winner announcement
- Reset button to restart the game

## 📜 License

This project is open source and available under the [MIT License](LICENSE).